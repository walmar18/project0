# Project 0

Web Programming with Python and JavaScript

The website contain five different .html pages, all accessible from the left vertical Nav.
All pages use stylesheet Bootstrap 4 and the project0.css stylesheet file.
Elements repeated in each page are:
	- The Nav bar, containing an unordered list with the links to all the other pages and a image of Antonio Vivaldi. This image has an Id wich is used in an #id selector at project 0.css.
	- The footer using class provided by bootstrap

Index.html
	- Contains an unordered list, in which each item is an ordered list
	- Use Bootstrap's Card component, which contains the YouTube video.

Pages 1 to 4 contain the text of the corresponding sonnets in two languages, italian and spanish, each one displayed in a different columns.
Page1.html
	- Contains a table with two columns, each corresponding to a language
Page2.html, Page3.html and Page4.html
	- Each contains two columns using the Bootstrap grid model.
 
project0.css is created with SASS from the project0.scss file
	- Uses different CSS properties, and different types of CSS selectors according to the requirements
	- Includes mobile-responsive @media querys to:  
		· Show on smaller screens the link that jumps to the top of the page. 
		· Decreases font size of Nav list  items on smaller screens.
	- Uses many SCSS variables for the colors.
	- Uses SCSS inheritance for the cells of the table in Page1.html. Also for the cells in the Page2.html, Page3.html and Page4.html that simulates a table using the Bootstrap grid model.
	- Uses SCSS nesting for the ul and ol contained in the index.html.
