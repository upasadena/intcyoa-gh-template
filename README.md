# Interactive CYOA GitHub Template
A template to easily host Interactive CYOAs on GitHub.

Features:

* Hyperlinks enabled
* IntCyoaEnhancer's Download Progress Indicator included
* Optional code to make your backgrounds static
* Automatic GitHub workflow to republish your site on any change
* Modified CSS file with comments where customizations can be made
    * The only customization so far is the ability to make the Point Bar icons
      white for dark Interactive CYOAs

View the text instructions [below](#instructions) or
[watch the video tutorial](https://www.youtube.com/watch?v=LCvOVB8wZQE).

## Instructions

### Sign up

1. First, [create an account](https://github.com/signup) on GitHub

### Create the repository

1. Press the bright green **Use this template** button at the top of this repo
2. Press **Create a new repository**
3. Give your repository a name, this will be the folder that will be used to
   access your CYOA
4. Press **Create repository**

### Enable GitHub Pages

1. Go into **Settings** → **Pages** and where it says **Build and deployment**
   look for the **Source** dropdown menu. Select **GitHub Actions**

### Uploading your files

1. Press the **Add file** dropdown → **Upload files**
2. Upload your `project.json` (and `images/` if appropriate)

---

That should be all! After a short time (usually ~12s) it should now
automatically begin hosting at `https://YOURUSERNAME.github.io/REPONAME`.

Feel free to remove this file and `LICENSE` to clean up the code even more.

### Video tutorial
Press the thumbnail below to open the video. You may need to open in a new tab
so as to not replace this window.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=LCvOVB8wZQE" target="_blank">
 <img src="http://img.youtube.com/vi/LCvOVB8wZQE/maxresdefault.jpg" alt="Watch the video" width="720" height="405" border="10" />
</a>

## More stuff

### Add the URL to the repository for ease of access
1. Press the settings gear to the right of the **About** section title and
   below the **Star** button.
2. Tick **Use your GitHub Pages website**

Your URL should now display!

### Manually republish without pushing
If you want to republish without adding or modifying files, simply go into the
**Actions** tab → select **Deploy static content to Pages** on the left side →
**Run workflow** → and **Run workflow** again.

### Make your background static
There is a style in `index.html` that you can comment out to make your
backgrounds static.

### Customize CSS styles
There is currently 1 commented CSS customization.

The customizations are:
1. Make the Point Bar icons white for dark Interactive CYOAs

In order to search for where you can make these customizations, simply Ctrl+F
(find) for `CUSTOMIZATION` in the `css/chunk-vendors.58637379.css` file.
`CUSTOMIZATION` is used at the start of comments, where it explains which
customizations can be made.

### Manually do this
If you want to manually do this, check out the **GitHub** section of the ICCT:
[https://icctutorial.pages.dev/publishing/github/][icct-gh]

[icct-gh]: https://icctutorial.pages.dev/publishing/github/
