# Lab 9 Feedback

## 9.2

- [ ] might be useful to add a step where we try to select something (by id, or tag, or whatever) and no such thing is found...

### 9.2.3

- [ ] this brings up the question, "what's the difference between the value and textContent properties?"...call out?

### 9.2.5

- [ ] "...in order to ensure new content gets added to the DOM tree" ... but to someone doing this exercises, doesn't it seem that DOM elements get added using this method? They might wonder "so this method doesn't work all the time?" ... of course, this might be the intent of the original statement...

### 9.2.6

- [ ] perhaps use "**HTMLCollection** object" instead of "list" and "node list" in this step? That would reinforce the concept that these are objects - and that these are not arrays either.
- [ ] "essentially an array" is a bit dangerous, IMO.

### 9.2.7

- [ ] "returns a node list" isn't quite correct - an HTMLCollection is returned

### 9.2.9

- [ ] I would mention that, confusingly, **querySelectorAll** returns a **NodeList** object, which is very much like and **HTMLCollection**...which you can iterate through like an array. But which is not an array. Isn't life grand?

## TYK#1

### 2

- [ ] Mention not to worry about the extra whitespace that's showing up? Or give a hint on ways to get around the problem?

### 3

- [ ] Since there are no img elements outside of the `<ul>`, "within the `<ul>` element" isn't necessary...though it brings up the point that maybe you _could_ add another img in here somewhere so that they grab only the "right" ones....
- [ ]The suggested shadow effect is pretty subtle...perhaps one that "pops" a bit more would be more useful here?

## 9.3

### 9.3.1

- [ ] Interesting that querySelector instead of getElementById used. This could be commented on - that is, why choose one over the other?
- [ ] _side note: this step reminded me that DocumentFragment would be a useful addition to new editions (or perhaps just as comments in lab exercises!)_

## 9.4

### 9.4.5

- [ ] since the addition of 'visible' necessary to make the aside appear, the intent of using it here (to illustrate the use of classList, I assume) might be lost? Add another class instead?
- [ ] actually, you probably want another class as well, if the intent is to show that classList can be used to bring in multiple classes!

## TYK#2

"...to output structured markup content based on object (??)" => object properties?

### 3

- [ ] which photo object prop should be used for the alt? description? or title?

### 5

- [ ] "...keep your code more manageable (and expressive)." (Sorry - I'm a **big** fan of expressive code!)

## 9.5

### 9.5.1

- [ ] var => let/const ?

### 9.5.2

- [ ] change from double quotes to single (for click) intentional?

### 9.5.3

- [ ] there are now 2 event listeners on the first button. Intentional? If so, spend a few words noting the order they trigger? (And the fact multiple handlers possible on a given element for a given event?)

### 9.5.5

- [ ] mention that toggle could be used here as well?
