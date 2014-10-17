---
layout: default
---
dnGREP is a [grep](http://en.wikipedia.org/wiki/Grep) utility for Windows. dnGREP searches files for lines matching a given [regular expression](https://github.com/dnGrep/dnGrep/wiki/Regular-Expressions), text, or [XPath](https://github.com/dnGrep/dnGrep/wiki/XPath) pattern and returns the match in the results tree. See the [wiki](https://github.com/dnGrep/dnGrep/wiki) for more.

Requires Microsoft [.NET 4.0](http://msdn.microsoft.com/en-us/netframework/aa569263.aspx) to run. Version 2.0+ is implemented using WPF framework.

##Features
  * [Shell integration](https://github.com/dnGrep/dnGrep/wiki/Shell-Integration) (ability to search from explorer)
  * Plain text/[regex](https://github.com/dnGrep/dnGrep/wiki/Regular-Expressions)/[XPath](https://github.com/dnGrep/dnGrep/wiki/XPath) search (including case-insensitive search)
  * [Phonetic](https://github.com/dnGrep/dnGrep/wiki/Phonetic) search (using Bitap and Needleman-Wunch algorithms)
  * File move/copy/delete actions
  * Search inside archives (via plug-in)
  * Search MS Word documents (via plug-in)
  * Search PDF documents (via plug-in)
  * [Undo](https://github.com/dnGrep/dnGrep/wiki/Undo) functionality
  * Optional integration with text editor (like notepad++)
  * [Bookmarks](https://github.com/dnGrep/dnGrep/wiki/Bookmarks) (ability to save regex searches for the future)
  * Pattern test form
  * Search result highlighting
  * Search result preview
  * Does not require installation (can be run from USB drive)
  * and more...


_Main Screen:_

![](https://github.com/dnGrep/dnGrep/wiki/Images/grep-main.jpg)


_Options:_

![](https://github.com/dnGrep/dnGrep/wiki/Images/options-window.jpg)


_Shell Integration:_

![](https://github.com/dnGrep/dnGrep/wiki/Images/shell-integration.jpg)

<!-- Show snippets of posts -->
<!-- <div class="posts">
{% for post in site.posts %}
<article class="post">    
<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
<div class="entry">
{{ post.content | truncatewords:40}}
</div>
</article>
<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
{% endfor %}
</div> -->