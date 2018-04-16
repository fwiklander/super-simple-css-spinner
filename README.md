# super-simple-css-spinner
A super simple CSS spinner.<br/>
Mainly here so that I have it easily accessible but added a short description below if you want to use it.

## Usage
Download/copy/clone the js and css files to your project.<br/>
It is recommended to simply copy the files to a folder of your choice so you can easily change the css as you see fit.

Import the js and css files in your html file (or put them inline if that's your flavour).<br/>
Adjust the path accordingly, the example below assumes you have them in root.
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

The outer div will take up the entire screen with a gray background, the inner div is the actual spinner.<br/>
The spinner will display by default when the page has loaded.<br/>
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
