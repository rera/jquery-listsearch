jQuery listSearch
===============

This is a tiny jQuery plugin which prepends and wires a search box to html list(s).

## Args

Currently, listSearch only accepts one parameter: 
<dl>
	<dt>searchclass</dt>
	<dd>The CSS class which is attributed to the search input. Default: none</dd>
</dl>


## Usage

1. Include jQuery
2. Include plugin
3. Initialize with jQuery selector

```
<script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
<script src="jquery.listSearch.js"></script>

<script type="text/javascript">
	$(document).ready(function() {
		var args = { 'searchclass' : 'searchbox' };
		$('ul.searchable').listSearch(args);
		
		// or just $('ul.searchable').listSearch(); to omit css class on search box
	});
</script>
```