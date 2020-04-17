Confusion with Bootstrap

Start of index.html with <!DOCTYPE html> to make sure browser knows it is html5

Then in the head section list the viewport and css sheets: bootstrap.min.css, font awesome and bootstrap social for social network buttons. The js scrips are loaded at the end of body tag and include jquery popper and bootstrap. 
Body starts with nav tag to that includes navbar at the top. This has a few components including the button to keep it collapsed and show it only for navbar-expand-sm and also make it fixed-top. Also a navbar-brand to show the logo. 
Wrapping it in navbar-collapse, the navbar-nav is a ul with 4 li items of class nav-item. Each item is a nav-link with span of fa icon along with text.

Next under header tag, introduce jumbotron for tha big strip with headline and image of logo. Wrap up text in row and row-header class. 

Next the rest of page in container div, add section with row, row-content. Make a ribbon kind of thing with media object showing thumbnail on left and content on media body on the right. 

Other than media, simple rows with row, row-content, align-items center with tagline, description etc. 
After these rows, a card to reserve a table in the restaurant. The card is composed of card-header with title and card-body with form group and rows for input. 
After form group rows to collect, there is a button to submit the form that calles the formsubmit()

One of navbar items is contact page, which takes us to concatus.html. 
This page has header, footer and jumbotron copied from index.html with making the contact link active in navbar. 
Right under jumbortron is the breadcrumb with Home/Contact..

Then comes the concat us information: 
Split in col-sm-4 with our address offset by 1 and the col-sm-6 for the map with another offset-sm-1
THen comes col-12 col-sm-11 offset-sm-1 with btn-group classes and a tag with role of button, class=btn and href=tel and mailto with a font-awesome icon of phone and email. 

Next is a row row-content for feedback form starting with col-md-9. A form with multiple form-group row with label and input type=”text’ for firstname, last name, checkbox, select option, then a feedback form and in the end a submit button. 
The footer section is made up from footer tag. The left section in foother is col-4 offset-1 with links with a tags for home, contact, about us. 
Next to it is col-7 with our address

Another link is for about us page, which has the header, footer and jumbotron copied from other pages. First is the our history section. A row row-content split by col-sm-6 made up of paragraphs with card on the leftover section. Card title and card body has rows and dl, dt and dd tags. 

There is also a card card-body tag with a blockquote and blockquote footer. 

Next comes list of leaders showed in a div tag with id = accordion. The list is made up of cars with card-header and role of tab and tag of data-toggle=”collapse”
The card body div has data-parent of accordion. 

