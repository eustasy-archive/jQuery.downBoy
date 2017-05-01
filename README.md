# [jQuery.downBoy](https://github.com/eustasy/jquery.downboy)

A small jQuery plugin to push your footer to the bottom of your responsive dynamic height page.

[![Build Status](https://travis-ci.org/eustasy/jQuery.downBoy.svg?branch=master)](https://travis-ci.org/eustasy/jQuery.downBoy)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a8cbb7167985494e922bdea60193e74f)](https://www.codacy.com/app/lewisgoddard/jQuery.downBoy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=eustasy/jQuery.downBoy&amp;utm_campaign=Badge_Grade)
[![Code Climate](https://codeclimate.com/github/eustasy/jquery.downBoy/badges/gpa.svg)](https://codeclimate.com/github/eustasy/jquery.downBoy)
[![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=482426)](https://www.bountysource.com/teams/eustasy/issues?tracker_ids=482426)

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
