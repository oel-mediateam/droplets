# DROPLETS
**_version 1.5.3_**  

A HTML, CSS, and JavaScript framework for instructional designers at University of Wisconsin-Extension division of Continuing Education, Outreach &amp; E-Learning (UW-EX CEOEL).

### How To Use
1. To start, download the [framework](https://github.com/uwex-learning-tech/droplets/archive/master.zip) (ZIP).
2. Unzip or extract the ZIP file when the download is completed.
3. Open the `dist` directory.
4. Upload all of the files and directories inside the `dist` directory to your LMS's file storage.
5. Include the `style.css` stylesheet from the `css` directory to the HTML head element. For example, `<link href="path_to_your_lms_file_directory/style.css" rel="stylesheet" />`.
6. If interested in using the JavaScript components, include the `style.js` javascript file from the `script` directory to the HTML head element. For example:
```
<script src="path_to_your_lms_file_directory/style.js" type="text/javascript"></script>
```
**Note:** This framework is specifically developed for designers use at UW-EX CEOEL. Some setups or usages may not be optimal or preferable for your organization. In addition, this framework is somewhat built to accommodate the LMS (Desire2Learn) that is being used at UW-EX CEOEL. However, you are most welcome to download or fork this repository and modified it to your organization's needs.

### Development Requirements
* HTML5
* Cascading Style Sheets (CSS3)
* SASS (http://sass-lang.com/)
* Compass (http://compass-style.org/)
* jQuery 3.x

Knowledges of SASS and Compass are essential to write the CSS for this framework. The CSS file is created/compiled and minified by SASS, a CSS preprocessor.

**Note:** [CodeKit](https://incident57.com/codekit/) is highly recommended for Mac users during the development process.

### Minimum Supported Web Browsers
* Internet Explorer 9+
* Mozilla Firefox 30+
* Google Chrome 33+
* Apple Safari 5+
* Opera 20+

*Latest stable version is always recommended.*

### Bug Reporting and Questions
If any bugs/glitches are found in this framework, please report them under the "**[Issues](https://github.com/uwex-learning-tech/droplets/issues)**" page on GitHub. When reporting a bug, please write the report as detailed and specifically as possible. Note the steps to reproduce the bug and include screen captures if possible.

For questions, please also post them under the "**[Issues](https://github.com/uwex-learning-tech/droplets/issues)**" page on GitHub.

---
#### Version Change Log

**1.5.3**
* Fixed an issue where img in figure tag is not respecting to img's width and height attributes.

**1.5.2**
* Lightbox enhancements: grid layout & support both <code>img</code> and <code>figure</code> (with <code>figcaption</code> as well)

**1.5.1**
* Two new icons: Email and Extra Credit
* Icons are now alphabetically ordered
* Fixed child iFrame element height when not nested inside a parent iFrame

**1.5.0**
* New Icon: Lab
* New Feature: Reveal
* New Feature: Lightbox (for image only)
* Updated Read More style
* Updated jQuery to version 3.2.1 slim build
* Minor fixes

**1.4.7**
* Added a new briefcase icon
* Fixed popover position issue

**1.4.6**
* Rework CSS for figure element.
* Figure element can now be floated.

**1.4.5**
* Updated a few font icons to improve legibility
* Adjusted a few font icons vertical alignments

**1.4.4**
* Fixed the issue where first icon size in a callout was larger than others.
* Icon font encoding in CSS is back.

**1.4.3**
* Added four new icons to the [icon set](https://media.uwex.edu/app/droplets/icons.html).

**1.4.2**
* Added three new icons to the [icon set](https://media.uwex.edu/app/droplets/icons.html): tech need, welcome, and competency.
* Enhanced the tab style for more visibility.
* Tab can now be colored. See doc for more info.

**1.4.1**
* Updated [Learning Resources Component](https://media.uwex.edu/app/droplets/learning_resources.html) to reflect feedback from Instructional Designers.

**1.4.0**
* New JavaScript component: [Learning Resources](https://media.uwex.edu/app/droplets/learning_resources.html)

**1.3.6**
* Improvements and minor fixes
* Added more contextual styles for tables: border with thickness and styles, cell text indentations, and neutral gray background color
* Added WAI-ARIA (accessibility) markups to elements
* Converted "Helpers" page to "Helpers & Accessibility", which now contains information on WAI-ARIA

**1.3.5**
* Fixed the issue where calendar tab was not working
* Added a short message about view agenda details in Display All view

**1.3.4**
* Removed unwanted css rules
* Resolved a tag name conflict with columns in tab

**1.3.3**
* Fixed an issue where popover is not aligned correctly

**1.3.2**
* Added left margin to right-floated block-level callout
* Table head are now properly aligned base on the specified class
* iFrame height is now properly set when expanding agenda detail on calendar

**1.3.1**
* Fixed page header line height
* Added more spacing after the page header
* Fixed accordion's auto-height calculation in an iFrame
* Fixed calendar not displaying/highlighting current day of the month
* Nested unordered list bullet is now a circle rather than a disc

**1.3.0**
* Added two new classes for table: `minimal-padding` and `small-text`
* `vert-top`, `vert-center`, `vert-bottom`, `horz-left`, `horz-center`, and `horz-right` classes can now be applied to the whole table rather than individual cells or `td` elements.
* Read More feature has a new look
* [Calendar](https://media.uwex.edu/app/droplets/calendar.html)
* Minor bug fixes

---
&copy; 2013 - 2018. Ethan Lin, University of Wisconsin-Extension Division of Continuing Education, Outreach & E-Learning, and Board of Regents. All rights reserved.
