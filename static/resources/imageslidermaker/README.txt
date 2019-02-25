Image Slider Maker README
=========================
ImageSliderMaker.com


Using in your website
---------------------

Please first make sure you have fully extracted the contents of the zip file.
In Windows, right-click on imageslidermaker.zip and select Extract All...

To get your slider working in your web page, you must add
my-slider.css, ism-2.2.min.js and the slide images to your project
directory and paste the markup (included below) into your HTML.

The directory structure of this package:

  imageslidermaker/
    README.txt
    example.html
    ism/
      css/
        my-slider.css
      js/
        ism-2.2.min.js
      image/
        slides/
          _u/1551043124052_385782.jpg
          _u/1551044253864_96820.jpg
          _u/1551043517307_265228.jpg
          _u/1551043998421_474559.jpg
          _u/1551044528484_89711.jpg
          _u/1551044898782_767200.jpg
          _u/1551045450844_53512.jpg
          _u/1551045426901_508920.jpg
          _u/1551044930351_246896.jpg
          _u/1551045178983_570053.jpg

For a working example, open example.html in your web browser or
follow the instructions below to integrate the slider into your
project.


Step by step instructions
-------------------------

1. Paste the following into the head of your HTML file:

<link rel="stylesheet" href="ism/css/my-slider.css"/>
<script src="ism/js/ism-2.2.min.js"></script>


2. Paste this into the body of your HTML file (at the location where:
   you would like your slider to appear in the page):

<div class="ism-slider" id="Josie">
  <ol>
    <li>
      <img src="ism/image/slides/_u/1551043124052_385782.jpg">
      <div class="ism-caption ism-caption-1" data-delay='200'>Josselyn #12, <br>Sophomore</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551044253864_96820.jpg">
    </li>
    <li>
      <img src="ism/image/slides/_u/1551043517307_265228.jpg">
      <div class="ism-caption ism-caption-0">Josselyn #13, Freshman<br>@Mapfre Columbus Crew<br>Stadium</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551043998421_474559.jpg">
      <div class="ism-caption ism-caption-0">Lancaster Lady Gales<br>2018</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551044528484_89711.jpg">
      <div class="ism-caption ism-caption-0">LHS 1rst Game on Turf<br>1-0 Win vs. Fairfield Union<br>Josselyn nets game winner</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551044898782_767200.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551045450844_53512.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1551045426901_508920.jpg">
    </li>
    <li>
      <img src="ism/image/slides/_u/1551044930351_246896.jpg">
    </li>
    <li>
      <img src="ism/image/slides/_u/1551045178983_570053.jpg">
      <div class="ism-caption ism-caption-1" data-delay='200'>Josselyn #8<br>LSSA Club</div>
    </li>
  </ol>
</div>
<p class="ism-badge" id="Josie-ism-badge"><a class="ism-link" href="http://imageslidermaker.com" rel="nofollow">generated with ISM</a></p>


3. Copy the ism/ directory into the root directory of your project.

   The css, js and image paths are relative, meaning the ism/
   directory should be in the same directory (path) as your HTML
   file containing the slider.


