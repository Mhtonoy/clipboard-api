# clipboard-api
It is a simple API that provides access to the operating system’s clipboard. You can paste content on it and even read from it. Pasting the content on the clipboard does not require any permission, but accessing the clipboard’s content is gated behind the Permission API.

##Clipboard
It is asynchronous and provides methods to read and write data to the clipboard. You can use this interface to build a small copy/paste functionality in your application.

##ClipboardEvent
This interface handles the events during the modification of the clipboard data.

##ClipboardItem
This interface represents a single item format used when reading or writing data via the Clipboard API.
