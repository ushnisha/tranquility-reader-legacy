## Version 2.0:

* Ability to export/save their offline content to a JSON 
  format file. 

* A link for export is provided every time you view the 
  list of urls stored offline (using the read later functionality).

--------------------------

## Version 1.2:

* Changed keyboard shortcut to show/hide menu div

* Moved Menu to the bottom of the window; 
  hide it faster (less obtrusive)

* Tranquility font size will override the page specific 
  cached zoom level

* Support for a background image (FilePicker to select 
  local file)

* Support for custom hex color codes for background, 
  font, links, annotation highlighting

* Converted some hard coded string values to use localization

* Reduced complexity by eliminating support for defaultFontColor
  and defaultBackgroundColor etc.

* Removed support for versions 16.0 - 19.0

* Removed support for private browsing for pre 20.0 versions 
  of firefox (was generating a warning during validation of 
  earlier releases; and is no longer an issue).

* No longer detect documents with minimal content and no longer 
  warn about document still loading (did not help the user 
  experience; more negative feedback than positive regarding 
  these features)

* Now when offline reading list is requested when the active 
  tab is not in tranquility view (or not a html document, 
  such as the "New Tab" view), then the offline reading list 
  is opened in a new tab. 

--------------------------

## Version 1.1.8:

* Check private browsing mode and alert that "Read Later" 
  functionality is not available.

* Minor changes to menu show/hide logic. The menu is now 
  almost completely hidden, and the expand menu button 
  (+) is now moved to the top right of the browser window 
  so that when printing the page, neither the menu nor 
  the button obscure the text on the page.

* Handle url's that point to text files better. Files 
  that have only preformatted content were not being 
  processed correctly (line breaks were being removed 
  from the preformatted contents also).

--------------------------

## Version 1.1.7:

* Ability to edit annotations

* Auto-hide the menu after 10 seconds (the menu was obscuring 
  part of the content). Menu can be expanded using the (+) button.

* Minor enhancements to the algorithm (delete a larger range 
  of hidden elements in the web page) 

--------------------------

## Version 1.1.6:

* Ability to add notes/annotations to offline content; Select a 
  portion of the text and right click to get the context menu 
  "Tranquility - Add Annotation" to add a new annotation.

* The annotation is saved automatically and can be retrieved 
  later. Selected text can be highlighted with a custom color.

* A summary of all the annotations is available via the 
  "View Notes" button. This is a convenient way to collate 
  all notes and compile them for a report (or for later review).

* Please note that at this time, annotations, once added, 
  cannot be edited or deleted. Annotation font sizes are 
  fixed and are not user customizable. 
  These features will be added in a later version.

* The layout of the tranquility mode has been streamlined 
  and given a more minimal appearance. Buttons have been 
  moved from the side to the top. The reading area border 
  has been removed to improve readability.

--------------------------

## Version 1.1.4:

* "Read Later" functionality to store tranquility view of pages for 
  offline reading

* Easy access to "Offline Links" view toolbar menu item or in the 
  tranquility view.

* Easy deletion of articles after reading them

* Unclutter your bookmarks menu by saving them as offline pages

--------------------------

## Version 1.1.3:

### Minor enhancements:

* Support for customization of link color, line width, text-justification.

### Bug fixes:

* Code modified from version 1.1.2 to take care of a corner case where 
  the tranquility version reversed the display order of all the 
  paragraphs in the web page. 

--------------------------

## Version 1.1.2:

* Non-English users can now select the Wikipedia language of choice 
  from the Preferences window

* Images and pre-formatted content will be re-sized to fit within the 
  reading width

* Additional support for multi-page articles. A navigation pane is provided 
  at the top and bottom of the web page to navigate to the Next or Previous 
  page or to a specific numbered page/link, if available

* Code changes to use String Bundles for future localization

* Improved handling of formatted links in the Tranquil Browsing Mode

* If the Print or Single Page View does not return sufficient content 
  Tranquility will now try to process the original page. This may help 
  in some cases where the Print or Single Page View is available only 
  to registered/premium users

* Users can now select the pruning strategy used by Tranquility in its 
  attempt to get a readable web page. The default option is a 
  Conservative pruning strategy. The Moderate and Aggressive pruning 
  strategies may result in truncation of relevant/useful content depending 
  on the structure of the web page

