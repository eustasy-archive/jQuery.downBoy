# [jQuery.downBoy](https://github.com/eustasy/jquery.downboy)

A small jQuery plugin to push your footer to the bottom of your responsive dynamic height page.

[![Build Status](https://travis-ci.org/eustasy/jQuery.downBoy.svg?branch=master)](https://travis-ci.org/eustasy/jQuery.downBoy)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a8cbb7167985494e922bdea60193e74f)](https://www.codacy.com/app/lewisgoddard/jQuery.downBoy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=eustasy/jQuery.downBoy&amp;utm_campaign=Badge_Grade)
[![Maintainability](https://api.codeclimate.com/v1/badges/c16a4c5f30d7917f0931/maintainability)](https://codeclimate.com/github/eustasy/jquery.downBoy/maintainability)
[![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=482426)](https://www.bountysource.com/teams/eustasy/issues?tracker_ids=482426)
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
