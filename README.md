[jQuery.downBoy](https://github.com/eustasy/jquery.downboy)
==============

A small jQuery plugin to push your footer to the bottom of your responsive dynamic height page.

### Implementation

Run on `footer` element.  
```
<script src="jquery.downboy.auto.min.js"></script>
```

Run on custom element, such as `#footer`.  
```
<script src="jquery.downboy.min.js"></script>
<script>
 	$(function() {
		downBoy('#footer'); // Run on load
		window.onresize = function() { // On Resize
			downBoy('#footer'); // Run Again
		};
	});
</script>
```
