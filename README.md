# jQuery-Vertical-Carousel
A simple, easily customizable and lightweight vertical carousel plugin using jQuery

<h3>Demo</h3>
<img src="https://raw.githubusercontent.com/haripaddu/jQuery-Vertical-Carousel/master/img/demo1.gif"/>

<h3>How to get the Vertical Carousel running in your application</h3>

<h6>Step 1: Include CSS in your header</h6>
<pre>&lt;link rel="stylesheet" href="jQuery.verticalCarousel.css" type="text/css" /&gt;</pre>

<h6>Step 2: Create HTML with the following structure.</h6>
<pre>
<!-- In order to plugin to work, all the classes that starts with "vc_" should not be changed -->
<!-- This div is needed to wrap the carousel structure and you can add a class or ID of your choice -->
&lt;div class="<strong>yourClassName</strong>"&gt;
	<!-- Anchor tag for Up action -->
	&lt;a href="#" class="vc_goUp"&gt;Up&lt;/a&gt;
	<!-- Anchor tag for Down action -->
	&lt;a href="#" class="vc_goDown"&gt;Down&lt;/a&gt;
	<!-- The HTML code for Carousel and Carousel Items. You can use any container tags instead of UL, LI -->
	&lt;ul class="vc_list"&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
		&lt;li&gt;..&lt;/li&gt;
	&lt;/ul&gt;
&lt;/div&gt;
</pre>

<h6>Step 3: Include the vertical carousel javascript after including jQuery</h6>
<pre>&lt;script type="text/javascript" src="jquery.verticalCarousel.min.js"&gt;&lt;script/&gt;</pre>

<h6>Step 4: Trigger the Carousel</h6>
<pre>
$(".<strong>yourClassName</strong>").verticalCarousel();
</pre>
<p>You can customize the vertical carousel by setting two different parameters</p>
<ol>
	<li>currentItem - You can choose which item to show when loaded</li>
	<li>showItems - You can choose how many items to show from the current Item in the vertical Carousel</li>
</ol>
<p><strong>Example</strong>
<pre>
$(".<strong>yourClassName</strong>").verticalCarousel({
	currentItem: 2,
    showItems: 2
});
</pre>