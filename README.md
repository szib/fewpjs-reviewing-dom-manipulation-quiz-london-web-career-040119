## Quiz: Reviewing DOM Manipulation

Answer the questions below using the following code example.

```html
<body>
  <h1>List of pets ideal for city-dwellers</h1>
  <div>
    <ul>
      <li><span id="dog">Poodle</li>
      <li><span id="king-cobra">Nag</li>
      <li><span id="mongoose">Joe Mongoose</li>
   </ul>
  </div>
</body>
```

???

# Reviewing DOM Manipulation

?: Which of the following declarations will create a variable whose content can be changed?

[ ] 1
[x] 15
[ ] 14
[x] 17

?: Given a method called `razzle`, How do you trigger its behavior? Select all that apply:

( ) `razzle` ( ) `razzle[]` ( ) `(razzle)()` (X) `razzle()`

?: In the HTML snippet above, select all JavaScript commands which would select the node containing the text “Poodle.”

[X] `document.querySelector(“#dog”)` [X] `document.querySelectorAll(“span”)[0]` [X] `document.getElementById(“dog”)` [ ] `document.getElementById(“#dog”)`

?: In the HTML snippet above, select all JavaScript commands which would select the `<li>` nodes.

[X] `document.querySelectorAll(“li”)` [X] `document.querySelectorAll(“ul > li”)` [X] `document.querySelectorAll(“ul li”)` [X] `document.getElementsByTagName(“li”)`

?: How can we change the text of the node with the `id` of “dog” to be set to “Byron”?

[X] `document.querySelector(“#dog”).textContent = "Byron";` [ ] `document.querySelectorAll(“span[0]”).textContent = "Byron";` [X] `document.querySelector(“#dog”).textContent = "Byron";` [ ] `document.getElementsByClass(“span”)[0].textContent = “Byron”`

?: Talk about bad ideas, king cobras are not good pets. How can we remove the `span` with the `id` “king-cobra”?

[ ] `document.querySelector("span").delete(“#king-cobra”)` [X] `x = document.querySelector(“span#king-cobra”); y = x.parentNode; y.removeChild(x)` [ ] `x = document.querySelector(“span#king-cobra”); y = x.parentNode(); y.removeChild(x) document.querySelector(“ul”).removeChild(“span#king-cobra”);`

?: We’ve been inundated by cat owners who are angry that we have missed their favorite species of pet.

[ ] `document.getElementsByTagName(“ul”)[0].write(“<li><span id=\”cat\”>Nancy Drew (the cat)</span></li>”);` [X] `base = document.getElementsByTagName(“ul”)[0]; item = document.createElement(“li”); s = document.createElement(“span”); s.id = “cat”; s.textContent = “Nancy Drew (the cat)”; item.appendChild(s); base.appendChild(item)` [X] `base = document.getElementsByTagName(“li”)[0].parentNode; item = document.createElement(“li”); s = document.createElement(“span”); s.id = “cat”; s.textContent = “Nancy Drew (the cat)”; item.appendChild(s); base.appendChild(item)` [ ] `base = document.getElementsByTagName(“li”)[0].parentNode; item = document.createElement(“li”); s = document.createElement(“span#cat”); s.textContent = “Nancy Drew (the cat)”; item.addChild(s); base.addChild(item)`

?: What JavaScript command would return the name of the mongoose? Use `document.querySelector` to target the containing node.

( ) `document.querySelectorAll(“#mongoose”).text;` (X) `document.querySelector(“#mongoose”).textValue;` ( ) `document.querySelector(“#mongoose”).text;` ( ) `document.querySelectorAll(“#mongoose”).content;`

?: How could you use `innerHTML` to replace the entirety of the HTML document’s body, targeted directly, with a `div`containing an `h1` whose content is “No Pets Allowed”?

( ) `document.querySelector("#body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"` ( ) `document.querySelector(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"` (X) `document.querySelector("body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"` ( ) `document.querySelectorAll(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>`

?: Changing rendered text in the DOM with JavaScript changes the HTML source.

( ) True (X) False

???
