# gulp-practice

## How to Run

1. [Install Node](http://nodejs.org)

2. Open terminal - check if install went correctly by running
```
node -v
```
  and

  ```
  npm -v
  ```
3.   Then download Gulp
```
npm install -g gulp
```

  - if there are errors
       * try
       ```
       sudo npm install -g gulp
       ```
       (mac only)

       * or change permissions by reading up on [How to Prevernt Permissions Errors](https://docs.npmjs.com/getting-started/fixing-npm-permissions#how-to-prevent-permissions-errors)

4. Check install with
```
gulp -v
```

5. Install dependencies
```
npm install
```

6. Run gulp in terminal
```
gulp
```

7. When revisiting the project run gulp in terminal like in step 6.

## Try It Yourself
- Try Browser Sync! (**my fav**) You can see the code refresh on your mobile device as you save changes! Use the "External" access URL in your phone's browser!

- Also try the SASS compiling by typing in to the sass file, CSS also works, and see the browser refresh  and the CSS file update automatically. (No more Prepros!)

### NOTE!
If there is an error in your code gulp will stop running! Check terminal for error, resolve it, and reload gulp.

### Problem Downloading
 If my download instructions don't work:
 1. Delete node_modules, package-lock, package.json.

 2. Follow [Getting Started with Gulp](https://travismaynard.com/writing/getting-started-with-gulp) for a step by step guide. Use the "dependencies download" listed below once you get to step 5 in the article.

 3. The gulpfile.js I created is what were trying to get terminal to read. Copy and paste my code when creating gulpfile.

## Dependencies download
```
npm install jshint gulp-jshint gulp-sass gulp-concat gulp-uglify gulp-rename browser-sync --save-dev

```

## Sites Referenced
[Stack Overflow -Browser Sync on phone](https://stackoverflow.com/questions/34739846/browser-sync-in-mobile-while-local-development)

[Browser Sync options - server and proxy](https://browsersync.io/docs/options/#option-proxy)

[Browser Sync + Gulp Documentation](https://browsersync.io/docs/gulp)

[Getting Started with Gulp](https://travismaynard.com/writing/getting-started-with-gulp)

[How to Prevernt Permissions Errors](https://docs.npmjs.com/getting-started/fixing-npm-permissions#how-to-prevent-permissions-errors)

[Gulp tutorial](https://youtu.be/1rw9MfIleEg)
