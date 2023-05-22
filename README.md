# Here i Create a Search filter

```
Welcome to My Github Profile.
as I create a Search filter from scratch using HTML, CSS, and JavaScript.
```
1) The code selects the search input field using its id and assigns it to the variable searchbar.
2) An event listener is attached to the search input field, listening for the 'input' event. Whenever the user types or changes the input, it triggers the fliterList() function.
3) The fliterList() function is defined, which is called when the 'input' event occurs.
4) It retrieves the value entered in the search input field, converts it to lowercase, and assigns it to the filter variable.
5) The code selects all elements with the class 'list-group-item' and assigns them to the listItems variable.
6) It iterates over each item in the listItems collection using a forEach loop.
7) For each item, it retrieves the text content and assigns it to the text variable, converting it to lowercase.
8) It checks if the lowercase text includes the lowercase filter. If it does, it sets the item's display style to "block" to show the item.
9) If the lowercase text does not include the lowercase filter, it sets the item's display style to "none" to hide the item.
10) The loop continues until all items in the listItems collection have been processed, and the function execution ends.
Overall, this code sets up an event listener for a search input field, and when the user enters text, it filters a list of items based on the search input, showing or hiding the items accordingly.


![image](https://github.com/ParagUnhale1998/Search-Filter/blob/main/Thumbnail.png)
