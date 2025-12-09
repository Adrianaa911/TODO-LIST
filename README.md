 -- TO-DO LIST --

Created a to-do list webpage where you can add, replace and delete your list. To create this page I've used HTML, CSS and JavaScript.

I've encountered some issues, but managed to fix it and make it work. This were the bugs:

1. Had an error- a type error in my code. When applied the Event listener it was null so I've made some changes in my code, starting with html-where I changed the button class into id and modified on js and css style sheet.

2. Has an style problem- my tick didn't appeared as It should.

3. The 'deleteAllTasks' button was used incorrectly, didn't worked and had to fix it. I was still calling the function instead of passing it, like this: 'deleteButton.addEventListener("click", deleteAllTasks());
'. There was no event handler attached correctly, therefore nothing happens immediately when the page loads, NOT when the user clicks. So I've pass it, like so: 'deleteAllTasks()' .


This project can be view following the link below:

https://adrianaa911.github.io/TODO-LIST/
