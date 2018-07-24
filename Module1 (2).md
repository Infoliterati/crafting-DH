# Thoughts on Module 1 

First, I'm behind. On account of being away for a few days and with marking to do. 

The readings are looking at blog posts by various digital historians about particular issues or concepts.  Very interesting.  I started to annotate them using hypothes.is but realised I wasn't saving them, so now I need to go back and have another look and express some thoughts about them.  

For now, my thoughts about open access, and making research data open, available and accessible. 
- can understand some reluctance in the context of the pressure on researchers to publish, competititve ennvironment can make one reluctant to share
- also questions about labour / exploitation 
- but we cannot progress alone, and can benefit from others using our data, building on it 
- is similar to citing / references sources of ideas, data is cited and can help researchers work become known, part of the scholarly conversation
- for students, this means being assessed different, focussed not on outcomes but the process (I really like this about the Crafting DH course)
- can see how in the digital realm how this applies (coding, cleaned data) - coming from a library background I have a philosophical position of supporting openness, that is what libraries are all about, making information freely available, and also supports openness of research data
---

### EXERCISE 1: learning markdown syntax with dillinger.io

Markdown is a syntax that marks semantic elements explicitly, separating (or liberating) the content from the tool, making it much easier to render the content / documents in different formats, such as pdfs or webpages. It is designed to be as readable as possible as is.   It can be written in any plain text editor, such as TextWrangler (Mac) or Notepad++ (Windows) but there are also specialist Markdown text editors, such as Dillinger

"Dillinger is a cloud-enabled, mobile-ready, offline-storage, AngularJS powered HTML5 Markdown editor" ( dillinger.io ). Dillinger allows you to 

  - Import a HTML file which will convert to Markdown
  - Drag and drop images (requires your Dropbox account be linked)
  - Import and save files from GitHub, Dropbox, Google Drive and One Drive
  - Drag and drop markdown and HTML files into Dillinger
  - Export documents as Markdown, HTML and PDF

So, for this exercise to learn to use markdown, I am trying out some of the markup language, and will include in this inserting an image, as well as links to websites. 

------

### Experiments (and notes)

this is *italics*
# Header 1 using hashtag
#### Header 4 using hashtag
(they get smaller the more hashtags you put in front)

Header 2 using -
----
Header 1 using =
===
(you need a line space between these headings for this method to work)

#### Lists 
1. first item on a numbered list

2. second item on the numbered list 
* This is a sublist with a dot point 

**FAIL alert!**  The sublist isn't working , and when I cut and paste from the cheatsheet, it also doesn't work. 
**SOLUTION** :  Read instructions in cheat sheet propertly, which says dot points are in lieu of line spacing

**_Note to self_** - I won't try and learn all these, but keep the cheatsheet bookmarked for handy reference.  The more I use the features, the more I will remember the commands. 

Things left to try, as listed in the cheatseat  
> block quotes (which I am doing now)
> different link types (see below)
> images (see below)
> code syntax (not just now)
> tables (not just now)
> inline html (not just now)
> horizontal rules (see above)
> line breaks (yep, got it)
> youtube videos 

inline style link [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

inline style link with title [sustainable authorship](https://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown "plain text using pandoc and markdown")

Referencing style link [Crafting Digital History, Module 1 Exercises]

Rerencing style link - numberered [1]

Relative to repository file [one of my github files](https://github.com/Infoliterati/Spoon-Knife/blob/master/README.md)

Link the [text itself]

Using angle brackets around URL <http://workbook.craftingdigitalhistory.ca/module-1/Exercises/>
(https://github.com/Infoliterati/Spoon-Knife/blob/master/README.md)

[Crafting Digital History, Module 1 Exercises]: http://workbook.craftingdigitalhistory.ca/module-1/Exercises/
[1]: http://workbook.craftingdigitalhistory.ca/module-1/Exercises/

[text itself]: http://workbook.craftingdigitalhistory.ca/module-1/Exercises/

**_Notes and question_**:
I found the referencing style links interesting - eg the fact that they were kept separate, or can follow later.  I wonder, are they always separated and what are the advantages of this? And, if they are reference links, should they be displayed at the end.  I'll have to thinkask about how they would be displayed at the end if that was required... [1]

[1]: this is my footnote with a [link](https://infoliterati.com)


#### Images

Inline-style: 
![alt text](https://cdn.pixabay.com/photo/2016/11/03/15/41/vintage-1794705_960_720.jpg "Mad Hatter's tea party")
 
**FAIL alert!**  The first time I tried this, I didn't have any luck inserting the image, until I realised I needed to right click the image to get the original URL where the image is stored as the image file.  I was really interested to see the symbol that appeared in place of the image, as it is the same one that appear, say in a graphic heavy email, where it doesn't display the image (but may ask if you want it downloaded); it also appears when there is a problem loading the image. So it was interesting for me to understand that symbol and realise a bit about what is going on there. One good thing about failing is that I am able to recognise/ diagnose and perhaps even fix when I come across other similar failings.

**_Reflection_**:  
- I love the hover function - this is achieved by putting the text in double quotation marks after the image location URL.  It is the 'instyle link with title' method (same as used in the above link-creating process). The same principles used in the link-creating process apply to images as well, eg using Reference-style, where the URL is kept separately and an alternative text inserted. The separate line is the reference /alternative text in brackets, followed by a colon and then the URL    
- It seems that  ![alt text] is what goes in place of the text placed in square brackets used when creating links
- there is also prose.io, another markdown editor that saves to Github. I've checked it out and its great!
- i think I have solved the problem of the references showing or not showing - if the square bracket/ colon is then followed by just a URL, it doesn't show up, but if there is some text in front of it, it does show - so is this used for substituting long URLs for a short text to make it less complicated ?
 
**Question for Slack**
markdown question:  I found the referencing style links interesting - eg the fact that the URLs were kept separate, or can follow later. Is the purpose to avoid cluttering up the text with long URLs?  I can see that as a "reference" they would be usefully placed at the end of the document (if visible). Through experimenting I discovered that if the square bracket with colon - [alternative text]: -  is then followed by just a URL, it doesn't show up in the output, but if there is some text in front of it, then it does show - so to make a reference visible, it needs some text, not just a URL. Is that right?  I'm also wondering if/how you can put in just text without it showing up in the preview window, or output document (as if writing a note to self).



 

 








 

 
 


 


