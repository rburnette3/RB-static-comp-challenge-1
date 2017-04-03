# Static Comp Challenge 1

#### HTML Layout
The approach taken to the HTML lay out was to first determine the number of individual "boxes" that would contain the information in the comp.
1.  Intro Box
2.  Profile Box
3.  Experience Box
4.  Education Box
5.  Blog Box
6.  Social Media Box
7.  Contact Box
8.  Portfolio Box
9.  Main Picture Box (aside)

The first eight boxes were grouped into a ``<section>`` element with a class of ".container".  The main picture was set to an element of ``<aside>``.  The display for the ``<section>`` element was styled in CSS using display: flex, flex-wrap:wrap and then float: left.  The ``<aside>`` was also floated left, together creating the initial layout as seen in the comp.  An additional ``<footer>`` was created for later use when the the screen size would become smaller.

#### CSS

With the initial layout complete the styling was then applied.  The ``<aside>`` element had a background img added and using the color matching tool in Coolors the color pallette was created.  The eight individual boxes were styled using these colors in a way that they would not overlap each other in color when the screen was condensed.  The media queries were established by reducing the screen size.  First noted at 960px and again at 600px.  For the first query the aside box shrank to become incorporated into the eight box section in the top right corner next to the "intro-box".  This was done by changing the background of the "profile-box" to the img and sizing accordingly.  The footer created earlier was then set to display and in turn became the "profile-box"  The media query was set at 600px.  At this point the intro box would consume 100% of the width of the comp and the smaller boxes would fall in line below two at a time using 50% of the width.  The "profile-box" would also use 100% of the width.  I attempted to incorporate the image into the "intro-box" on the right side but felt it was too cluttered with the existing text and buttons.

Hex Colors used:
#8B6D69
#768593
#324086
#BF594B
#453231


#### Original Comp

![original comp](https://github.com/rburnette3/RB-static-comp-challenge-1/blob/master/img.file/Screen%20Shot%202017-04-03%20at%205.06.00%20AM.png)

#### Final Comp

![original comp](https://github.com/rburnette3/RB-static-comp-challenge-1/blob/master/img.file/Screen%20Shot%202017-04-03%20at%205.22.09%20AM.png)
