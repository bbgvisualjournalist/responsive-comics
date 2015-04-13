# responsive-comics
A simple example of using CSS and media queries to create responsive comics based on a 6-column grid. 

##Background
We used this for a [VOA project](http://projects.voanews.com/circumvention/) explaining various online tools for circumventing government censorship efforts.

As part of that project we knew that we:
* wanted to create simple explanations of complex tools
* use vector art that could be repurposed across the explanations, to illustrate recurring concepts.
* needed to support multiple translations (we ended up pulling the translations from [a Google Spreadsheet](https://docs.google.com/spreadsheets/d/123DWrahipU6XOVjnVdTd0kdOBFBlzXuxButFymJ-OmA/pubhtml)).

Unlike a large, static infographic explanation, comic book pages divided up into panels are ideal for reflowing onto different devices.

##How it works
I'm using a 6-column grid. Panels can be subdivided to guarantee that they'll remain grouped on smaller devices. Panels can include additional classes to add borders, tilt the panels or add drop shadows. Text can be styled as narration or inset as speech balloons. Some panels require inline styles to provide positioning.

For comic books that are translated in both left-to-right and right-to-left languages, the panels will be reorganized to flow accordingly. I experimented with automatically flipping the artwork for each panel, but ultimately we decided to provide a separate RTL version of the artwork.

##Inspiration and links
Pablo Defendini's [2012 talk about combining responsive web design and comics](http://radar.oreilly.com/2012/01/responsive-design-pablo-defendini-books-in-browsers.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+oreilly%2Fradar%2Fatom+%28O%27Reilly+Radar%29). He also discusses the benefits of leaving text as text as a way of supporting translation.

There have also been several examples of manually slicing up the pages and serving different panel arrangements for mobile, tablet and desktop, including Joe Sacco's response to [Charlie Hebdo attacks](http://www.theguardian.com/world/ng-interactive/2015/jan/09/joe-sacco-on-satire-a-response-to-the-attacks) in the Guardian and the Washington Post's ['Fox Guy' story](http://www.washingtonpost.com/wp-srv/special/lifestyle/magazine/fox-guy/). 
