# Awesome Kramdown

A collection of awesome kramdown goodies for the converter for (structured) text with formatting markup in markdown conventions  
made with ♥ in Vienna ;-)


_Contributions welcome. Anything missing? Send in a pull request. Thanks._



## Headquarters (HQ)

_a fast converter in Ruby without any C extensions for (structured) text with formatting markup in markdown_

- **kramdown** (web: [kramdown.gettalong.org](http://kramdown.gettalong.org), gem: [kramdown](https://rubygems.org/gems/kramdown), rdoc: [kramdown](http://rubydoc.info/gems/kramdown))
  - [Quick Reference](http://kramdown.gettalong.org/quickref.html)
  - [Syntax](http://kramdown.gettalong.org/syntax.html)
  - [Documentation](http://kramdown.gettalong.org/documentation.html)
    - Readers/Parsers (Input)
      - [Github Flavored Markdown (GFM)](http://kramdown.gettalong.org/parser/gfm.html)
    - Writers/Converters (Output)
      - [LaTeX](http://kramdown.gettalong.org/converter/latex.html) - TeX Typesetting
      - [Man](https://kramdown.gettalong.org/converter/man.html) - Man(ual) Pages in groff format
   - [Official News & Updates](http://kramdown.gettalong.org/news.html) 


_Support_

- [Official Users Mailing List](http://groups.google.com/group/kramdown-users)


_Sources_

- **kramdown** (github: [gettalong/kramdown](https://github.com/gettalong/kramdown))

_Made By_

- **Thomas Leitner** (twitter: [_gettalong](https://twitter.com/_gettalong), github: [gettalong](https://github.com/gettalong))
  - [Q&A w/ Thomas Leitner](https://github.com/statictimes/questions/blob/master/01-thomas-leitner-kramdown.md) by Static Times, Feb 2016
  - [Using Markdown with the kramdown Library and Tools](http://talks.gettalong.org/2016-02-vienna-html) - talk slides (in HTML) from the Vienna.html meetup in Feb 2016 by Thomas Leitner


## Articles, Posts, etc.

- [kramdown Tips & Tricks](https://about.gitlab.com/2016/07/19/markdown-kramdown-tips-and-tricks) by Marcia Ramos (GitLab), Jul 2016
- [kramdown gem - turn easy-to-read and easy-to-write wiki-style plain text in markdown into hypertext](http://planetruby.github.io/gems/kramdown.html) - Planet Ruby Gem of the Week Series, Jan 2015
- [Making Markdown more HTML5 with kramdown](http://kalifi.org/2015/04/html5-markdown-kramdown.html) by Kari Silvennoinen, April 2015


## Parsers & Extensions

**kramdown-rfc2629** (gem: [kramdown-rfc2629](https://rubygems.org/gems/kramdown-rfc2629), github: [cabo/kramdown-rfc2629](https://github.com/cabo/kramdown-rfc2629)) by Carsten Bormann et al

an RFC7749 (XML2RFC) generating backend for the kramdown markdown parser. Mostly useful for RFC writers.

**govspeak** (gem: [govspeak](https://rubygems.org/gems/govspeak), github: [alphagov/govspeak](https://github.com/alphagov/govspeak)) by Ben Griffiths, James Stewart et al 

a set of extensions to markdown layered on top of the kramdown library for use in the UK Government Single Domain project

**writedowm** (gem: [writedowm](https://rubygems.org/gems/writedown), github: [adamhollett/writedown](https://github.com/adamhollett/writedown)) by Adam Hollett et al  

a set of extensions to markdown layered on top of the kramdown library, extensions include: asides, checkboxes, figures, image dimensions and more

**kramdown-man** (gem: [kramdown-man](https://rubygems.org/gems/kramdown-man), github: [postmodern/kramdown-man](https://github.com/postmodern/kramdown-man)) by Hal Brodigan et al 

a kramdown converter for converting markdown files into man pages

**kramdown-asciidoc** (github: [opendevise/kramdown-asciidoc](https://github.com/opendevise/kramdown-asciidoc)) by Dan Allen et al

a kramdown converter for converting markdown files into asciidoc(or) for using docbook 'n' friends

**kramdown Facebook Instant Article Converter** (github: [contentful-labs/kramdown-instant-article](https://github.com/contentful-labs/kramdown-instant-article)) by Rouven Weßling et al

custom converter for kramdown to create markup optimized for Facebook Instant Articles.

**slackdown** (github: [houston/slackdown](https://github.com/houston/slackdown)) by Bob Lail et al 

a kramdown converter for converting markdown text to slack's simplified markdown


**repositext** (github: [imazen/repositext](https://github.com/imazen/repositext)) by Jo Hund, Aaron J Walker, Nathanael Jones et al

a customized parser/converter for repositext (repositext.org) - components for large-scale content collaboration & publishing work flows


**manuscript** (github: [aalgahmi/manuscript](https://github.com/aalgahmi/manuscript)) by Abdulmalek Al-Gahmi 

incl. extented parsers for latex, html and epub


## Online (Live) Editors

**kramdown-service**
(heroku app: [trykramdown](http://trykramdown.herokuapp.com),
 gem: [kramdown-service](https://rubygems.org/gems/kramdown-service),
 github: [writekit/kramdown-service](https://github.com/writekit/kramdown-service))

simple online editor that lets you try the kramdown library converting markdown to HTML or LaTeX. 
The online app also includes a HTTP JSON API service (e.g. /markdown) for conversion. 
All is packed up in the kramdown-service gem for easy (re)use and as an extra bonus includes a binary, that is, 
kramup, that starts up the online editor and service on your local machine (e.g. use `$ kramup`). 
Supported conversion options/modes include:
    
 - HTML  - kramdown in GitHub-Flavored Markdown (GFM) Mode
 - HTML  - kramdown in GitHub-Flavored Markdown (GFM) Mode w/ Syntax Highlighter (rouge)
 - HTML  - kramdown in "Classic" Mode
 - LaTeX - kramdown in GitHub-Flavored Markdown (GFM) Mode
    

**online-kramdown-sinatra**
(heroku app: [kramdown](http://kramdown.herokuapp.com),
 github: [online-kramdown-sinatra](https://github.com/unindented/online-kramdown-sinatra)) by Daniel Perez Alvarez et al

quick and dirty implementation of an online kramdown editor

This fork (github: [arthurattwell/online-kramdown](https://github.com/arthurattwell/online-kramdown)) 
by Arthur Attwell runs on Windows locally.



## More Markdown Goodies

_modern hypertext markup in easy-to-read and easy-to-write ye olde plain vanilla text_

See the **Awesome Markdown List @ Mundi Mark** (github: [mundimark/awesome-markdown](https://github.com/mundimark/awesome-markdown)) ».



## Meta

**License**

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.
