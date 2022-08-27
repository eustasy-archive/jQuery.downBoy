# [jQuery.downBoy](https://github.com/eustasy/jquery.downboy)

#### Deprecated: You should probably be using [Flexbox](https://web.dev/learn/css/flexbox/) or [Grid](https://learncssgrid.com/) in CSS instead. 

###### A small jQuery plugin to push your footer to the bottom of your responsive dynamic height page.

[![Normal](https://github.com/eustasy/jQuery.downBoy/actions/workflows/normal.yml/badge.svg)](https://github.com/eustasy/jQuery.downBoy/actions/workflows/normal.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/c16a4c5f30d7917f0931/maintainability)](https://codeclimate.com/github/eustasy/jquery.downboy/maintainability)
[![jsDelivr](https://data.jsdelivr.com/v1/package/gh/eustasy/jQuery.downBoy/badge?style=rounded)](https://www.jsdelivr.com/package/gh/eustasy/jQuery.downBoy)

### Implementation

Run on `footer` element.  
```
<script src="https://cdn.jsdelivr.net/gh/eustasy/jQuery.downBoy@1.3.0/jquery.downboy.auto.min.js" integrity="sha256-gblkF/eHYhPMM+XZ1weVZuXsdF2HyRUCqCmSvvRVfcM=" crossorigin="anonymous"></script>
```

Run on custom element, such as `#footer`.  
```
<script src="https://cdn.jsdelivr.net/gh/eustasy/jQuery.downBoy@1.3.0/jquery.downboy.min.js" integrity="sha256-x2jMLmtp0NhzmpxjZ9AnCBTmdCP3za4/fZJimVYwYeE=" crossorigin="anonymous"></script>
<script>
 	$(function() {
		downBoy('#footer'); // Run on load
		window.onresize = function() { // On Resize
			downBoy('#footer'); // Run Again
		};
	});
</script>
```
