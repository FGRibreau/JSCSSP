[JSCSSP](http://www.glazman.org/JSCSSP/) - CSS parser in JavaScript [![Gittip](http://badgr.co/gittip/fgribreau.png)](https://www.gittip.com/fgribreau/)
================================

This is a modified version of JSCSSP which remove DOM pollution. (and I'm not the author of JSCSSP).

Usage
---------------------------------------
	var parser = new CSSParser();
	parser.parse("a{color:#FF0OFF;}", false, true);
