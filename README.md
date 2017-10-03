# Understanding `float` property in CSS

The `float` property in CSS lets you wrap text around an image. CSS makes this wonderful thing happen by allowing elements following a floated element in HTML markup to surround the element so it stays where you need it!

Note: you can not center an object using the float element! Float values are: left, right or none.

## Components
Let's take a quick look at how the float element works:

Begin with a simple HTML, floating some text around an image, add to HTML a header, image, and some text:

<h1> Simple float example </h1>


<img src="http://whc.unesco.org/uploads/thumbs/site_1513_0001-750-0-20160616135229.jpg" alt="Khangchendzonga National Park"/>

<p> This is one of many pictures available online of the Khangchendzonga National Park. This picture was found on the unesco website.</p>
<p> This is the national park we will be using as the subject of our class project. Stay tuned for all the interesting things we will discover as a class while working on this project. </p>


As with any element, there's a basic structure of
 ```
 img {  
      float: left;
  }
  ```

The fantastic, amazing float element instructs the image where to float, either left or right or none. Let's try it out:

Add this CSS to the HTML suggested above:

```
img {

  float: right;
  width: 500px;
}
```

With the help of the float element the image is no longer confined to a position above or below the text!

Try floating the image to the right then the left. What happens when you float: none? Now adjust the width and play around with the height until you are satisfied with the presentation of the page.
Start with the following, then get creative!

```
image {
  float: left;
  width: 500px;
  height: 250px;
}

```

You can use more than one floating element but it is important to understand how multiple floating elements interact if you are to use them properly. Let us imagine there are five images inside a div that is 500px wide, and has 10px of margin (5px on the right and 5px on the left). If you multiply 5 (images) by 50px and then multiply 5 by 10px (margin) and add the two together you will discover a div with the total width of 300px will be adequate to hold your images neatly.

After you learn all about margins try this advanced challenge: search for 4 images related to Khangchendzonga National Park. Float 2 of those images to the left of the image in the above example and 2 to the right of the example image. You have now created a photo gallery that can be used on a website, congratulations!!!  

## Try it yourself

You can clone this repository and load a local copy of [the tutorial page](./float-property-tutorial.html) in your browser to see the float element in action. Then make some changes to the file to learn this yourself!

## Learn More

The [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Floats) has lots more detail about this float element!
