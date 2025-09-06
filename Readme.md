Subject:

Bootstrap **responsive CSS framework**

is a popular **front-end framework** that helps you build **responsive** and **mobile-first** websites quickly. 
It includes **pre-designed components**, a **grid system**, and **utility classes**

Bootstrap will figure out how wide your screen is and respond by resizing your HTML elements - hence the name responsive design.

With **responsive design**, there is no need to design a mobile version of your website.
It will look good on devices with screens of any width.


Example Code: add Bootstrap to any app by adding the following code to the top of your HTML
```
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>
```

With Bootstrap, an image could be exactly the width of our phone's screen, all we need to do is add the **img-responsive** class to your image. 
Do this, and the image should perfectly fit the width of your page.


Center our heading element to make it look better. 
add the class **text-center** to our h2 element.

Example Code: add several classes to the same element by separating each of them with a space
```
    <h2 class="red-text text-center">your text</h2>
```


Bootstrap has its own styles for button elements
With **btn** and **btn-default** classes
**Removed in Bootstrap 4 and later**
In Bootstrap 4 and 5, btn-default no longer exists.
use instead **btn-secondary**


Making them block elements with the additional class of **btn-block**, your button will stretch to fill your page's entire horizontal space and any elements following it will flow onto a "new line" below the block.
Example Code:
```
    <button class="btn btn-default btn-block">Submit</button>
```


The **btn-primary** class is the main color you'll use in your app. 
It is useful for **highlighting actions** you want your user to take.


Bootstrap comes with **several pre-defined colors for buttons**. 
The **btn-info** class is used to **call attention** to optional actions that the user can take.


The **btn-danger** class is the button color you'll use to notify users that the button performs a **destructive action**, such as deleting a cat photo.


Bootstrap uses a **responsive 12-column grid system**, which makes it easy to put elements into rows and specify each element's relative width. 
Most of Bootstrap's classes can be applied to a div element.


Bootstrap's **col-md-***  class. 
Here, **md means medium**, and * is a number specifying how many columns wide the element should be. 
In this case, the column width of an element on a medium-sized screen, such as a laptop, is being specified.

col-xs-*, where xs means extra small (like an extra-small mobile phone screen)


By using the inline span element, you can put several elements on the same line, and even style different parts of the same line differently.

the span with the class text-danger make the text red


**Font Awesome** is a convenient library of icons. 
These icons can be webfonts or vector graphics. 
These icons are treated just like fonts. 
You can specify their size using pixels, and they will assume the font size of their parent HTML elements.

Example Code: include Font Awesome in any app by adding the following code to the top of your HTML
```
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
```


Example Code: add the Font Awesome classes to the i element to turn it into an icon
```
    <i class="fas fa-info-circle"></i>
    <i class="fa fa-trash">
    <i class="fa fa-paper-plane"></i>
```

To add a **thumbs-up icon** to your like button by giving it an i element with the classes **fas** and **fa-thumbs-up**


You can use Bootstrap's col-xs-* classes on form elements, too


All textual <input>, <textarea>, and <select> elements with the class .form-control have a width of 100%.

Example Code:
```
    <div class="container-fluid">
```
Has responsive fixed widths based on screen size.
Adds margins on the left and right (not edge-to-edge).
Best when you want content to be centered and not touch the screen edges.


Bootstrap has a class called **well** that can create a visual sense of depth for your columns.


Not every class needs to have corresponding CSS. 
Sometimes we create classes just for the purpose of selecting these elements more easily using jQuery.

