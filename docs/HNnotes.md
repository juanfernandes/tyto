* no modal take that out by default, sensible defaults. use load config.
* although we are going to disable the introModal leave it available and change it to [this](http://imgur.com/a/FQkUm).
* Could I do a clever interactive overlay that shows the different actions highlighted and then can do a click to continue and not show message again?? This could be really useful for people.

* adding card button placement, bottom of column? top right of column? big grey icon over the column but how do you work with the drag part of this? maybe do some mock ups in balsamiq.

* pressing escape on intro modal but I think this has already been fixed.
* localStorage and autosaving so that a users board is saved in the browser. Change save board to become export board.
* google drive or dropbox integration especially useful when it comes to using other devices. skydrive also? I would like to go with google drive first I think.
* here is a link to working with dropbox that someone posted:[link](https://dl.dropboxusercontent.com/u/182037406/js-datastore-api-task-example/index.html)
* inform users about localStorage use and also allow them to disable it and also clear it on demand say with an advanced menu option.
* doing localStorage from onion2k, include JSON2.js??
* but it's as simple as: 

	var ls = window.localStorage;
	var config = JSON.parse(ls.getItem('config')); //load the config
	ls.setItem('config', JSON.stringify(config)); //save the config

* add an undo for the last done action.

* read a book based on UX/UI design :[link](http://pragprog.com/book/lmuse/designed-for-use)

* a small gear for advanced menu concepts??
* open menu by default but rather put the buttons in the header instead of a menu at all right??
* move the actions into the header, bad dropdowns can be seen [here](http://jgthms.com/dont-use-dropdowns-for-a-few-items-only.html) and there was a discussion about getting header actions correct [here](https://support.google.com/mail/answer/2473038?hl=en&ctx=mail) with the basic gist being dont just use icons because that's crazy!!

* a mode for editing columns??? enter edit mode then you can move create and delete columns then when you're out you can play with cards. interesting idea.
* draggable columns eh.

* draggable wasn't supported in safari this is where portlets in jquery may come in very handy especially if we can get a mobile version working with hammer.js
* rearranging of cards there is something in the issues list already for this.

* cookies need to be enabled!.

* sorted the page height using calc, for those wanting a larger space then they can tweak that in syles.

* templates and examples for Quad Charts, Kanban board, Zachman Enterprise Architecture, Lean Canvas, Business Model Canvas. REAL COOL FEATURE. 
	1. [Quad Chart](http://en.wikipedia.org/wiki/Quad_chart)
	2. [Kanban Board](http://en.wikipedia.org/wiki/Kanban_board)
	3. [Enterprise Zachman Framework](http://en.wikipedia.org/wiki/Zachman_Framework)
	4. [Lean Canvas](http://blog.spark59.com/2012/the-different-worldviews-of-a-startup)
	5. [Business Model Canvas](http://en.wikipedia.org/wiki/Business_Model_Canvas)

* email functionality was given a thumbs up *pats back*

* Josip Broz Tito LOL!

* app wide refactoring use coffeescript class if possible.

* float:right to animated menu if left on there.