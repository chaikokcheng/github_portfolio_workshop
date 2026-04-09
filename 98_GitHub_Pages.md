# The Complete Guide to Hosting a Website on GitHub Pages

GitHub Pages is a free hosting service that takes HTML, CSS, and JavaScript files directly from a repository on GitHub and publishes them as a website. 

The easiest way to get started is by creating a User Page, which will give you a customized URL like https://yourusername.github.io.

---

## Option 1: The Root "User Page"
*Creates a website at exactly `https://yourusername.github.io`*

**Note:** You can only have one User Page per GitHub account, and the repository name must match your username exactly.

### Step 1: Create the Repository
1. Log in to [GitHub](https://github.com).
2. Click the **+** icon in the top-right corner and select **New repository**.
3. Name the repository **`yourusername.github.io`** (Replace "yourusername" with your exact GitHub username).
4. Set the repository to **Public**.
5. Check the box to **Add a README file**.
6. Click **Create repository**.

### Step 2: Add Your HTML File
1. Inside your new repository, click **Add file** > **Create new file**.
2. Name the file **`index.html`**.
3. Add your HTML code. If you just want to test it, paste this:
   ```html
   <!DOCTYPE html>
   <html>
     <head>
       <title>My GitHub Page</title>
     </head>
     <body>
       <h1>Hello, World!</h1>
       <p>My site is live.</p>
     </body>
   </html>```

4. Click the Commit changes... button.

5. Enter a brief commit message and click Commit changes.

### Step 3: Verify Deployment
1. Go to your repository's Settings tab.

2. Click Pages in the left sidebar.

3. Under "Build and deployment", ensure the Source is Deploy from a branch.

4. Under "Branch", select main (or master) and /(root), then click Save.

5. Wait 1-2 minutes, then visit https://yourusername.github.io to see your live site!
  
