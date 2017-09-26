# Understanding `float` property in CSS

The `float` property in CSS lets you wrap text around an image. CSS makes this wonderful thing happen by allowing elements following a floated element in HTML markup to surround the element so it stays where you need it!

<!--Note: you can not center an object using the float element! Float values are: left, right or none -->

## Components
Let's take a quick look at how the float element works:

Begin with a simple HTML, floating some text around an image, add to HTML a header, image, and some text:

```
<h1> Simple float example </h1>
<img src= "http://whc.unesco.org/uploads/thumbs/site_1513_0001-750-0-20160616135229.jpg" alt="Khangchendzonga National Park"
<p> This is one of many pictures available online of the Khangchendzonga National Park. This picture was found on the unesco website.</p>
<p> This is the national park we will be using as the subject of our class project. Stay tuned for all the interesting things we will discover as a class while working on this project. </p>
```

As with any element, there's a basic structure of ```img {
  float: left;}```. The fantastic, amazing float element instructs the image where to float, either left or right or none. Let's try it out:

```Add this CSS to the HTML suggested above. Use a <style> element or <link> to a separate .CSS file - pick one to try
 body {
   width: 90%;
   max-width: 900px;
   margin: 0 auto;
 }

 p{
   line-height: 2;
   word-spacing: 0.1rem;
 }

```
<!-- You should see the image sitting above the text. With the help of the float element this ugly layout can be transformed into something beautiful -->

``` Add the following to float the image:

img {
  float:left;
  margin-right: 30px;
}

```

You can use more than one floating element but it is important to understand how multiple floating elements interact if you are to use them properly. Let us imagine there are five images inside a div that is 300px wide, and has 10px of margin (5px on the right and 5px on the left). If you multiply 5 (images) by 50px and then multiply 5 by 10px (margin) and add the two together you will discover a div with the total width of 300px will be adequate to hold your images neatly.

## Try it yourself

You can clone this repository and load a local copy of [the tutorial page](./a-tag-tutorial.html) in your browser to see the float element in action. Then make some changes to the file to learn this yourself!

## Learn More

The [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Floats) has lots more detail about this float element!
