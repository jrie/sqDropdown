# sqDropdown
A simple javascript select box enhancement which provides searching and nicer multiple selections.

### Features
* Select single or multiple values
* Search select dropdown values while typing into the main area of focus
* Offers a somehow pleasent view of items
* Simple setup

### Usage
See 'index.html' for details on how to setup the items.  

In short, create a `select` element or elements with a base option structure, like you would do normally. You can also use `selected` options.

Add the class `sqDropdown` to the `select` element or elements - also add a unique data attribute `data-originid` with the numbered index of the sqDropdown you want to add. This is required to help the script target the correct dropdown.

Now include the `css` and `js` code which you like to use, either the regular or the minified version. The `index.html` shows the unminified setup. After the css class is added and the script is loaded, the magic will appear.

Reload the page and check out the nicely put dropdowns.
