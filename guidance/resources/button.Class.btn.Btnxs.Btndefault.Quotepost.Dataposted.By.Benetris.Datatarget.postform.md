## <button class="" "btn="" btn-xs="" btn-default="" quote-post"="" data-posted="" by="" "benetris"="" data-target=""></button>

 
![<button Class ](https://u.jimcdn.com/cms/o/s753bd862094ba8c5/emotion/crop/header.jpg?t=1468864448)

 Here is what I came up with:  
# How to Quote a Post Using a Button in HTML
 
In this article, we will learn how to create a button that can quote a post from another user in a forum or a blog. This can be useful if you want to reply to someone's comment or opinion with your own thoughts.
 
## <button class="" "btn="" btn-xs="" btn-default="" quote-post"="" data-posted="" by="" "benetris"="" data-target=""></button>


[**DOWNLOAD**](https://www.google.com/url?q=https%3A%2F%2Furluso.com%2F2tKGIQ&sa=D&sntz=1&usg=AOvVaw3_ftjjoq4dyz7IDwUxUK5J)

 
To create a button that can quote a post, we need to use some HTML attributes and some JavaScript code. Here are the steps:
 
1. Create a `<button>` element with the class `btn btn-xs btn-default quote-post`. This will style the button according to the Bootstrap framework. You can change the class names if you are using a different CSS framework or your own custom styles.
2. Add a `data-posted-by` attribute to the button and set its value to the name of the user who posted the original comment. This will help us identify the source of the quote.
3. Add a `data-target` attribute to the button and set its value to the id of the form element where you want to insert the quoted text. This will help us find the destination of the quote.
4. Add an `onclick` attribute to the button and set its value to a JavaScript function that will copy the text from the original post and paste it into the form element. We will write this function in the next step.
5. Create a JavaScript function that will take two parameters: the button element and the event object. The function will do the following:
    - Get the value of the `data-posted-by` attribute from the button element and store it in a variable.
    - Get the value of the `data-target` attribute from the button element and store it in another variable.
    - Find the parent element of the button element, which should be a `<div>` element that contains the original post text. Get its innerHTML and store it in another variable.
    - Wrap the original post text in a `<blockquote>` element and add a citation with the name of the user who posted it. Store this in another variable.
    - Find the form element with the id that matches the value of the `data-target` attribute. Get its current value and append the quoted text to it. Set this as the new value of the form element.

Here is an example of how the HTML code for the button and the JavaScript function might look like:
  ```html <button data-posted-by="Benetris" data-target="post-form" onclick="quotePost(this, event)">Quote</button>   ``` 0f148eb4a0
