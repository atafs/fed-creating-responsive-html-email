# Assignment
Build an HTML responsive email using the mockup and images attached

### Design and Pattern choices:
- I have chosen the Responsive Design with Tables, in order to render acceptably over more than 30 of the most popular web-based email clients.

### Setting Expectations:
- Responsive Email design may negatively affect the layout for older, web-based email clients.
- Single column emails will render properly in most number of them.
- Simply flowing the elements to the right or left.
- In order to scale to more complex emails layouts, that gracefull degrade in older email clients, this choice allows to change the screen size in a responsive way (breaking down elements and customizing them to specific screen sizes).

### Details about Specifications:
Base HTML Structure:
- Since most email clients don't support a full range of HTML and CSS (creates challenges for responsive designs).
- We have the ability to take container such div or other elements and move those elements when we resize the browser.
- When a table size changes, all the td's will get smaller but we can't change the relationship of them (they are locked inside that table structure).
- To get around this limitation, I create full tables with individual content. And when the width changes, I am moving the entire tables around.

Responsive Content:
- For now, the structure is created to support a responsive page, that adapts to the screen sizes by changing their elements (images, text and so on).
- To get a fully responsive page without seing scroll bars, I still need to create smaller images in photoshop or similar program.
- To then add them to the media queries that would reflect the changes in the html code.
- I would also need the design specifications of how the page should behave and how it is breaking down their elements
Thank you very much for the opportunity to make this assignment.

Cheers
Americo 
