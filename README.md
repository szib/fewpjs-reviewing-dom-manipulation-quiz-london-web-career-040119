## Quiz: Reviewing DOM Manipulation

Answer the questions below using the following code example.

```html
<body>
  <h1>List of pets ideal for city-dwellers</h1>
  <div>
    <ul>
      <li><span id="dog">Poodle</span></li>
      <li><span id="king-cobra">Nag</span></li>
      <li><span id="mongoose">Joe Mongoose</span></li>
   </ul>
  </div>
</body>
```

???

# Reviewing DOM Manipulation

?: Which of the following declarations will create a variable whose content CANNOT be changed?

( ) `var lunchOrder = "tofu"`
( ) `let lunchOrder = "soup"`
(X) `const lunchOrder = "rock salt"`

?: Given a method called `razzle`, how do you trigger its behavior? 

( ) `razzle` ( ) `razzle[]` ( ) `(razzle)` (X) `razzle()`

?: In the HTML snippet above, select the JavaScript command that would select the node containing the text "Poodle."

( ) `document.querySelector('.dog')`
( ) `document.querySelector('#king-cobra')`
(X) `document.getElementById('dog')`
( ) `document.getElementById('#dog')`

?: In the HTML snippet above, select the JavaScript command which would select all the `<li>` nodes.

( ) `document.querySelector("li")`
(X) `document.querySelectorAll("ul > li")`
( ) `document.querySelectorAll("ul")`
( ) `document.querySelector("span")`

?: Which of the following JavaScript statements will change the text of the node with the `id` of "dog" to the text "Byron"?

( ) `document.querySelectorAll("span[0]").textContent = "Byron";`
( ) `document.querySelector("#li").innerHTML = "Byron";`
(X) `document.querySelector("#dog").textContent = "Byron";`
( ) `document.getElementsByClass("span")[0].textContent = "Byron"`

?: Talk about bad ideas, king cobras are not good pets. How can we remove the `span` with the `id` "king-cobra"?

( ) `document.querySelector("span").delete("#king-cobra");`
(X) `x = document.querySelector("span#king-cobra"); y = x.parentNode; y.removeChild(x);`
( ) `x = document.querySelector("span#king-cobra"); y = x.parentNode(); y.removeChild(x);`
( ) `document.querySelector("ul").removeChild("span#king-cobra");`

?: We’ve been inundated by cat owners who are angry that we have missed their favorite species of pet. What JavaScript snippet will add an `li` with a `span` inside with the text "Nancy Drew (the cat)" inside to our `ul`?

( ) `document.getElementsByTagName("ul")[0] += "<li><span id=\"cat\">Nancy Drew (the cat)</span></li>";`
( ) `ul = document.getElementsByTagName("ul")[0]; ul.innerText += "<li><span id=\"cat\">Nancy Drew (the cat)</span></li>";`
(X)`base = document.getElementsByTagName("li")[0].parentNode; item = document.createElement("li"); s = document.createElement("span"); s.id = "cat"; s.textContent = "Nancy Drew (the cat)"; item.appendChild(s); base.appendChild(item)`
( )`base = document.getElementsByTagName("li")[0].parentNode; item = document.createElement("li"); s = document.createElement("span#cat"); s.textContent = "Nancy Drew (the cat)"; item.addChild(s); base.addChild(item)`

?: What JavaScript command would return the name of the mongoose?

( ) `document.querySelectorAll("#mongoose").text;`
(X) `document.querySelector("#mongoose").textValue;`
( ) `document.querySelector("#mongoose").text;`
( ) `document.querySelectorAll("#mongoose").content;`

?: Which snippet correctly uses `innerHTML` to replace an HTML document’s body with a `div`containing an `h1` with content "No Pets Allowed"?

( ) `document.querySelector("#body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
( ) `document.querySelector(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
(X) `document.querySelector("body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
( ) `document.querySelectorAll(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>`

?: Changing rendered text in the DOM with JavaScript changes the HTML source.

( ) True (X) False

???
