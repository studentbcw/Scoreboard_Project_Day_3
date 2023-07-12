# Instructions  

## BUILDING
#### What Happens When I Click It?
Build small, test small! Let's write a function that logs to the console when a button is clicked.

```js
console.log("Button Connected")
```

In the *index.html* file, add an "onclick" event handler to the "increase score" button that calls your function from above.

## Increase the Score
Once you are sure that the button is working, try setting up a variable like this.

```js
let score = 0
```
Inside your function, under the console.log("Button Connected"), increase the score variable by one each time the button is clicked.

## Draw the Score to the Webview

In your *index.html* file, add an `id` attribute to the <h1> tag that shows the score.

In your *script.js* file, let's write a function called draw()  that grabs the html element using 

```js
document.getElementById("")
```
and saves this element into a variable called `scoreElement`.

Now, you can change the value of the `scoreElement` by setting the innerText of this element equal to score.

We still need to call our draw() function! Let's put draw() at the bottom of our other function (the one that increases the score). 

Now, watch as every time you click the increase score button, the score goes up!

## STRETCH GOALS

If you finish early, try adding another button that decreases the score by one each time it's clicked. 

OR

In the `style.css` file, find the `.bg-image` CSS class, and change the background to another background in our assets folder.

