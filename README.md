# Notes4
Reading notes 4

Wireframing
Wireframing is a practice used by UX designers that allows them to define and plan the
info hierarchy of their design for a website, app, or product
You need a plain b&w diagram showing where your info goes before building with code
The path must be clear before adding colors etc
can be drawn by hand or using software

With the help of paper-prototypes, you can test with end users at every stage of ideation and design. Changes at these stages
are much easier—and therefore cheaper—than changes deemed necessary after coding is under way.****

experiment with different programs to wireframe
6 steps
1.Do your research
2.prepare research for quick reference
3. make sure you have your user flow mapped out
4. Draft, don't draw.  Sketch, don't illustrate
    -collaborate, like on a white board
5. Add some detail and get testing
  -Use usability conventions such as putting navigation (search) at top, simple wording, tooltips indicating functionality that could be included in a 
  prototype transition
  -You can use tools like UsabilityHub to preference test screens and collect qualitative feedback, and Prott to test and check understanding of the basic user flow
  With this tool, you can simply photograph and upload your hand-sketched wireframes, and then connect them to user button overlays.
6. Start turning wireframes into prototypes
  -After feedback from first prototype you can start developing high-fidelity prototypes
   Most well-know tool for this is Figma
  Once you’ve developed your wireframes in Sketch, you can import them into the industry-leading prototyping tool InVision (which, incidentally, we built a
  course in conjunction with) and interlink your screens for a second round of high-fidelity user testing***


HTML
opening tag =<p>
content
angle brackets= <>
clsoing tag <p>
all together is called element

"Attributes" contain extra information about the element that you don't want to appear in the content
Ex: class="editor-note"
class= attribute name
note= attribute value

attribute should always have:
1. a space between it and the element name (or previous attribute if the element already has one or more attributes)
2. Attribute name followed by equal siagn (=)
3. Attribute value wrapped by opening and closing " marks

putting elements inside other elements is called nesting
Some elements have no content and are called empty elements. Take the <img> element that we already have in our HTML page:

<img src="images/firefox-icon.png" alt="My test image">
Copy to Clipboard
This contains two attributes, but there is no closing </img> tag and no inner content. This is because an image element doesn't
wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.

<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were 
meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking 
<html></html> element wraps around entire page
<head></head> element is container for stuff you want on page that isn't viewer content like keywords or page desripts for search results
              or css for style
<meta charset="utf-8"> element sets the character set
<title></title> sets title in browser tab or bookmark
<body></body> element contains all content you want to show

Images
Let's turn our attention to the <img> element again:
<img src="images/firefox-icon.png" alt="My test image">
As we said before, it embeds an image into our page in the position it appears. It does this via the src (source) attribute, 
which contains the path to our image file.
alt attribute provides descriptive text for scrreen readers or if image does not display
< h1>-<h6>  (heading elements)
< p><p/>  elements for paragraphs
< ul>=unordered list
< ol>=ordered list
each item put inside 
< a>=anchor
add href="urlname"
examp: < a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>

Semantics refers to the meaning of a piece of code
Some of the benefits from writing semantic markup are as follows:

Search engines will consider its contents as important keywords to influence the page's search rankings
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without 
semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming
Roughly 100 semantic elements

HTML=HyperText Markup Language
"Hypertext" refers to links that connect web pages to one another


[Go to TOC](https://catdude2000.github.io/reading-notes/)