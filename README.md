# Responsive-Dashboard

Building an Admin Dashboard Layout With CSS and a Touch of JavaScript

.create a responsive admin dashboard
.from borrowed ideas in wordpress dashboard such as collapsible sidebar menu


1.Begin With the Page Markup
we need svg, a header and a section

SVG Sprites
-from evento elements/download those trade and dashboard icons.

..............The container should be hidden, so we’ll apply (display: none) to it. If we don’t hide it, a big empty area will appear at the top of the page.
2.Header
 we’ll define a nav element which will serve as the wrapper for the following elements:
-The logo
-The Collapse button that will toggle the menu on mobile screens
-he menu itself

3.Section
The section will contain two nested sections.

Section #1
we’ll place the search form and some info (name, avatar, and notifications) about the current logged in user.
Section #2
just for enriching the demo with some dummy content, we’ll place a bunch of article placeholders. 
Use a maximum of 5–7 different widgets to create a view.




CSS Formats.
Define Some Basic Styles
-Style the Header
 Its width will be 220px and its height equal to the viewport height.
 -Menu Styles
The menu will serve as a flex container, and we’ll give it flex: 1, so it’ll expand and cover the full parent height.
-Page Content Styles
Remember that the .page-content section contains two sub-sections.
will be placed 220px away from the left side of the viewport. Plus, we’ll give it width: calc(100% - 220px). Note that its left property value is equal to the header width.
-will be placed 220px away from the left side of the viewport. Plus, we’ll give it width: calc(100% - 220px). Note that its left property value is equal to the header width.
-Grid Styles

Toggle Header
-Each time we click on the collapse/expand button, the header state will change. If it’s expanded, it will collapse (leaving just icon variants of the menu items), and vice versa.

Show Tooltip on Admin Menu Items 

Going Responsive
-On screens up to 767px wide, our page will look like this:

Toggle Mobile Menu
Each time we click on the toggle button, the menu state will change. If it’s expanded, it will collapse, and vice versa.
