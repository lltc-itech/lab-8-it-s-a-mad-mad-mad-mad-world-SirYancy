# Lab 8 - It's a Mad, Mad, Mad, Mad World

This is a classic computer programming exercise. You have to know about forms, input and output, string manipulation, and functions. And you get to be creative! You're going to have fun.

You are going to build a Mad-Lib. If you don't know what a Mad-Lib is, [check these out](https://www.madlibs.com/). In the file `index.html`, you will find a mostly blank web page. In it, you will build a Mad-Lib. You can be as creative as you wish with this story, but make sure it is at least a paragraph long and should have at a reasonable number of inputs to keep things interesting and practice techniques.

Here are the requirements: 

* You must have at least five text entry boxes and one submit input (a button) in your form.
* Your form must call a function which will be defined in `madlib.js`
* Use `<label>` elements to label each text box so the input will fit in a mad-lib story that you will write.
* You must use at least one of your text inputs more than once.
* Change any web-page content/code/text that looks like it should be changed (headers, comments, etc)
* When the user hits `Enter` or clicks the Submit button, the text should be generated and inserted into an empty `<div>` (or other appropriate) element that you will have to create (it will need an `id` attribute!
* The mad-lib story should appear as a nicely formatted paragraph or two. Be very aware of how sentences and paragraphs are generated in HTML and how you would include tags in the output so that it looks nice.

## Hints

* You shouldn't have to worry too much about type conversions since this is pure string manipulation and the input from a textbox is always a string.
* Have fun with this. Be creative but tasteful. No low-effort submissions.
* When testing, make sure you read your outputs carefully so you see where spaces and things are being arrayed.
* Also when testing, a nice strategy is to add a `value` attribute to each `<input>` element so they have a default value and you don't have to keep typing something into each box each time you want to test your madlib. Just remember to delete these attributes when you're ready to submit.
* Extra credit if you style it up with CSS.
