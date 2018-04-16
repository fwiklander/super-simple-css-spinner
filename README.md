# super-simple-css-spinner
A super simple CSS spinner

## Usage
Download/copy/clone the js and css files to your project.
Import the js and css files in your html file (or put them inline if that's your flavour).
Adjust the path accordingly, the below example assumes you have them in root.
```html
<head>
  <link rel="stylesheet" href="spinner.css" />
  <script src="spinner.js"></script>
</head>
```

Create two divs in your body element
```html
<body>
  <div class="spinner">
    <div class="loader">
    </div>
  </div>
</body>
```

The outer div will take up the entire screen with a gray background, the inner div is the actual spinner.
The spinner will display by default when the page has loaded.
If you wish to set it hidden at startup simply add a "display: none" to the style attribute as shown below.

```html
<body>
  <div class="spinner" style="display: none;">
    <div class="loader">
    </div>
  </div>
</body>
```

To toggle the spinner make function calls to hideSpinner() and showSpinner().
