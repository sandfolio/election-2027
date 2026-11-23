# HT Elections 2027

A static Hindustan Times assembly election prototype covering seven states. Open `index.html` in a browser to preview it. The project has no build or dependency installation step. Keep `index.html` at the root of the folder you serve.

Navigation uses URL fragments, so the prototype can be hosted in a subdirectory without routing configuration. The core interface and illustrations are packaged in the HTML. External articles, video playback, video thumbnails, and some photos need internet access.

## Add to Git

For a new repository, run these commands from the extracted folder.

```sh
git init -b main
git add index.html README.md .gitignore
git commit -m "Add HT Elections 2027 prototype"
```

To send that commit to an existing empty remote, replace `YOUR_REPOSITORY_URL` with its Git URL.

```sh
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

To add the prototype to an existing repository, copy the files into the chosen folder and commit using that repository's current workflow.

The prototype includes sample data, including illustrative manifesto entries and the sample announcement countdown. Constituency follows, ratings, and comments are stored in the current browser.
