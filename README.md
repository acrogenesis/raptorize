Raptorize jQuery Plugin
=========

An awesome jQuery plugin that unleahes a Raptor of Jurassic proportions...
Well, technically it's Cretaceous proportions, but we'll let that slide for now.

Fixed version of Raptorize: A jQuery Plugin by Zurb
Original Raptorize jQuery Plugin http://zurb.com/playground/jquery-raptorize


Fixes
------------
This version fixes the need to use jQuery 1.4.3 or jQuery Migrate Plugin (Works with the neweset jQuery versions)
The Horrid spacing zurb had on the js file
Fixed Raptor being displayed when scrolling in iOS 5, 6

This package includes
------------
* An awesome Raptor Graphic courtesy of www.raptorize.com
* MP3 and OGG audio files for the HTML5 audio on Webkit and Firefox
* The jQuery Plugin which makes the magic happen
* The jQuery Library to make all the pieces work together
* An example HTML file that has all the initial setup pieces


How to use
------------

### What you need
First let's attach the scripts and activate the plugin in the footer of your document:

    <script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.js"></script>
    <script src="jquery.raptorize.2.0.js"></script>
    <script type="text/javascript">
       $(window).load(function() {
          $('.myButton').raptorize();
       });
    </script>

The only piece that you need to know here is that you need an anchor or element with the class 'myButton'. And there you have it, you're done!

### The Options

Raptorize can be activated on a click event, a timer which just fires after the page is loaded, or the Konami-Code (that is the default and what is have hooked up above but it only works once per page load).

    <script type="text/javascript">
       $(window).load(function() {
          $('.button').raptorize({
            'enterOn' : 'timer', //timer, konami-code, click
            'delayTime' : 5000 //time before raptor attacks on timer mode
       });
    });
    </script>


### Konami Code
`↑ ↑ ↓ ↓ ← → ← → B A`
Learn more about the Konami Code at https://en.wikipedia.org/wiki/Konami_Code

Contributing
------------

1. Fork it.
2. Create a branch (`git checkout -b my_markup`)
3. Commit your changes (`git commit -am "Cool new feature"`)
4. Push to the branch (`git push origin my_markup`)
5. Open a [Pull Request][1]
6. Enjoy a refreshing 'Insert Favorite Beverage' and wait

License
------------
The MIT License (MIT)
