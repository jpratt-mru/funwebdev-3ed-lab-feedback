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

- [ ] mention that `toggle` could be used here as well?

## 9.6

### 9.6.3

- [ ] _maybe_ be clear that they should be editing `lab09-ex05.js`...though it _is_ kind of obvious?...
- [ ] the given code in the DOMContentLoaded handler starts with the code they were doing in 9.5.3, skipping 1 & 2, which might cause confusion
- [ ] opportunity to mention difference between `e.target` and `e.currentTarget`?

## 9.7

### 9.7.1

- [ ] propogate => propagate

### 9.7.2

- [ ] suggest that they clear the console after every click; otherwise the console will be very "noisy" and it'll be harder to see what's happening!

### 9.7.3

- [ ] might need to be clearer that this needs to go in the load handler...
- [ ] opportunity to again mention multiple handlers on a single element and the order they fire?

### 9.7.4

- [ ] propogated => propagated

### 9.7.5

- [ ] make location (inside the load handler) explicit

## 9.8

### 9.8.2

- [ ] "...each one representing a single stock ~~symbol~~"

### 9.8.4

- [ ] "and assign event handlers..." => assigning
- [ ] "after the code from the previous step": unfortunately, that includes the load handler!
- [ ] use single quotes in `== "img"` for consistency

### 9.8.5

- [ ] use single quotes in `= "block"` for consistency

## TYK#3

Was the intent here to add 5 individual event listeners? Or just use event delegation? Or give them an option? (If so, being explicit might be useful here....) The instructions, are of course, specific...but an adventurous soul who thinks they're being clever using event delegation is going to be bitten:

- I'm seeing some very interesting behaviour (at least in Chrome) - if we use event delegation on the div.panels, then any clicks in one of the `<p>`s skips the parent `div.panel`!

- So if they decide to use event delegation, they won't see the expansion occur if the click on the p's...which take up quite a bit of room!

## 9.9

This is a fun exercise...but there is a lot of "magic" going on here for learners doing this sucker at this point in the textbook. Almost so much that the focus of the exercise (keyboard event handling) is somewhat lost?

### 9.9.2

- [ ] missing a `);` at end of code block

### 9.9.3

- [ ] maybe keep the `audio.currentTime = 0;`? it's just one line, like the `...`!

### 9.9.5

- [ ] "...look at the .key and .playing CSS classes. Notice the transition property?" => `.playing` doesn't have a transition property!

### 9.9.6

- [ ] 'keypress' is used as the event instead of 'keydown'
- [ ] 'load' is used instead of 'DOMContentLoaded'
- [ ] it's not clear where the new code should go...before the previous playSound and what followed it?

## 9.10

This is a tough one. Being even a bit comfortable with the debugger is uber-important. Even trying out a few of the basics here is really useful...but this could be expanded quite a bit and be even more useful. (Or maybe split into a number of exercises instead of just one?)

## 9.11

Might be useful to point people to some docs on `<video>`? Though, ideally, they should be engaging their natural curiosity and doing so without prompting. Yup.

### 9.11.4

- [ ] const `vol` is created, but not used in the following `addEventListener` call...though the code still "works", because global variables are being made for each element with an id!

## 9.12

### 9.12.1

- [ ] "...when the images become visible in the browser." => the img elements? (because "images" might be misconstrued as "the completed images")
- [ ] "As well, CSS for the img tag ensures..." => is this necessary? If so, perhaps it can be moved to a comment elsewhere? It seems a bit out of place here.
- [ ] "uses version" => versions

### 9.12.2

- [ ] `orientationchange` has been deprecated: https://developer.mozilla.org/en-US/docs/Web/API/Window/orientationchange_event
- [ ] orientationChange => orientationchange (might be a moot point due to deprecation?)

### 9.12.3

- [ ] Is the comment at the bottom - which just, as it states, repeats the comment in the code - necessary?
- [ ] the purpose of the opening if statement is a bit opaque...it depends on knowing what `setTimeout` returns, knowing the intent of `if (lazyloadThrottleTimeout)`, and knowing that there's a `clearTimeout` in the Web API.
- [ ] what purpose does the `if (images.lenth == 0)` serve? When will the original images NodeList every change here?

## 9.13

### 9.13.3

- [ ] might not be necessary to say the "This assigns an anonymous function...." bit, since they've done a bunch of these in a row without a reminder. Or reword it a bit: "The anonymous function on the load event assigns the setBackground function to the blur and...."?
- [ ] switch around steps 3 and 2? Previous exercises have put the handler function after the invocation (like for updateButton in ex 9.11)...but perhaps it is good to show that you can have a function declaration before its use. But if that was the intent, maybe mention it in the relevant steps?

### 9.13.4

- [ ] "Tab between..." => "Move between different fields with tab or the mouse."?

## 9.14

Maintain consistent use of ' and "

### 9.14.3

- [ ] "Experiment by filling in some fields, leaving others blank. Also try putting just spaces in some fields."

### 9.14.4

- [ ] comment says to "hide the error message element" but since it starts off hidden, this might cause confusion. Maybe "hide the error message from previous attempts"? or something like that...
- [ ] greyed out code uses `var msg` instead of `let msg`
- [ ] might need to be a bit more explicit that the last two added lines replace the alert?
- [ ] need to justify use of `innerHTML` instead of `createElement`?
- [ ] "...shown in FIgure 9.6" => 9.7
