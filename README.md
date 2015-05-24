# Structure

    src
    |---*.html
    |
    |---fragments
    |   |---*.html          //  html fragments to include
    |
    |---js
    |   |---globals.coffee
    |   |---plugins.js
    |
    |---modules
    |   |---module name
    |   |   |---css
    |   |   |   |---global.scss
    |   |   |
    |   |   |---js
    |   |   |   |---global.coffee
    |   |   |   |---plugin.js
    |   |   |
    |   |   |---*.html      // these html files should be treated as fragments only
    |
    |---css
    |   |---globals.scss
    |
    |---files               // contains associated files such as images
    |
    dist
    |
    |---css
    |   |---globals.css
    |
    |---js
    |   |---globals.js
    |   |---plugins.js
    |
    |---*.html
    |
    |---files