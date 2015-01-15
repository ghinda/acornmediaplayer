Acorn Media Player - jQuery HTML5 media player [![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ghinda&url=https://github.com/ghinda/acornmediaplayer&title=acorn-media-player&language=javascript&tags=github&category=software)
==============================================

Acorn Media Player is a HTML5 media player with a focus on accessibility and customization.

Articles describing its development on [Dev.Opera](http://dev.opera.com/):

+ [Building a custom HTML5 video player with CSS3 and jQuery](http://dev.opera.com/articles/view/custom-html5-video-player-with-css3-and-jquery/)
+ [A more accessible HTML5 <video> player](http://dev.opera.com/articles/view/more-accessible-html5-video-player/)


Features
--------

### Accessibility
Acorn Media Player is built with accessibility in mind.
It provides full keyboard control using standard tab-based navigation, screen-reader (and other AT) support, accessible themes, and other accessibility tweaks.

### Closed-Captions
This is yet no native support for closed captioning on HTML5 <video>, but that shouldn't stop you from providing them.
It supports external SRT files just like desktop media players.

### Transcript
Along with closed captions support, the player provides a dynamic transcript generated from the selected captions.

### Other features
Other notable features include:
* Easy customization and theming
* Fullscreen support
* Buffering indicator
* <audio> support
* Loading indicator
* Remembers volume level using HTML5 LocalStorage
* Easy to use, understand and adapt
* Free and Open Source

How to use
----------
1. Mark-up your &lt;audio&gt; and &lt;video&gt;
2. Include jQuery and jQuery UI Slider
3. Include specific JavaScript and CSS for Acorn Media Player
4. Include the Theme(s)
5. Call the plugin

More details on the [projects webpage](http://ghinda.net/acornmediaplayer/).

Themes
------

These are the themes included with the player:

* access(default theme)
  Includes child theme accesslight

* darkglass
  Includes child theme darkglasssmall

* barebones


Contributors
------------

* https://github.com/stephenoldham
* https://github.com/leslash

License
-------
Acorn Media Player is licensed under the MIT license.

Fallback?
---------
Acorn Media Player does not provide any fallback for old browsers, or those that don't support the provided video format.

You can provide your own fallback using [Video for Everybody](http://camendesign.com/code/video_for_everybody).

Acorn Media Player is a project by [Ionuț Colceriu](http://www.ghinda.net).
