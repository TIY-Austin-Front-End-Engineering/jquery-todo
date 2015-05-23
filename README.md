# jQuery to-do

## Description
Create a to-do list in jQuery


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand how to use jQuery to select elements
* Understand how to use jQuery to manipulate elements
* Understand how to use event objects


### Performance Objectives

After completing this assignment, you be able to effectively use

* $('...')
* $element.val()
* $element.html()
* $element.css()
* e.preventDefault()



## Details

### Deliverables

* A repo containing at least:
  * `dist/main.js`
  * `dist/index.html`

### Requirements

* No JSHint warnings or errors
* No W3C validation errors


## Normal Mode
1. Start with a fresh project. Follow the steps from the [vanilla to-do list](https://github.com/TIY-Austin-Front-End-Engineering/vanilla-todo) assignments, but use jQuery where applicable.
2. Add click event listeners to each of your todo items as they are added to your html. When a to-do item is clicked, it should have a line strike through it.

## Hard Mode
1. Update the array that stores to-do items to store objects instead of strings. Each object should look like:
        ```js
        {
        	id: 1,
        	todo: 'wash the car',
        	completed: false,
        	deleted: false
        }
        ```
2. Update your render function to now properly render an array of objects instead of an array of strings. It should ignore (not show) objects that have their deleted property set to true. It should render items with a completed property of true as having a strike through.
3. When a to-do item is clicked on, update that item in your array to have a completed value of true and then re-render the list.

## Nightmare Mode

1. When a new item is added to your array, also make a $.post request to tiny pizza server with the appropriate todo, completed, and deleted properties.
2. When the page loads, pull all entries from tiny pizza server, save them to your array, and call your render function.
3. When an item is clicked on, update its completed property to true, make a $.put request to tiny pizza server to update its todo, completed and deleted properties. Then call your render function.
4. Try and figure out a way to permanently delete a to-do item so that it no longer shows up on your page.
            


## Notes

Notes go here...

## Additional Resources

* Read []()
