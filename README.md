# Data Institute 2018
For students of https://projects.propublica.org/graphics/ida-propublica-data-institute

Here are all of the materials we used to teach the 2018 Data Institute: slides, exercises, links, and homework. This is not an online course and doesn’t have all the context or instruction to be a standalone class.

Want to use our slides? Our teaching materials fall under the [same Creative Commons license](https://creativecommons.org/licenses/by-nc-nd/3.0/us/) we use across our site. [Get more details here.](https://www.propublica.org/steal-our-stories/)

# Curriculum

## Table of Contents
Click to jump directly to:
- [Install Party](#welcome-reception--install-party)

Week 1:
- [Day 1: Intro to Data Journalism, Spreadsheets, Best Practices](#day-1)
- [Day 2](#day-2)
- [Day 3](#day-3)
- [Day 4](#day-4)
- [Day 5](#day-5)

Week 2:
- [Day 6](#day-6)
- [Day 7](#day-7)
- [Day 8](#day-8)
- [Day 9](#day-9)
- [Day 10](#day-10)

## Welcome Reception & Install Party

**ACCOUNTS**
<ul>
  <li><a href="https://github.com/join?source=header-home">Github.com</a><br>(Make sure to confirm your e-mail address)</li>
  <li><a href="https://accounts.google.com/SignUp?service=wise&amp;continue=https%3A%2F%2Fdrive.google.com%2F%23&amp;ltmpl=drive">Google.com</a></li>
</ul>

**SOFTWARE**
- <a href="https://www.google.com/chrome/browser/desktop/">Google Chrome</a>
- Slack (<a href="https://itunes.apple.com/app/slack/id803453959?ls=1&amp;mt=12">Mac</a>, <a href="https://slack.com/ssb/download-win">Windows</a>)
- Sublime Text (<a href="https://download.sublimetext.com/Sublime%20Text%20Build%203114.dmg">Mac</a>, <a href="https://download.sublimetext.com/Sublime%20Text%20Build%203114%20x64%20Setup.exe">Windows</a>)
- <a href="https://desktop.github.com/">Github Desktop App</a>
- Tabula (<a href="https://github.com/tabulapdf/tabula/releases/download/v1.0.1/tabula-mac-1.0.1.zip">Mac</a>, <a href="https://github.com/tabulapdf/tabula/releases/download/v1.0.1/tabula-win-1.0.1.zip">Windows</a>)
- Open Refine (<a href="https://github.com/OpenRefine/OpenRefine/releases/download/2.5/google-refine-2.5-r2407.dmg">Mac</a>, <a href="https://github.com/OpenRefine/OpenRefine/releases/download/2.5/google-refine-2.5-r2407.zip">Windows</a>)
	- If you're on a Mac, and you get the error that Google/Open Refine is damaged, [follow these instructions](open-refine-troubleshooting.md).

**Macs**
- Open your <a href="https://en.wikipedia.org/wiki/Terminal_(OS_X)">Terminal app</a> (comes with all Macs) and paste these exact commands into the window, one at a time, and press enter:
- `xcode-select --install`
- `python -V`
  - Your Terminal should say something like "Python 2.7.13". Your last two digits might be different, that's okay. If you get something that Python 3, which looks like: "Python 3.X.XX" let Sisi know.
- `sudo easy_install pip`
  - This will ask you to put in your computer password. Go ahead, and quick warning: the cursor won't move, but trust that your computer is reading what you're typing in.
- `pip install --user BeautifulSoup`
- `pip install --user Requests`

**Windows**
- Download [Cygwin](https://cygwin.com/install.html)
- When you get to this step, ask for Sisi

<hr/>

## Day 1
### Monday, Oct 1

### Intro to Data Journalism
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-data.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-data.jpg"></a>

### Intro to Spreadsheets
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-spreadsheets.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-spreadsheets.jpg"></a>

**Exercises**
- Organizing information in rows & columns using [Senate data](https://www.senate.gov/general/committee_assignments/assignments.htm)
- Learning how to sort with [Trump expenditures](https://docs.google.com/spreadsheets/d/1od86DSRi5kJPJfLpDRcSbPj2nJiRk4yJUIrfunjlK4Q/edit#gid=0)

### Finding & Loading Data
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/finding-loading.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/finding-loading.jpg"></a>

**In-Class Demos**
- Using Socrata to look at [3-1-1 calls from NYC](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)
- [Tabula](https://tabula.technology/)
- Types of data (numeric, text, date)
- Quirks of Excel (reformatting dates, dropping leading zeros)
- Text files and types (csv, tab, fixed width, pipe)
- Text delimiter (probably quotes, but maybe not)
- Open your text file in a reader and examine it

### Best Practices
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/best-practices.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/best-practices.jpg"></a>

**In-Class Demos**
- Create a text document
- Save a clean copy of your data
- Keep track of your work
- Describe your steps
- Copy/paste functions
- Screen grabs of dialogue boxes

### Advanced Spreadsheets: String Functions
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/string-functions.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/string-functions.jpg"></a>

**Exercises**
- [Practice Data](https://drive.google.com/file/d/0Bw5Mt7QIQlsgc2tLdFlpQ2QwTXM/view)
- Reformat
- Split
- Transpose

### Homework
- None! Enjoy the city!

## Day 2
### Tuesday, Oct 2

### Evaluating Data
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/evaluating-data.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/evaluating-data.jpg"></a>

### Data Integrity
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/data-integrity.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/data-integrity.jpg"></a>

### OpenRefine
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/open-refine.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/open-refine.jpg"></a>

### Analyzing Data: One Variable
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/one-var.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/one-var.jpg"></a>

## Day 3
### Wednesday, Oct 3


## Day 4
### Thursday, Oct 4

### Intro to Code
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/intro-to-code.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-code.jpg"></a>

**In-Class Demos**
- What coding languages have you heard of?
- Using the web inspector

### How Websites Work
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/how-websites-work.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/how-websites-work.jpg"></a>

**In-Class Demos**
- How the Internet passes websites around
- What HTML, CSS and Javascript contribute to a webpage

**Exercises**
- Drawing a Website

### HTML
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/html.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/html.jpg"></a>

**In-Class Demos**
- How to create your first HTML file
- Shortcut to the basic HTML template
- How to use:
  - `<h1>`
  - `<h2>`
  - `<h3>`
  - `<p>`
  - `<img>`
  - `<a>`
  - `<ul>`
  - `<!-- Comments -->`

**Exercises**
<ul>
  <li>Copy and paste <a href="https://codepen.io/sisiwei/pen/KzLezJ?editors=1000">this code</a> and follow the instructions inside to format the page.</li>
  <li>Can you fix this <a href="https://codepen.io/sisiwei/pen/PNvaeB?editors=1000">broken code</a>? </li>
</ul>

### Basic CSS
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/css.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/css.jpg"></a>

**In-Class Demos**
<ul>
  <li>How to create your first CSS file</li>
  <li>Shortcut to linking to your CSS file</li>
  <li>How CSS styles work</li>
</ul>

**Exercises**
<ul>
  <li>Using your practice HTML file from before, add CSS styles to it such you change the:
    <ul>
      <li>color</li>
      <li>font-family</li>
      <li>font-size</li>
    </ul>
  </li>
  <li>On your own, look up how to do the following in CSS, and add it to your HTML file as well:
    <ul>
      <li>underline text</li>
      <li>bold text</li>
      <li>italicize text</li>
    </ul>
  </li>
  <li>Going back to the Supreme Court article you formatted earlier, do the following using CSS:
    <ul>
      <li>Make the main headline dark red.</li>
      <li>Use the font family "Georgia" for the main headline and the subheadline.</li>
      <li>Center the text of the main headline and the subheadline.</li>
      <li>Give the paragraphs a line height of 19 pixels.</li>
      <li>Remove the underline from the links.</li>
      <li>Make the "Related articles" label all uppercase.</li>
      <li>Bonus: Make an underline appear when you hover over a link.</li>
    </ul>
  </li>
</ul>

### CSS Classes

**In-Class Demos**
<ul>
  <li>How to write your own CSS Class</li>
  <li>How CSS deals with conflict</li>
</ul>

### Homework

<ul>
  <li>Save <a href="https://codepen.io/sisiwei/pen/bpXwMB?editors=1000">this HTML</a> onto your computer. Link to a new CSS file that you create. Write CSS to make the end result look like <a href="/graphics/images/data-institute/presentations/mars.jpg">this image</a>. You may only write CSS. You cannot edit the HTML file.</li>
  <li>Using HTML, CSS, and the information you gathered over the weekend, lay out a one-page web portfolio for yourself. Don't worry too much about the final design, just make sure to get all of your information on the page and formatted using HTML.</li>
</ul>

## Day 5
### Friday, Oct 5

### Intro to Design
<p>
<a href="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/designforj/designforj.html" target="_blank">
  <img src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/design_intro.jpg">
</a>
</p>


**Lecture**
<ul>
  <li>What's Design Anyways?</li>
  <li>Design Principles: The Only 4 Rules You Gotta Know</li>
  <li>Details: The Real Secret of Good Design</li>
</ul>

**Exercises**
<ul>
  <li>Align This!</li>
  <li>Resume Redesign</li>
</ul>


### Type, Layout & Color
<p>
<a href="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/lectures/TypeLayoutColor.pdf" target="_blank"><img src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/type.jpg"></a>
</p>

**Lecture**
<ul>
  <li>Letter: The Many Faces of Type</li>
  <li>Text: How to Deal with Words</li>
  <li>The Grid: Putting the Pieces Together</li>
  <li>Colors &amp; How to Pick 'Em </li>
</ul>



**Exercises**
<ul>
  <li>Name that Font!</li>
  <li>Type Crimes</li>
</ul>


### Let's make a webpage!

<p>
<a target="_blank" href="http://lenagroeger.com/makeawebsite/"><img src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/online_portfolio.jpg"></a>
</p>

**In-Class Demos**       
<ul>
  <li>Making a website</li>
  <li>Getting your portfolio on the internet!</li>
</ul>



### Homework
<ul>
  <li>Using the principles we discussed today, redesign your résumé. Email the before and after version to <a href="mailto:data.institute@propublica.org">data.institute@propublica.org</a>.</li>
  <li>Using everything you've learned about HTML & CSS, start laying out your portfolio HTML page. Then, since you've learned how to make a working webpage on the internet, upload your page to Github.</li>
</ul>



<br></br>
<h2>📚 Weekend! 🎉</h2>



## Day 6
### Monday, Oct 8


## Day 7
### Tuesday, Oct 9


## Day 8
### Wednesday, Oct 10


## Day 9
### Thursday, Oct 11


## Day 10
### Friday, Oct 12
