# CSS_TASK4

## ASSIGNMENT 

Create a simple html page with the following list:

```html
    <ul class="fruits">
        <li>Apple</li>
        <li>Banana</li>
        <li data-foodtype="squishy">Orange</li>
        <li>Pear</li>
        <li>Kiwi</li>
        <li id="berry">Strawberry</li>
    </ul>
````

Write the answers into the browser console, using console.log().

Some help:<br>
https://www.w3schools.com/jsref/prop_html_innerhtml.asp<br>
https://www.w3schools.com/cssref/sel_attribute_value.asp
<br>

1. Use **getElementById()** to find the `<li>` element that contains the word "Strawberry". Print out both the **html element** and the **innerHTML**. Change the background color of the list element to red.

```
-> <li id="berry">Strawberry</li>
-> I found the berry: Strawberry
```
<br>

2. Now find the `<li>` element that contains the word Orange. Use the **QuerySelector()** method with a **CSS [attribute=value] Selector**. Change the background color of the list element to orange.

```
-> <li data-foodtype="squishy">Orange</li>
-> I found the fruit: Orange
```
<br>

3. 1 - Use **getElementsByTagName()** to return a collection of all the `<li>`elements in the document. Use console.log to see that it is a HTMLCollection with 6 child elements. Study the HTMLCollection.
```
-> HTMLCollection(6) [li, li, li, li, li, li#berry, berry: li#berry]
```
<br>

3. 2 - Use a **for loop** to print out the name of the fruits from the previous collection. In the loop, change the background color of the list element containing "Pear" to green. Give the `<li>`elements a width of 100px and change the list-style-type to none to remove the bullets.
```
-> Using the for loop here:
-> Apple
-> Banana
-> Orange
-> Pear
-> Kiwi
-> Strawberry
```
<br>

4. 1 - Use **QuerySelectorAll()** to return a collection of all the `<li>`elements in the document. Use console.log to see that it actually is a NodeList with 6 child elements.
```
-> NodeList(6) [li, li, li, li, li, li#berry]
```
<br>

4. 2 - Use **forEach()** to iterate over the list and print out the name of the fruits. Add borders around each `<li>`element.
```
-> Using forEach here:
-> Apple
-> Banana
-> Orange
-> Pear
-> Kiwi
-> Strawberry
```
If you are done, you should see something like this:<br>
https://github.com/vynmetropolia/CSS_TASK4/blob/master/css_task4.png
