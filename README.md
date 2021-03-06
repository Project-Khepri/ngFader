# ngFader
A simple, responsive and pure AngularJS fading slideshow directive that requires no jQuery!

## Demo
You can see a working demo [here.](http://www.thetexans.org)

## Dependencies
ngFader requires ngAnimate for the fading transitions and ngTouch for mobile swiping gestures. 

ngAnimate:
https://angularjs.org/ <br>
ngTouch:
https://angularjs.org/

## Setup Instructions
1. Link the ngFader CSS in your header:<br>
<pre><code>\<link type="text/css" rel="stylesheet" href="css/ngFader.css"></code></pre>
2. Add the ngFader directive script tag in your header: <br>
<pre><code>\<script src="js/directives/ngFader.js"></script></code></pre>
3. Add 'ngFader' as a module dependancy - make sure ngAnimate and ngTouch is listed as a dependancy as well:
<pre><code>angular.module('yourAppModule', ['ngAnimate', 'ngTouch', 'ngFader']);</code></pre>
4. In the ngFader directive, list your image locations in the “scope.images” array: <br>
<pre><code>scope.images = [{<br>
		src: 'img/slideshow/slideshow_Image_1_low.jpg',<br>
		alt: 'Add your image description here'<br>
		}, {<br>
		src: 'img/slideshow/slideshow_Image_2_low.jpg',<br>
		alt: 'Add your image description here'<br>
		}, {<br>
		src: 'img/slideshow/slideshow_Image_3_low.jpg',<br>
		alt: 'Add your image description here'<br>
		}, {<br>
		src: 'img/slideshow/slideshow_Image_4_low.jpg',<br>
		alt: 'Add your image description here'<br>
}]</code></pre>
5. Add <code>\<ng-fader>\</ng-fader></code> where you want the fader to show.<br>


## Donate 
Github charges me a monthly fee to contribute this code to our development community. Help me cover the cost by donating via [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2SYBU2SUZCJUE).



