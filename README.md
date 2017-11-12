# Absurd History Website

Super basic website for Absurd History.

## How to make a new episode page

* make a new directory in `src/episodes/` with the slug of the episode name. Example directory name: `2-medieval-medicine/`.
* create an `index.html` file inside the newly created directory.
* add a link to the home page `src/index.html`
* copy over html from a previous episode `index.html` into the newly created episode `index.html`, modify the field.
* push to s3 with `$ npm run deploy`
