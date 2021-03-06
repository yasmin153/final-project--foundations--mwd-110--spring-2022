# Spring 2022 Foundations of Web Design and Development — Final Project

* **Do not edit this file.**
* **Do not start this project until you have read these instructions carefully.**

## ❖・Before You Begin・❖
1. Log in to GitHub.
2. Fork this repo(sitory). See [this video](http://code-warrior.github.io/tutorials/git/github/forking-and-cloning-at-the-github-web-site/) on how to carry out this step and step `3`.
3. Clone your fork, using either the web site or the GitHub Desktop client.
4. Checkout your personalized branch, the one with your name and GitHub user handle.

---

## ❖・Introduction・❖
For this final project, you’re building a portfolio-themed web site of your school projects, graphic design work, photographs/illustrations, audio compositions, or other creative work. If you don’t have work of your own, you have three options:

1. Use a friend’s, colleague’s, or family member’s work as the basis for your project.
2. Create a portfolio of an artist’s or designer’s work whom you admire. (They can be alive or deceased.)
3. Produce a portfolio for a fictitious person or entity using open source images.

I encourage you to consider both traditional web design elements (navigations on top, 960 pixel widths, etc) and non-traditional elements (navigation elements perhaps on the bottom, non-linear display of content, etc). Experiment!

---

## ❖・File List・❖
**Note**: Git-related files are not listed below.

1. `README.md`
2. `index.html`
3. `scss/_reset.css`
3. `scss/_variables.css`
4. `scss/style.css`
5. `img/`
6. `js/`

---

## ❖・Rules・❖
### Design-Related Rules
* Your project must be a multi-page site consisting of at least three pages: `about`, `contact`, `gallery/portfolio`.
* Use no more than three colors and a neutral.
* Use no more than two typefaces, both from [Google Fonts](https://fonts.google.com/).
* You **must** design at least three versions of your site: mobile, tablet, and desktop/laptop.
* No lorem ipsum content; that is, no filler content.

### Code-Related Rules
* You must use Sass to style this project. **Note**: CSS is ignored in this project.
* You must leverage and expand on the existing Sass files in the `scss` folder, without altering the reset document: `_reset.scss`, `_variables.scss`, and `style.scss`. Consider adding the following alias to your command line’s alias file: `sass --style=compressed --update --watch`.
* There is **no** need to invoke multiple `“preconnect”` link types for your Google Fonts. The only one you’ll need is already in the included `index.html` file.

### Scaffold-Related Rules
* Only submit files that are required by your project: Do not submit working files, such as `.psd`, `.ai`, `.indd`, or `.sketch` files.
* Use lowercase, combined with kebab case, to name folders and files (`do-this` or `do-this.html`); no spaces in folder or file names (`not this`); no camel case (`notThis`); no snake case (`not_this`).
* All HTML files must go in the root of this folder, with the `index.html` file acting as the springboard for your site. If you design a site with multiple folders, make sure to update the `.gitignore` file in the root of this project so it’s not ignored in your submission.
* All Sass must go in the `scss` folder and generate CSS into a sibling folder called `css`.
* If you use images, they must go in the `img` folder.
* Any images you include **must** be smaller than or equal to 1MB.
* If you use audio, their files must use the `mp3` extension.
* If you use Video, their files must use the `mp4` extension.
* If you use jQuery and/or JavaScript, their files must go in the `js` folder. If you’re not using either language, then you may delete the `js` folder.
* Ensure there are no absolute paths anywhere in your project.

---

## ❖・Questions to Consider・❖
* What is the trend in pages that display similar content? How far can my design stray from that trend without affecting user experience (UX) negatively?
* Is the contrast between type and (back) ground balanced sufficiently to make reading easy? If not, can I justify why?
* Which typeface will help me to get my meaning across? Does each typeface complement each other, and do they work harmoniously with the overall design?
* Is the space I use around content helping the user consume my design, or is it making her/him work hard at understanding my intentions?
* Which sections of the content are most important?
* What should be emphasized?
* Does the color scheme complement the message I’m trying to convey, or is it simply serving an aesthetic role in my design?
* Is my design communicating what I need it to?
* Is my site easy to navigate?

---

## ❖・Grading・❖
| Item                                             | Points |
|--------------------------------------------------|:------:|
| *HTML is W3C-compliant*                          | `20`   |
| *Sass is generates valid W3c-Compliant CSS*      | `20`   |
| *Code is clean, neat, and organized*             | `20`   |
| *Design shows attempt at producing quality work* | `20`   |
| *Rules for this assignment followed correctly*   | `20`   |

---

## ❖・Due・❖
12:00 PM on Thursday, 5 May 2022.

---

## ❖・Presentations・❖
You will present this final project to the class for a group critique via Zoom at our [assigned final exam time](https://www.hartford.edu/academics/academic-calendar/final-exam-schedule.aspx): **2:00 PM on Thur, 5 May.** Videoconferencing details will be provided in a separate communication.

---

## ❖・Submission・❖
You will need to issue a pull request back into the original repo, the one from which your fork was created. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may *only* be submitted via GitHub. **No other form of submission will be accepted**.
