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
