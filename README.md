# Adding a new product feature:

* From the main page, open up `index.html`. Go to the edit icon to start editing.
* Go to `<ul>` section with the class `product-features`. (`<ul class="product-features">`), but check to make sure the content is the list of product features because the Stockist list has the same tags with the same class names.
* Each product feature needs to be within the `<ul> </ul>` tags.
* Each product feature needs to within it's own `list-item` tags with the class `product-features--list-item`.
* Example: `<li class="product-features--list-item">This product is the best</li>`

# Adding a new Stockist

* Follow the same rules above, except make sure the section you're working on is the stockist section.
* This time when you add a new store, you will also add a link/anchor tag. Inside the `<li></li>`, the name of the store will go inside an `<a></a>` tags.
* The `<a></a>` tags will need to have attributes in the following format: `<a href="WEBSITE LINK HERE">NAME YOU WANT TO APPEAR</a>`.
* For the store location, you need to create another `<ul class="product-features"><li class="product-features--list-item">Store location</li></ul>`
* This has to be at the same level of the list item with the link. So it's another `<ul></ul>` inside of the top level `<ul></ul>`

# Saving your changes

* After you've made your changes, commit everything using the inputs at the bottom.
