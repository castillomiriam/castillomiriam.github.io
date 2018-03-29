---
layout: post
title:      "Brief Bootstrap Bio "
date:       2018-03-29 01:31:44 -0400
permalink:  brief_bootstrap_bio
---

![Bootstrap](http://www.unixstickers.com/image/cache/data/stickers/bootstrap/bootstrap.sh-340x340.png)

*Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first project on the web.*

Hi! I'm going to walk you through a few key points about Bootstrap and why it's great. You know all the stuff you learned in the CSS section of the curriculum about building responsive layouts, graceful degradation, progressive enhancement, media queries, etc? Making web pages responsive to the size of the screen they were on? 

```
@media[not|only] type [and] (expr) [,] … {
rules
}
```

*^ this thing. you remember.*

Bootstrap makes it all a lot easier for you. Here's how in a few key points. 

As stated above, bootstrap is an HTML, CSS and JS framework for developing responsive, mobile first projects on the web.

**Why you should use it:**

**+**
* Responsive, features, flexible styling.
* Popular
* Open Source (github)
* Build Quickly, save time 

**–**
* Lack of individuality, non-content driven media      queries (break points are made for you)
* Heavier than necessary (more code than needed)

[Get Bootstrap](http://www.getbootstrap.com)
[Github Link](http://www.github.com/twbs/bootstrap)

**Download Types (There's Three):**
* Compiled and minified css, javascript, and fonts
* Sourceless, javascript, and font files, along with our docs
* Bootstrap ported from less to sass for easy inclusion in rails, compass, or sass-only projects.

**CDN Usage (Links From CDNS):**
[CDN Link 1](http://www.bootstrapcdn.com)
[CDN Link 2](http://www.cdnjs.com/libraries/twitter-bootstrap)

**Folder Structure:**
* There are three folders: css, js, fonts + all the files inside this folder.

**Setting Up A New Project:**
* After downloading, change the Bootstrap folder to your own folder name for the project. Then create an index.html page inside the project folder and you're set.

```
my-site-project/
-css/
-js/
-fonts/
-index.html
```

*^ Folder will look like this *

**Basic Html File Usage (basic html-5 template):**
[Get code here](http://getboostrap.com/getting-started/#template)


**Bootstrap Grid system**
*Bootstrap's grid system uses a series of containers, rows, and columns to layout and align content. *

**Containers**
* Container classes are used to wrap your content to center it. you have a choice of fixed width or fluid (stretches across the whole screen.) 

**Rows**
* Creates vertical separation. Use row class to wrap columns.

**Columns**
* Use col classes to separate content horizontally. The default grid allows for 12 columns.

* Class name “col-” is followed by either xs, sm, md or lg. These indicate the sizes which affect the *css media query break points* (This defines how may pixels the columns start to stack vertically instead of horizontally).


**Collapsed To Start-Horizontal Above Breakpoints (Except for XS)**
* LG-*1200px*
* MD-*992px*
* SM-*768px*
* XS-*<768px*

**Column Offset**
You can use “-offset” class to shift columns over to the right. Therefore, col-sm-offset-4 will offset the column 4 spaces. 

**Column Ordering**
You can change to the conventional order of the columns by using push and pull classes. Push will push columns to the right and pull will pull columns to the left. You can use a number to indicate how many column spaces to push or pull.

**Nesting columns**
Columns can be nested inside one another by inserting a row inside a column and then inserting additional columns inside of the inner row.


[Bootstrap In More Depth](http://http://instruction.learn.co/student/video_lectures#/221)
[Get Bootstrap](https://getbootstrap.com/)







