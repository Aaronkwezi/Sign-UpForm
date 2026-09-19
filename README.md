# WEZIS Sign-UpForm
This is  a Sign-Up form project for an imaginary web application called WEZIS. I developed it to test my skills in form creation and validation using HTML and CSS knowledge.  It also tests my flex box skills and brand identity skills.
During this project many issues were faced and solutions were developed ans shown in detail below
## Technologies used
- HTML5
- CSS3
- Flexbox
- HTML5 form validation
- SVG

## Problems encountered.
1. During the creation of the form I faced a challenge trying to group different sections for proper styling.
2. Faced problems with the responsiveness of the image when it came to shrinking the browser window.
3. Encountered challenges when styling  form feild without use of grid.
4. Validation states to show if a text was accepted, denied or being typed.

## Solutions to the  Problems

### Responsive Logo

Solved the image responsiveness problem by use of "min-height: 100vh;" in the ".logo-container" and use of flex: 1; feature in ".logo-container img " class style to enable the logo image cover the entire height of the page even when shrinked instead of leaving white space at the bottom.

### Form validation styling

 The style validations were worked upon by giving each input a blue color focus when active, if "user-invalid" it would show red and if "user-valid" it would show green and remove the focus of blue.
 
### Form Layout

 The flex-box styling of the personal information was done by creation form groups which were organised columns(flex-direction: column) and the content inside each form group was given a flex-direction: row.

## Future improvements for Sign Up form.
1. Use of grid and flex box together for styling.
2. Add javaScript validation alongside HTML5 validation for more advanced validation and user feedback.
3. Improve mobile responsiveness