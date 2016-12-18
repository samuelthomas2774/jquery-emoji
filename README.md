jQuery Emoji Plugin
===================

A simple, lightweight jQuery plugin for [emoji](http://www.emoji-cheat-sheet.com/) parser. :tounge:

[HarryUK](https://github.com/harryuk): updated by HarryUK
	+ :gaypride: :golfguy: :golfgirl: :mfinger: :horserider:

Installation
------------

Include script after the jQuery library (unless you are packaging scripts somehow else):

Requires jQuery 1.8 or later.

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.0/jquery.min.js"></script>
<script src="/path/to/jquery.emoji.js"></script>

```

Usage
-----

Very simple.

```html
<script type="text/javascript">
$(document).ready(function(){
    $(".comment").each(function(i, d) {
        $(d).emoji();
    });
});
</script>

```

```html
<div class="comment">
    <p>:+1:</p>
</div>

```

You can also change the url of emojis:

```js
$(".comment").emoji(emoji_url_temp);
// Or...
$.emoji.url = emoji_url;

```

Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Author
------

[linyows](https://github.com/linyows)

License
-------

Copyright (c) 2012 linyows Licensed under the MIT license.
