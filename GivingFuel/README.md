## GivingFuel

### Step 1
The first step is to copy the files to a host.

### Step 2
To configure the campaign page to pull in extensions, we need to add some code to reference the third-party extensions.

To do this, we use the "raw html" component in GivingFuel:

1. On your form, add a new "raw html" element to the bottom of your form.
2. In the HTML Markup of the element, enter the location of the bootstrapper script:


```html
<script type="text/javascript">
  var fdn_script = document.createElement('script');
  fdn_script.type = "text/javascript";
  fdn_script.src = "//host.com/givingfuel/default.php" + window.location.search;
  fdn_script.onload = function () {
    //do nothing
  };
  document.head.appendChild(fdn_script);
</script>
```

This will dynamically create a <script> element on the page that pulls in the third party code and also pass in any URL GET parameters to the extension code.
