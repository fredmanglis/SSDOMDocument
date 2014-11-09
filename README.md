# SSDOMDocument

This is just a class I have extended from PHP's [DOMDocument](http://php.net/manual/en/class.domdocument.php) to use in my templating tasks, so that I can have a means to create pure HTML templates in my projects. It is inspired by [this post](http://www.workingsoftware.com.au/page/Your_templating_engine_sucks_and_everything_you_have_ever_written_is_spaghetti_code_yes_you) and the implementation of a templating engine ([DOMTemplate](https://github.com/Kroc/DOMTemplate))with some of those ideas - you can see the documentation for DOMTemplate [here](http://camendesign.com/code/dom_templating)

I was motivated to build my own engine as a starting point, to understand what the implementation above is doing. This is more bare-bone, and possibly lacks a lot of extras, so, I'd recommend that one use [DOMTemplate](https://github.com/Kroc/DOMTemplate) rather than this project, but you know what, for those of you who like to use this one, I'll be grateful for your input.

On with the show then. . .
