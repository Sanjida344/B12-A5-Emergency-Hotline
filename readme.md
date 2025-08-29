1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?


ans:getElementById-returns one element,,
getElementByClass-returns multiple element,
querySelectorALl -node list and loop with forEach()
querySelector-supports all selectors


2.How do you create and insert a new element into the DOM?

ans:document.createElement(tagName).

and insert into the dom-appendChild()-(adds as the last child)

3.What is Event Bubbling and how does it work?

ans:Event bubbling = event moves child travels upward and triggers handlers on parents along the way.

4.What is Event Delegation in JavaScript? Why is it useful?
ans:When event occurs on a child it bubbles up to the parent and the parent single event listener handles it and bubbling under the hood.

5.What is the difference between preventDefault() and stopPropagation() methods?

ans:Use preventDefault()  want to stop the browsers built in action.
topPropagation()  want to stop the event from reaching other elements.