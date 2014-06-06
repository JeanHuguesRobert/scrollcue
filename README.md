scrollcue
=========

A visual clue that delimits the newly visible content.

The actual file is currently a gits at [git](git://gist.github.com/639187.git) or [http](http://gist.github.com/639187).

I am using it in simpliwiki and kudocracy.


What is it?
-----------

When scrolling large content, it is sometimes visually difficult to track where the new content is diplayed.

This is because that position keeps moving as long as one scrolls. If you scroll by a small amount, this is not a problem. However, if you scroll in order to fill the screen with the maximum amount of new content (ie kind of 'page down'), it is difficult to know when to stop scrolling.

With scrollcue, there is an horizontal line that delimits the newly visibile content. To 'page down' with scroll, simply scroll until that line reach the top of the screen. To 'page up', scroll until the line reach the bottom of the screen.


Example:
--------

See the effect while browsing long content from c2's wiki thru SimpliWiki [at](http://simpliwiki.com/c2/WhyWikiWorks).


Roadmap
-------

  * move source code to here
  * use grunt to produced minimized version
  * split code to remove jQuery dependency

June 2014, by @jhr


