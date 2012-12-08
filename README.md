Acorn Media Player - HTML5 media player - jQuery plugin
=======================================================

Acorn Media Player is a jQuery plugin implementing a custom HTML5 <video> player with a special focus on accessiblity and customization.

There are two articles online on [Dev.Opera](http://dev.opera.com/) describing it's development:

+ [Building a custom HTML5 video player with CSS3 and jQuery](http://dev.opera.com/articles/view/custom-html5-video-player-with-css3-and-jquery/)
+ [A more accessible HTML5 <video> player](http://dev.opera.com/articles/view/more-accessible-html5-video-player/)

Features
--------

### Accessiblity
Acorn Media Player is built with accessibility in mind.
It provides full keyboard control using standard tab-based navigation, screen-reader (and other AT) support, accessible themes, and other accessibility tweaks.

### Closed-Captions
This is yet no native support for closed captioning on HTML5 <video>, but that shouldn't stop you from providing them.
It supports external SRT files just like “real” media players.

### Transcript
Along with closed captions support, the player provides a dynamic transcript generated from the selected captions.

### Other features
Other notable features include:
* Easy customization and themeing
* Fullscreen support
* Buffering indicator
* <audio> support
* Loading indicator
* Remembers volume level using HTML5 localStorage
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

* [Steve Oldham](https://github.com/stephenoldham)


Participate
-----------
Please report any issues you may have using the GitHub issue tracker, and I'll do my best to fix them asap. Also, feel free to fork the project, I'll be glad to add back any improvements.

You can also email me directly at [cristian@ghinda.net](mailto:cristian@ghinda.net). 

License
-------
I know "copyright is for losers", but the media player is dual-licensed under the GPL and MIT licenses. You can use it under whichever of these suits you. 

Fallback?
---------
Acorn Media Player does not provide any fallback for browsers that are old, or don't support the provided video format.

This keeps you, the developer, from being locked into a certain fallback method. Most "other" video implementations(Flash, Silverlight, Java) have a lot of accessibility issues, so I'm not going to choose sides. Also, this way you can do things the way you want, and even if you later decide that you don't want to use this media player, your markup will stay the same and the fallback mechanism you chose will still work.

Take a look at [Video for Everybody](http://camendesign.com/code/video_for_everybody). 

Acorn Media Player is a project by [Ionut Cristian Colceriu](http://www.ghinda.net).