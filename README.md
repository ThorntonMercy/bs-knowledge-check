# Bootstrap Knowledge Check

The knowledge check consists of creating:
1. A functional navbar that collapses into hamburger menu on small screens, with Home, About, and Contact sections.
2. Create a registration form where first/last name are side by side on the same row, and have email/ password fields, as well as a checkmark to confirm acceptance of ToS.
3. Create a hard-coded table with sample user input, utilizing a responsive table div, striped rows, and hover effects.
4. Create an image section using img-fluid with one regularly styled image and one styled with rounded-circle.
5. Create two buttons, one that remains visible regardless of screensize, and one that hides when the screen size is small.

Additionally:
1. The form is to validate all fields labeled "required"
2. The form submission button is to be styled btn-success
3. Verify that all containers and content work across a variety of browsers and screen sizes.

I structured the site going Navbar, registration form, table, images, buttons, and then the footer. 

I styled the site using mostly the success color theme. For a more muted color, I utilized "bg-success-subtle" for a soft green background color. 

There are four rows of hard coded user data, themed off of sci-fi shows, showing first/last names, emails, and passwords. The table header is styled in secondary so that it is visually different from the subtle green, but isn't harsh like the dark colors. There are hover effects as well as striped effects in place. 

I stacked the images on top of each other by default, and had them centered in the div. The standard rectangle image is first, followed by the rounded image. 

The buttons are "off-color" compared to the rest of the site theme. The always visible button is warning color, and the sometimes visible button is info color. 

I confirmed that the elements all adjust correctly and display as required and as expected to on smaller screens vs larger screens, without needing additional media queries due to using container-fluid, grid, and bootstrap classes. 

The form validation works due to a JS script placed in the footer. Fully expect deducted points for this.
