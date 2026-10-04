Assignment #3. Responsive Web Design (Media Queries + Bootstrap Grid)

Student Name: Aibar Bikanov
Group: IT-2503

The main goal of this assignment is to master responsive web design techniques using custom CSS media queries, CSS Flexbox/Grid, and the Bootstrap framework. It consists out of 5 tasks (task0-task4), with the task 4 being a portoflio page.

Task 0 - Responsive Typography:

Implemented fluid heading and paragraph text sizes using pure CSS @media (min-width: ...) queries to ensure readability on mobile (20px/14px), tablet (32px/18px), and desktop (48px/22px)viewports.   

<img width="1917" height="987" alt="image" src="https://github.com/user-attachments/assets/6dec5af0-3c7c-4dd4-a9ef-7be641d86244" />


Task 1 - Resizable Columns (Flexbox & Grid):

Created a multi-column flex container with dynamic basis values calculated via calc(). The layout transitions automatically from 1 column on mobile (100%) to 2 columns on tablet (50%) and 3 columns on desktop (33.3%).   

<img width="1906" height="992" alt="image" src="https://github.com/user-attachments/assets/83c57b58-999c-46af-b20f-91a649f5ec1e" />
<img width="1132" height="392" alt="image" src="https://github.com/user-attachments/assets/36956d8a-3451-477e-a2d9-985ba288953b" />
<img width="917" height="510" alt="image" src="https://github.com/user-attachments/assets/3557575f-af31-4ebc-af8d-fc9cb029d251" />


Task 2 - Bootstrap Responsive Columns:

Replaced custom layout code with Bootstraps 12-column grid system (row g-3) using predefined classes (col-12 col-md-6 col-lg-4) to achieve identical layout breakpoints with reduced codebase complexity.

<img width="1902" height="982" alt="image" src="https://github.com/user-attachments/assets/b5059210-69a1-4580-bb54-e6a8afb6f261" />
<img width="1125" height="382" alt="image" src="https://github.com/user-attachments/assets/c5d89ead-dda3-4cbf-84d7-71bf9d5902c5" />


Task 3 - Bootstrap Navigation Bar:

Built a fully responsive header using .navbar, .navbar-expand-lg, and .navbar-dark. Integrated JS-driven collapsing behavior via data-bs-toggle="collapse" and data-bs-target="#navbarNav" to convert links into a functional hamburger menu on mobile displays.   

<img width="1917" height="933" alt="image" src="https://github.com/user-attachments/assets/a48620c7-ced3-4d29-9de6-66586beda57b" />


Task 4 - Responsive Portfolio Page:

Combined previous concepts into a structured portfolio page containing a header, collapsible navbar with logo, main content grid, cards section, sticky sidebar, and footer.Applied Flexbox utilities inside cards to force alignment of action buttons.   Configured sticky footer positioning using flex column properties on body (min-height: 100vh) and main (flex: 1). 

<img width="1917" height="983" alt="image" src="https://github.com/user-attachments/assets/b9de0613-f363-449a-98a9-31635ae5ee89" />
<img width="1187" height="948" alt="image" src="https://github.com/user-attachments/assets/cab9a5b4-0144-4ae7-9ff0-2312a4dbbe16" />


Conclusion

All tasks were completed successfully according to Assignment. The resulting portfolio web page demonstrates full responsiveness across multiple viewport widths, clean semantic code structure, and strict adherence to modern HTML5/CSS3 and Bootstrap standards.
