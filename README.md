# Personal Site Template

1. Go through each page and make it your own. Replace 'xxx' with your own words to describe your projects.
    - `index.html` is the home page
    - `projects.html` is the projects page
    - `resume.html` is the resume page
    - `project#.html` - each will be a projects page

2. To update an image, save the image you wish to upload to the `assets/images` folder and ensure it is the same name of the image you want to replace. For example, if you want to replace the image on the homepage, that image is `image2.PNG`. Save the image you want to replace that image with as `image2.PNG` and anywhere that image is used should now have the image you uploaded. 

3. Feel free to update the styling if an image is too big or small by adjusting the size on the `<img></img>` tag

**NOTE:** the `tab-icon.png` image is the image that you see on the Browser tab. Update this to whatever image you like. It's best to keep it simple or to use a transparent image but that's not a requirement

4. Upload your resume in with the same method described above for updating images (i.e., replace mine by uploading yours with the same name in the same folder).

4. All links to various pages of the site should work as well as images. You shouldn't have to update them.

5. Once you're done and you've checked your pages look good by clicking through each one (preferably with Live Server, see TIP below), you need to host your site. Follow these [instructions](https://pages.github.com/).
    - Make a Github account at `https://github.com/`
    - **IMPORTANT:** Create a repository named `<username>.github.io` where `<username>` is your username that you created on Github 
    - Download the Git CLI (Git command line interface) at https://git-scm.com/downloads/
    - Reopen Visual Studio Code in the folder `/personal-site-starter`
    - Go to `Terminal` > `New Terminal` at the top menu of Visual Studio Code
    - Run the following commands
        - Ensure Git is downloaded by typing in the following command `git --version`. If an error occurs where it doesn't recognize the word `git`, then you need to reinstall because the installation must not have gone through properly
        - Run `git config --global user.name "yourusername"` in terminal
        - Run `git config --global user.email "email@youremail.com"` in terminal
        - Run `git clone https://github.com/username/username.github.io` in terminal
        - Run `git add .`
        - Run `git commit -m "Initial commit"`
        - Run `git push -u origin main`
    - Fire up a browser and go to https://username.github.io to see your hosted site.

**TIP:**
To see your pages hosted live on your computer, use Live Server. You can download this using the Extensions tab on the left side menu (looks like 4 blocks). Search for Live Server and install it. It should be the first result. To use it, right click on the html page you want to "server" and click "Open with Live Server." The page should open in your Browser exactly how it will appear when the site is hosted. Every time you save the page, it'll live update in your Browser. If it gets buggy, just try reopening with Live Server again.