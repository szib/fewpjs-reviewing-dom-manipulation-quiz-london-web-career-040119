# Reviewing HTML Manipulation

Use the following markup to answer the questions below.

```html
<body>
  <section>
    <h1 id="section-heading">Best Dinosaurs</h1>
    <ul>
      <li class="carnivore-link"><a href="http://dinosaurpictures.org/Velociraptor-pictures">Velociraptor</a></li>
      <li class="carnivore-link"><a href="http://dinosaurpictures.org/Tyrannosaurus-pictures">Tyrannosaurus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Diplodocus-pictures">Diplodocus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Apatosaurus-pictures">Apatosaurus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Triceratops-pictures">Triceratops</a></li>
    </ul>
  </section>
</body>
```

Q: What code would we write to remove the section heading?
A:

```javascript
var heading = document.getElementById('section-heading')
heading.remove()
```

Q: What code would we write to create a new `p` element and add it to the page?
A:

```javascript
var p = document.createElement("p")
document.body.appendChild(p)
```

Q: What code would we write to change the class of the first `li.herbivore-link` to "red"?
A:

```javascript
document.querySelector('.herbivore-link').className = "red"
```
