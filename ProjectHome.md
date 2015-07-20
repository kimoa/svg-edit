# Introduction #

SVG-edit is a fast, web-based, JavaScript-driven SVG drawing editor that works in any modern browser.

**All development is now taking place over on github:  https://github.com/SVG-Edit/svgedit.  Please send your pull requests that way**

For usage questions on SVG-Edit, please ask at http://stackoverflow.com/tags/svg-edit/

If you have bug fixes, feel free to add to the [issue tracker](https://code.google.com/p/svg-edit/issues/list) or mention on the mailing list, but a reply may not be forthcoming at this point unless someone happens to have interest and ability in the issue.

# Recent news #
  * 2014-04-17 (with 2014-04-22 [zip](http://svg-edit.googlecode.com/svn/branches/2.7/build/svg-edit-2.7.1.zip) addition) 2.7 and stable branches updated to reflect 2.7.1 important bug fixes for the embedded editor.
  * 2014-04-07 [SVG-edit 2.7](http://svg-edit.googlecode.com/svn/branches/2.7/) was released (Note that Google has [discontinued new project Downloads](http://google-opensource.blogspot.hk/2013/05/a-change-to-google-code-download-service.html) via Google Code so we had to commit the [zip package](http://svg-edit.googlecode.com/svn/branches/2.7/build/svg-edit-2.7.zip) into the 2.7/stable branch). Features detailed at VersionHistory.
  * 2013-11-07 [community conference call](CommunityConferenceCall5.md) (You can listen to the recording)
  * 2013-10-10 [community conference call](CommunityConferenceCall4.md) (You can listen to the recording)
  * 2013-04-09 [community conference call](CommunityConferenceCall3.md) (You can listen to the recording)
  * 2013-02-12 [community conference call](CommunityConferenceCall2.md) (You can listen to the recording)
  * 2013-01-15: [SVG-edit 2.6](https://code.google.com/p/svg-edit/downloads/detail?name=svg-edit-2.6.zip&can=2&q=) was released

# Demos #
Try out the <b><a href='http://svg-edit.googlecode.com/svn/branches/stable/editor/svg-editor.html'>latest stable release</a></b> (or as a [download](http://svg-edit.googlecode.com/svn/branches/stable/build/svg-edit-2.7.zip)).

For the adventurous ones, please do try out the [trunk build demo](http://svg-edit.googlecode.com/svn/trunk/editor/svg-editor.html) (This is the development code of the next version).

# Videos / Screencasts #
  * [SVG-edit 2.4 Part 1](http://www.youtube.com/watch?v=zpC7b1ZJvvM)
  * [SVG-edit 2.4 Part 2](http://www.youtube.com/watch?v=mDzZEoGUDe8)
  * [SVG-edit 2.3 Features](http://www.youtube.com/watch?v=RVIcIy5fXOc)
  * [Introduction to SVG-edit](http://www.youtube.com/watch?v=ZJKmEI06YiY) (Version 2.2)

# Features #
SVG-edit is an online vector graphics editor that uses only JavaScript, HTML5, CSS and SVG (i.e. no server-side functionality).  SVG-edit has the following features:

<table><tr><td>
<ul><li>Free-hand drawing<br>
</li><li>Lines, Polylines<br>
</li><li>Rects/Squares<br>
</li><li>Ellipses/Circles<br>
</li><li>Polygons/Curved Paths/Stars<br>
</li><li>Stylable Text<br>
</li><li>Raster Images<br>
</li><li>Select/move/resize/rotate<br>
</li><li>Undo/Redo<br>
</li><li>Color/Gradient picker<br>
</li><li>Group/ungroup<br>
</li><li>Align<br>
</li><li>Zoom/pan<br>
</li><li>Layers<br>
</td>
<td>
</li><li>Convert Shapes to Path<br>
</li><li>Wireframe Mode<br>
</li><li>Save drawing to SVG<br>
</li><li>Linear Gradient Picking<br>
</li><li>View and Edit SVG Source<br>
</li><li>UI Localization ()<br>
</li><li>Resizable Canvas<br>
</li><li>Change Background<br>
</li><li>Draggable Dialogs<br>
</li><li>Resizable UI (SVG icons)<br>
</li><li>Open Local Files<br>
</li><li>Import SVG into Drawing<br>
</li><li>Connector lines and Arrows<br>
</td>
<td>
</li><li><a href='http://code.google.com/p/svg-edit/wiki/ExtensionDocs'>Plugin Architecture</a>
</li><li>Smoother freehand paths<br>
</li><li>Editing outside the canvas<br>
</li><li>Increased support for SVG elements<br>
</li><li>Add/edit Sub-paths<br>
</li><li>Multiple path segment selection<br>
</li><li>Support for foreign markup (MathML)<br>
</li><li>Radial Gradients<br>
</li><li><a href='http://code.google.com/p/svg-edit/wiki/ConfigOptions'>Configurable Options</a>
</li><li>Eye-dropper tool<br>
</li><li>Stroke linejoin and linecap<br>
</li><li>Client-side export to PNG, JPEG, BMP, WEBP<br>
</td></tr></table></li></ul>

SVG-edit works directly in the browser.  There are several side projects included in the repository: A Firefox Add-on, an Opera Widget, and a Google Wave Gadget, but they have been upgraded to work with the current code and current browsers.

In browsers that support the W3C File API or via [WebAppFind](https://github.com/brettz9/webappfind/), this editor allows you to open local files.  The set of browsers in which this supported is: Firefox 3.6+, Chrome 6+, Safari 5+, and Opera 11.10+ (builds from 2011-04-05 onwards).

# Supported browsers #

The following browsers had been tested for 2.6 or earlier and will probably continue to work with 2.7.

  * Firefox 1.5+
  * Opera 9.50+
  * Safari 4+
  * Chrome 1+
  * IE 6+ had been supported as of version 2.6 via [Chrome Frame plugin](http://code.google.com/chrome/chromeframe/) and may still work for some features, but only IE 9+ will be supported going forward

# Support the project #
If you use SVG-edit, add to your Ohloh.net stacks:
&lt;wiki:gadget url="http://www.ohloh.net/p/325148/widgets/project\_users.xml" height="100" border="0"/&gt;

# Further Reading #
  * [Projects that use SVG-edit](ProjectsThatUseSvgEdit.md)
  * [Reviews](Reviews.md)
  * [How to participate](HowToParticipate.md)
  * [Frequently Asked Questions](FrequentlyAskedQuestions.md)
  * [Tips and Tricks](TipsAndTricks.md)
  * [Roadmap](Roadmap.md)
  * [Governance](Governance.md)
  * [Code Refactoring](CodeRefactoring.md)
  * [Version History (release notes)](VersionHistory.md)
  * This editor depends on many other open-source projects.  See [Acknowledgements](Acknowledgements.md) for details.