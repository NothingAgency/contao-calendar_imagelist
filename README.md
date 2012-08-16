# Calendar Imagelist - Sortable image list for Calendar Events

* Author:		Fabian Gander [cyclodex@nothing.ch](cyclodex@nothing.ch)
* Contributors:	Weyert de Boer [sprog@nothing.ch](sprog@nothing.ch), Stefan Pfister [red@nothing.ch](red@nothing.ch)
* Website: 		[https://www.nothing.ch/](https://www.nothing.ch/)
* Version: 		1.0.1
* Date: 		2012-08-16
* License: 		[GNU Lesser Public License](http://opensource.org/licenses/lgpl-3.0.html)
* Dependencies:	Contao Version from 2.10, dcawizard [https://github.com/isotope/dcawizard](https://github.com/isotope/dcawizard)

## Description
Extends the calendar events with an image gallery. The images can be sorted in the backend using drag and drop and support an optional image caption and link. The Frontend module renders the images in a unsorted list.

## Installation and Usage
1. Make sure the `dcawizard` extension is installed and running properly
2. Copy the files into the _modules_ folder from Contao
3. Update the database (e.g. with the _Extension manager_)
4. Display specific setup:
   event-reader: To show the images in the _event-reader_ be sure to place the "Events Imagelist" _Frontend module_ accordingly in your page layout
   event-list:   If you want to show the images in the _event-list_ be sure to select the proper template in the module `event_list_imagelist`
5. Extend the events with images
6. Enjoy :)

## Change Log

*1.0.1 (2012-08-16)*
* Added support for event-list

*1.0.0 (2012-07-17)*
* initial release
