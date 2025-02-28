# moveo-analytics-js-tag
JS Head Tag to integrate Moveo One analytics

To install the Moveo One analytics library for web, please follow the instructions below:

1. Add the Moveo One analytics script to your HTML file:

```html
<script src="https://cdn.jsdelivr.net/npm/moveo-one-analytics@latest/dist/moveo-one.min.js"></script>
``` 

2. Initialize the Moveo One analytics instance:

```html
<!-- In the <head> section -->
<script src="https://moveoonestorage.blob.core.windows.net/000-scripts/moveo-one-script.min.js"></script>
<script>
  // Initialize MoveoOne with their token
  const moveo = MoveoOne.init('YOUR_TOKEN_HERE');
  
  // Optionally identify the user
  moveo.identify('user123');
</script>
``` 
