## **\<h1\> --- \<h6\>** - Heading
The `<h1> --- <h6>` elements represent a section heading in a hierarchal manner such as below. 

<img src='screenshots/html/sc4.png' width=148 height=283/>

`<h1>` is the most important heading while `<h6>` is the least important heading. The general rule is that use the `<h1>` element once per page as the main heading and do not skip the heading levels, e.g. `<h1> -> <h5>`. Below is an example of a page using this format

```html
<!DOCTYPE html>
<html> 
    <body>
        <h1>Learning HTML</h1>
        <h2>What is HTML?</h2>
        <p>Explanation on what HTML is...</p>
        <h2>HTML Tags<h2>
        <h3>Tag #1</h3>
        <p>Explanation on Tag #1...</p>
        <p>Second explanation on Tag #1...</p>
        <h3>Tag #2</h3>
        <p>Explanation on Tag #2...</p>
        <h3>Tag #3</h3>
        <p>Explanation on Tag #3...</p>
        <h2>Learning CSS</h2>
        <h3>What is CSS?</h3>
        <p>Explanation on what CSS is...</p>
    </body>
</html>
```


<img src='screenshots/html/sc5.png' width=241 height=585/>

## **\<p\>** - Paragraph
The `<p>` represents a paragraph of graph. It is used to give your webpage structure by separating content into blocks of text

```html
<!DOCTYPE html>
<html> 
    <body>
        <h2>Important of the environment</h2>
        <p>The environment is important because... Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur porta dictum neque, at tristique leo. Ut in placerat metus, ac pretium magna. Nulla semper velit est, et egestas diam iaculis non. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Sed accumsan molestie eros eu fringilla. Duis et nulla risus. Nunc interdum eu est id dignissim. Vestibulum interdum rhoncus enim, laoreet tristique purus accumsan eu. Vivamus blandit dui ut est semper, id dapibus turpis rhoncus. Proin sit amet scelerisque justo. Sed nec pharetra nisi. Cras congue faucibus arcu commodo vehicula. Mauris posuere rhoncus orci, eget pretium justo ultrices a. Donec interdum erat in consequat cursus.</p>
    </body>
</html>
```

<img src='screenshots/html/sc6.png'/>


## **\<ul\> | \<ol\>** - List Elements
The `<ul>` and `<ol>` allows you group a list of related items together. Within these elements, each contain list items which are noted as `<li>` element. The difference between `<ul>` and `<ol>` will be shown below.

`<ul>`: *Unordered List* - the order of the list items does not matter, renders a bullet point before each item
```html
<!DOCTYPE html>
<html> 
    <body>
        <h1>My Favorite Food</h1>
        <ul>
            <li>Pizza</li>
            <li>Peanut Butter & Jelly</li>
            <li>Sushi</li>
            <li>Pancakes</li>
        </ul>
    </body>
</html>
```

`<ol>`: *Ordered List* - the sequence of list items matters, renders a number before each list element to show order
```html
<!DOCTYPE html>
<html> 
    <body>
        <h1>How to Make an Awesome Peanut Butter & Jelly</h1>
        <ol>
            <li>Get two slices of bread</li>
            <li>Put peanut butter on one slice</li>
            <li>Put jelly on the other slice</li>
            <li>Place the two slices of bread on top of each other</li>
            <li>Enjoy!</li>
        </ol>
    </body>
</html>
```
<img src='screenshots/html/sc7.png'/>

## **\<img\>** - Image Embed
Let's say you want to add an online image to your webpage. Then you can use the `<img>` element. For the `<img>` element to render you will need a image link and add a attribute to the `<img>` element. Attributes allows us to supply more information element for it to render. Different attributes require different values. They can be required, like *src*, or optional like *width* and *height*. Let's add [this](https://cdn.pixabay.com/photo/2021/09/19/12/19/animal-6637774_1280.jpg) image to our webpage (Courtesy of yamabon). 

Notice how `<img>` does not have a closing tag!

```html
<!DOCTYPE html>
<html> 
    <body>
        ...
        <p>I am creating my very <b>first</b> webpage</p>
        <img src="https://cdn.pixabay.com/photo/2021/09/19/12/19/animal-6637774_1280.jpg" width=100 height=100>
    </body>
</html>
```

Now what if we wanted to use our own images? We can replace the *src* link with a relative path where our images are located. In the same directory as `index.html`, create a new folder called `images`. Then add your image to this folder, or you can save [this](https://cdn.pixabay.com/photo/2019/07/30/05/53/dog-4372036_1280.jpg) image to your folder (Courtesy of birgl). Remember to rename your image to something like `dog.png`.

<img src='screenshots/html/sc8.png'/>
<img src='screenshots/html/sc9.png'/>

Modify your *src* attribute like so:

```html
<!DOCTYPE html>
<html> 
    <body>
        ...
        <img src="images/dog.png">
    </body>
</html>

```
?> Note that your image file extension should match up in the *src* attribute

Here we use a file path to point to our image. Starting from the current directory of `index.html`, it navigates into the `images` file and renders the image with the exact file name in the *src* attribute.

## **\<a\>** - Anchor 
The `<a>` element is used for creating hyperlinks to other web pages, emails, files, or anything that can placed into a URL. The most important attribute of `<a>` element is the *href* attribute, the URL link which a page linked to. Below are some examples of using the `<a>` element.

```html
<!DOCTYPE html>
<html> 
    <body>
        <a href="https://www.youtube.com/">Youtube<a/>
        <a href="https://www.youtube.com/" target="_blank">Open Youtube in a new tab<a/>
        <a href="mailto:averycoolemail@example.com">Send Email</a>
        <a href="tel:+123456788">Phone Number</a>
        <a href="#locationOnOtherPage">Another location on the page</a>
    </body>
</html>
```

<img src='screenshots/html/sc10.png' height=219 width=268/>