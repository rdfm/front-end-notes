# NOTES: Onsite Interview

## PREPARATION

- On Mac: 
  - Safari, go to: apple.com
  - Chrome, go to: apple.com
  - Firefox, go to: apple.com
- On iPhone: 
  - Download Apple Store App
  - Safari app, go to: apple.com
  - Chrome app, go to: apple.com
  - Firefox app, go to: apple.com

---

## TASKS

### Technical Test (30 minutes)

- Build a page using HTML and CSS from a PSD.
- Can use any resource you want (online, notes, etc.)
- Use their MBP 15, sublime editor.

NOTE: The picture looked like a promotional ad pop up. The button was styles blue with rounded corners and white text as well as the horizontal ribbon up to right (SEE ATTACHED DRAWING)

(TO DO:
	- find PSD example of pop up (Dribble, Apple Design Resources)
	- build from PSD
  - extract CSS from layers
)

---

### Recreate (vertically and horizontally centered element inside)

- Refer to: [W3C - CENTERING THINGS](https://www.w3.org/Style/Examples/007/center.en.html)

- Refer to: [CSS Layout - Horizontal & Vertical Align](https://www.w3schools.com/css/css_align.asp)

- Refer to: [CSS-Tricks: Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/)


---

## QUESTIONS

### General Questions

- What happens when I type in www.apple.com in to the browser, behind the scenes to all the way to what I see?
(TO DO: Go to apple.com, view developer tools, and observe, note, and test)

GO TO: www.apple.com

Refer to: [Rendering a web page – step by step](https://friendlybit.com/css/rendering-a-web-page-step-by-step/)

---

- What happens when you have an html file that says Hello?
(TO DO: define / answer)

Question to ask: How does browser load an HTML Page?
Example: HTML file which just includes the text "Hello"

- Browser / DOM builds DOM tree
- Fixes anything missing (wraps in <html> tags, includes the <head> tag, places text inside <body> tag)
- displays text with default styling from browser

---

- What is the DOM and what happens in it?
(TO DO: define / answer)

1_Document_Object_Model_DOM.md
2_Intro_DOM.md
3_W3C_DOM_Level_1_Core.md
4_traversing_HTML_table.md
5_locating_DOM_elements.md
6_create_DOM_tree.md
7_events_and_DOM.md
8_whitespace_in_DOM.md
9_examples_DOM.md
file_structure.txt


[CSS-Tricks: What is the DOM](https://css-tricks.com/dom/)

[MDN: Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)


---

- Any difficulties you’ve had when developing a website and how you address those problems?
(TO DO: Find an example, refine talking points, and prepare a solution)

Research:
	- Commom web development mistakes
	- 

> Syntax / Type Errors
	- Linters
	- Inspecting

> Cross-Browser Compatibility
	- check "Can I use"
	- Cross Browser testing (
	- add vendor prefixes if needed

---

### HTML + CSS

- What new features were introduced in HTML5? 
(TO DO: define / answer)

Refer to: [What's New in HTML 5](https://www.lifewire.com/whats-new-in-html5-3467974)
Refer to: [MDN: HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

---

- What new features were introduced in CSS3? 
(TO DO: define / answer)

Refer to: [What’s new in CSS 3](https://medium.com/beginners-guide-to-mobile-web-development/whats-new-in-css-3-dcd7fa6122e1)

Refer to: [MDN: CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)

---

- What is the box model?
(TO DO:
	- define / answer
	- recreate example
	- create visual version, add to rdfm Knowledge Base
)

Refer to: [MDN: The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model)

---

- What different positions properties are there and what do they do? 
(TO DO: define / answer)

Refer to: [MDN: position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

static;
relative;
absolute;
sticky;

---

- What different display properties are there? (TO DO: define / answer)
(TO DO: define / answer)

---

- What are selectors are there in CSS?
(TO DO: define / answer)

Refer to: [MDN: CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors#Simple_selectors)

---

- What are Psuedo Classes?
(TO DO: define / answer)

https://github.com/rdfm/MDN-notes/blob/master/Common_questions/2-CSS_questions/1-Basic/06-Pseudo-classes.md

:

- ONLY in certain state (style element)

---

- What are Psuedo Elements?
(TO DO: define / answer)

https://github.com/rdfm/MDN-notes/blob/master/Common_questions/2-CSS_questions/1-Basic/07-Pseudo-elements.md

::

- certain part of an element (add style)

---

- What do these do in css?
	div p
	div + p
	div ~p
	.test1 .test2
	.test1.test2

(TO DO:
	- define / answer
	- create CSS Selectors Page to rdfm Knowledge Base)
)

https://github.com/rdfm/MDN-notes/blob/master/Common_questions/2-CSS_questions/1-Basic/08-Combinators_and_multiple-selectors.md

div p
	- Descendant combinator
	- Any element matching B that is a descendant of an element matching A 

div + p
	- Adjacent sibling combinator
	- Any element matching B that is the next sibling of an element matching A (that is, the next child of the same parent).

div ~ p
	- General sibling combinator
	- Any element matching B that is one of the next siblings of an element matching A (that is, one of the next children of the same parent).
	
.test1 .test2
	- Descendant combinator
	- Any element matching B that is a descendant of an element matching A 
	
.test1.test2
	- includes both classes

[MDN: Class Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)

---

### JavaScript

- What new features were introduced in ES6 JavaScript?
(TO DO: define / answer)



---

## ADDITIONAL (TO DO)

- HTML Fundamentals
	- HTML Quiz (https://www.w3schools.com/HTML/html_quiz.asp)

- CSS Fundamentals
	- CSS Quiz (https://www.w3schools.com/css/css_quiz.asp)

- Sass
  - study Sass basics
  - install Sass
  - install Sass (w/ Gulp)
  - common Sass mixins / snippets
- Git/GitHub/GitLab
  - Research GitLab

Refer to: [GitLab site](https://about.gitlab.com/)

> GitLab is a single application for the entire software development lifecycle. From project planning and source code management to CI/CD, monitoring, and security.

  - LinkedIn Learning: GitLab
- Apple Store App (iOS)
  - Research source code
  - Research  

## Browser: Safari

Turn on Safari Developer Tools
Safari > Preferences > Advanced > Check: "Show Develop menu in menu bar"


## Text Editor: Sublime Text

### Package Control

- TYPE: Shift + Command + P 
- Search: Install Package Control 
- Search: Package Control: Install Package
  - OR Package Control: Remove Package

### Install Packages

- Emmet
- SideBarEnhancements
- BracketHighlighter
- HTML5
- Sass
- Color Highlighter
  - Color picker (Ctrl + Shift + C)
- AutoFileName
- View In Browser
- MarkdownEditing
- MarkdownPreview
  - Search: "Markdown Preview: Preview in Browser
- MarkdownLivePreview
  - Type: alt + m

**TO TRY**:
- Pretty JSON
- SublimeLinter
- DocClokr (https://packagecontrol.io/packages/DocBlockr)
- All Autocomplete
- A File Icon
- Pretty JSON
- Emmett Css Snippets (https://peiwen.lu/Emmet-Css-Snippets-for-Sublime-Text-2/)
- Terminal
- SublimeREPL
- ColorPicker
- Babel

### Command Line: subl 

**NOTE (Using zsh)**

- In Terminal: $ nano  ~/.zshrc
- ADD (to the bottom of file):
  - $ echo 'export PATH=$PATH:$HOME/bin' >> ~/.zshrc
  - $ echo "export EDITOR='subl'" >> ~/.zshrc
- Restart terminal window
- In terminal: $ subl .

---
