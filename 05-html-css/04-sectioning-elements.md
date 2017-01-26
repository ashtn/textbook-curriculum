# Sectioning Elements


## 📚 Learning Goals 📚
- Can organize content using semantic sectioning tags
- Know why we organize content with semantic sectioning tags

## What are Sectioning Elements
HTML has sectioning elements that allow you to organize your HTML document into logical, topical sections.

They bring a big advantage for people who need the structure to help them understand the page, for instance people needing the help of some assistive technology, like a [screen reader](http://webaim.org/techniques/screenreader/).

Below are some common sectioning tags

```html
  <body> </body>

  <div> </div>

  <section> </section>

  <article> </article>

  <nav> </nav>

  <aside> </aside>

  <header> </header>

  <footer> </footer>
```
**Think, Pair, Share**
- On your own, research how to use each of the above tags.
- Then, discuss with your chair pair.
- And then, high five each other. 👏🏾

## Organize content with Sectioning Elements
Sectioning elements wrap around the elements we have already been working with. Organizing elements into sectioning elements will also become useful as we start to style the layout of our webpages.

Here are a couple of diagrams that show how sectioning elements will be used to wrap around  content, based on layout designs:   
![Sectioned Elements Diagram](imgs/section_elements.gif)
<img src="imgs/section_elements2.png" alt="[Another Sectioned Elements Diagram" style="width: 500px;"/>

## Element Relationships
When elements become nested inside of each other they start to form relationships.
- An element that is inside of an other is a **child-element**
- The element wrapping a child is the **parent-element**.
- Elements on the same level as each other are **sibling-elements**.

A visual diagram of elements relationships to each other:
![Element Relationship Diagram](imgs/content-hierarchy-diagram.png)

The relationship tree above is modeled from the following code:
```html
<body>
  <header>
    <h1><a href="index.html"> Favorite Things </a></h1>
  </header>
  <article>
    <h2> A Few of my Favorite Things  </h2>
    <p>
      Biscuit dragée marzipan marzipan sweet roll sweet roll jujubes. Sesame snaps gummi bears jelly beans candy canes danish. Biscuit jelly beans brownie. Cake pastry biscuit bonbon donut bonbon.
    </p>
  </article>
  <footer>
    <h3> &copy; 2016 </h3>
  </footer>
</body>
```


### Draw a relationship tree for the html code below:
```html
  <body>
    <header>
      <h1> Sweet Spot </h1>
      <nav>
        <ul>
          <li><a href="#"> Login  </a></li>
          <li><a href="#"> Signup </a></li>
        </ul>
      </nav>
    </header>
    <section>
      <h2> Recent Posts</h2>
      <article>
        <header>
          <h3> I WANT IT ALL </h3>
          <h4> By: Veruca Salt </h4>
        </header>
        <p>
          Powder marshmallow apple pie jujubes. Oat cake pastry sugar plum cake sweet. Fruitcake wafer candy canes candy canes apple pie caramels sweet roll candy topping. Apple pie gummies halvah jelly-o apple pie gummi bears gingerbread. Donut ice cream topping carrot cake.
        </p>
        <p>
          Tiramisu jelly beans apple pie cotton candy dragée gummi bears. Candy canes dessert gingerbread pastry gummies sweet roll icing marzipan donut. Chupa chups donut danish candy liquorice fruitcake wafer donut brownie. Oat cake pudding dragée cotton candy ice cream cotton candy. Pudding jelly lemon drops halvah cupcake. Jujubes brownie marshmallow caramels cake.
        </p>
      </article>
      <article>
        <header>
          <h3> Top 10 Sites to See at Gumdrop Mountain! </h3>
          <h4> By: Princess Lolly </h4>
        </header>
          <p>  
            Wafer bear claw marshmallow soufflé icing bonbon sugar plum. Gingerbread jujubes toffee ice cream croissant gingerbread muffin bonbon. Donut gingerbread tart chocolate cake fruitcake cookie chocolate bar brownie muffin. Marzipan marzipan bonbon topping brownie tiramisu tootsie roll biscuit. Pudding topping icing chocolate bar.  
          </p>
          <p>
            Apple pie gummies donut cupcake liquorice lollipop gummi bears cotton candy gummi bears. Sesame snaps jujubes tiramisu carrot cake tootsie roll. Wafer jelly icing muffin bear claw carrot cake. Topping jelly lollipop dragée jelly chocolate cake wafer bonbon.
          </p>
      </article>
    </section>
    <footer>
      <ul>
        <li><a href="#"> Contact </a></li>
        <li><a href="#"> Contribute </a></li>
        <li><a href="#"> Careers </a></li>
      </ul>
    </footer>
  </body>
```


## Best Practices
- Avoid using too many <div> tags as sectioning tags.
- It common to have many sectioning tags nested within each other.


## Vocab ✅
  - Semantic
  - Sectioning
  - Parent
  - Child
  - Sibling


## 🔑 Key Takeaway
Using semantic sectioning tags provides more meaningful and consistent structure to our HTML code. It also makes it easier for people that rely on screen readers and to target HTML with CSS and JavaScript.


### Additional Resources
- [MDN Article: Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure) (Highly Recommended, should be mandatory. Just read it. )
- [Treehouse Blog Post](http://blog.teamtreehouse.com/use-html5-sectioning-elements) (Also great, and highly recommended)
- [Element Relationships](http://www.littlewebhut.com/css/info_element_relationships/)
- [A Look Into Proper HTML5 Semantics](http://www.hongkiat.com/blog/html-5-semantics/)
