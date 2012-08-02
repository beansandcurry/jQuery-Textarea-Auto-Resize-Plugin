jQuery-Textarea-Auto-Resize-Plugin
==================================

A jQuery Plugin that Auto-Resizes textareas as they change

<ul class="feature-list">
  <li>Doesn&rsquo;t mess up with your form events</li>
  <li>Doesn&rsquo;t create additional form elements</li>
  <li>Wide browser support</li>
  <li>Debugging option to see how the height is being measured</li>
</ul>

Download
--------
&rarr; <a href="https://github.com/beansandcurry/jQuery-Textarea-Auto-Resize-Plugin" class="btn">View Project on Github</a><br />
&rarr; <a href="https://raw.github.com/beansandcurry/jQuery-Textarea-Auto-Resize-Plugin/master/autoresize.jquery.js" class="btn">Download Plugin</a>

Installation
------------
&rarr; <a href="http://beansandcurry.com/sandbox/jQuery-Textarea-Auto-Resize-Plugin/demo.html" class="btn">Visit the Instructions and Demos Page</a><br />

	<script src="jquery.js"></script>
	<script src="autoresize.jquery.js"></script>
	<script>
	$(function () {
	  // Apply the autoresize plugin to your textarea
	  $("textarea").autoresize();

	  // Pass the debug parameter to see the mirrored element
	  $("#my-textarea").autoresize({debug:true});
	});
	</script>

Demos
-----
<a href="http://beansandcurry.com/sandbox/jQuery-Textarea-Auto-Resize-Plugin/demo.html#demos" class="btn">Plugin Demos</a>
  
Copyright 2012 Beans & Curry. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.