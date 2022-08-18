A web browser takes you anywhere on the internet.
It retrieves information from other parts of the web and displays it on your
desktop or mobile device. The information is transferred using the
Hypertext Transfer Protocol, which defines how text, images and video are
transmitted on the web. This information needs to be shared and displayed
in a consistent format so that people using any browser, anywhere in
the world can see the information.

Sadly, not all browser makers choose to interpret the format in the same way.
For users, this means that a website can look and function differently.
Creating consistency between browsers, so that any user can enjoy the
internet, regardless of the browser they choose, is called web standards.

When the web browser fetches data from an internet connected server, it uses
a piece of software called a rendering engine to translate that data into
text and images. This data is written in Hypertext Markup Language (HTML)
and web browsers read this code to create what we see, hear and experience
on the internet.

Hyperlinks allow users to follow a path to other pages or sites on the web.
Every webpage, image and video has its own unique Uniform Resource Locator
(URL), which is also known as a web address. When a browser visits a server
for data, the web address tells the browser where to look for each item that
is described in the html, which then tells the browser where it goes on the
web page.

The browser's high level structure #

The browser's main components are:

1.The user interface: this includes the address bar, back/forward button,
bookmarking menu, etc. Every part of the browser display except the window
where you see the requested page.

2.The browser engine: marshals actions between the UI and the rendering engine.

3.The rendering engine: responsible for displaying requested content. For
example if the requested content is HTML, the rendering engine parses HTML
and CSS, and displays the parsed content on the screen.

4.Networking: for network calls such as HTTP requests, using different
implementations for different platform behind a platform-independent interface.

5.UI backend: used for drawing basic widgets like combo boxes and windows.
This backend exposes a generic interface that is not platform specific.
Underneath it uses operating system user interface methods.

6.JavaScript interpreter. Used to parse and execute JavaScript code.

7.Data storage. This is a persistence layer. The browser may need to
save all sorts of data locally, such as cookies. Browsers also support
storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.

Browser components

![Browser components](https://i.ibb.co/47jVHx2/browse.jpg)

It is important to note that browsers such as Chrome run multiple
instances of the rendering engine: one for each tab. Each tab runs in
a separate process.
