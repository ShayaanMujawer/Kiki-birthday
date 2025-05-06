# How to Deploy Your Birthday Gift Pages to GitHub Pages

This guide will help you deploy your set of HTML pages and assets to GitHub Pages so they can be accessed as a web application from anywhere.

## Prerequisites
- A GitHub account (sign up at https://github.com if you don't have one)
- Git installed on your computer (optional, for command line usage)

## Steps

### 1. Create a New Repository
- Log in to GitHub.
- Click the "+" icon in the top-right corner and select "New repository".
- Name the repository (e.g., `birthday-gift-pages`).
- Choose "Public" visibility.
- Click "Create repository".

### 2. Upload Your Files
You can upload files via the GitHub web interface or use Git command line.

#### Using GitHub Web Interface:
- Go to your new repository page.
- Click "Add file" > "Upload files".
- Select all your HTML files (`Page 1 mem.html`, `page2.html`, `page3.html`, `page4.html`) and all related assets (images, videos, audio).
- Commit the changes.

#### Using Git Command Line:
- Initialize a git repository in your project folder:
  ```
  git init
  git add .
  git commit -m "Initial commit"
  ```
- Add the remote repository URL:
  ```
  git remote add origin https://github.com/yourusername/birthday-gift-pages.git
  ```
- Push the files:
  ```
  git branch -M main
  git push -u origin main
  ```

### 3. Enable GitHub Pages
- Go to the repository "Settings" tab.
- Scroll down to the "Pages" section.
- Under "Source", select the branch (usually `main`) and root folder (`/`).
- Click "Save".

### 4. Access Your Site
- After a few minutes, GitHub will provide a URL like:
  ```
  https://yourusername.github.io/birthday-gift-pages/
  ```
- Open this URL in any browser to view your pages.
- Share this URL with your recipient.

## Notes
- Make sure all links between pages are relative and correct.
- If you add or update files, commit and push changes again to update the site.

If you want, I can help you prepare the files or create a script to automate the upload process.
