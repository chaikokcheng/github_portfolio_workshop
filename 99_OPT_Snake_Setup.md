# How to Set Up the GitHub Snake Animation 🐍

This guide will walk you through adding the fun, animated snake that eats your contribution graph to your GitHub Profile README.

## 1. Create the File in Your Repository

You need to put this YAML file inside a specific hidden folder called `.github/workflows`.

1. Go to your GitHub profile repository (usually `chaikokcheng/chaikokcheng`).
2. Click the **Add file** button, then select **Create new file**.
3. In the "Name your file..." box, type exactly this:
   `.github/workflows/snake.yml`
   *(Notice that typing the `/` automatically creates the folders).*
4. Paste your YAML code into the main text area.

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *" # runs daily
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: username
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
## Make sure for github_user_name put your account username

5. Click **Commit changes...** at the top right and save it to your main branch.

## 2. Give GitHub Actions Permission to Write

Your script creates a new branch called `output` to store the generated images. By default, GitHub Actions might not have permission to do this.

1. In your repository, click on the **Settings** tab at the top.
2. On the left sidebar, scroll down to **Actions** and click **General**.
3. Scroll all the way down to the **Workflow permissions** section.
4. Select **Read and write permissions**.
5. Click **Save**.

## 3. Run the Action Manually (The First Time)

Your script is scheduled to run daily at midnight (`cron: "0 0 * * *"`), but it also has `workflow_dispatch:`, which means you can force it to run right now.

1. Go to the **Actions** tab at the top of your repository.
2. On the left sidebar, click on **Generate Snake** (the name of your workflow).
3. On the right side, click the **Run workflow** dropdown button, and click the green **Run workflow** button.
4. Wait a minute or two. You should see a green checkmark indicating it ran successfully.

## 4. Verify the Images Were Created

1. Go back to the main page of your repository (`<> Code` tab).
2. Click the branch dropdown (where it says `main`).
3. You should now see a new branch called `output`. If you click it, you will see a `dist` folder containing `github-snake.svg` and `github-snake-dark.svg`.

## 5. Display the Snake on Your README

Now you just need to show the animation on your actual profile page!

1. Go back to your `main` branch and edit your `README.md` file.
2. Paste the following HTML code where you want the snake to appear. This specific code handles both Light and Dark mode automatically:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/username/username/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/username/username/output/github-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/username/username/output/github-snake.svg">
</picture>
```

3. Commit your `README.md`, and your snake animation should now be live and will update automatically every day!

