Subject:

Bootstrap responsive CSS framework.

is a popular front-end framework that helps you build responsive and mobile-first websites quickly. 
It includes pre-designed components, a grid system, and utility classes

Bootstrap will figure out how wide your screen is and respond by resizing your HTML elements - hence the name responsive design.
With responsive design, there is no need to design a mobile version of your website. It will look good on devices with screens of any width.

You can add Bootstrap to any app by adding the following code to the top of your HTML:
Example Code:
```
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>
```

with Bootstrap, an image could be exactly the width of our phone's screen, all we need to do is add the **img-responsive** class to your image. 
Do this, and the image should perfectly fit the width of your page.


center our heading element to make it look better. 
add the class **text-center** to our h2 element.
you can add several classes to the same element by separating each of them with a space, like this:
Example Code:
```
    <h2 class="red-text text-center">your text</h2>
```


Bootstrap has its own styles for button elements
With **btn** and **btn-default** classes


making them block elements with the additional class of **btn-block**, your button will stretch to fill your page's entire horizontal space and any elements following it will flow onto a "new line" below the block.
Example Code:
```
    <button class="btn btn-default btn-block">Submit</button>
```

Step 6

















