# Lab 10 Feedback

## general notes

- [ ] choose whether to go the single or double quote route? Or is it better educationally to see a mix? Perhaps for a given exercise, stick with one style. (For example, 10.1 uses both styles.)

## Preparing Directories

- [ ] reword the first paragraph, since labs are now provided in a different way

## 10.1

### 10.1.1

- [ ] "simple array" => "simply an array of strings"? (unsure what "simple" means in this context)

### 10.1.2

- [ ] "sortedPaintingsByYear" => "paintingsSortedByYear" ?

### 10.1.3

- [ ] bug: doesn't handle equality
- [ ] suggest adding an even _more_ concise version: `return a.year - b.year;`

### 10.1.4

- [ ] formatting suggestions:
  - [ ] bring the `paintings.filter` down to the next line (like you do in 10.1.5)
  - [ ] remove the brackets from the condition

### 10.1.6

- [ ] because it's quite the gotcha, I'd add another forEach that illustrates that you cannot force an early exit from a forEach (that is, you can't use a `return` inside a forEach and have it behave the same way as a for/for-of)

### 10.1.7

- [ ] the impact of using `i` is lost a bit here, since both returned paintings use lowercase `with`s anyway. How about something like `ar`? (which grabs 'Artist', 'Earring', and 'Gardens')
- [ ] `regexEx` is perhaps not quite as descriptive as it could be (I had to think a moment on what 'Ex' stood for)...perhaps `regexResults`?

### 10.1.8

- [ ] perhaps leave out "or the ellipse"? First off, I think it's 'ellipsis' and second I'm not sure the word is necessary here anyway.
- [ ] perhaps put a comment that reminds the reader that `titles` was defined at the top of the file?
- [ ] "This has added the titles array..." => "This has added the **contents of** the titles array..."

### 10.1.10

- [ ] we come across the meaning of "simple" in "simple array" again

### 10.1.12

- [ ] "A more concise way..." => "An even more concise way..."

## TYK#1

### 1

- [ ] "...to each symbol object..." => "...to each stock object..."
- [ ] via a regular for or a for-of loop ?
- [ ] the "This" in "This will require..." is a bit unclear. Perhaps "Adding this new function will require a function expression."?

### 3

- [ ] why use $0? (Do negative stock prices exist?) If the goal is to use a compound conditional here, maybe choose a different lower bound?

### 4

- [ ] "Create a new array of strings contains `<li>` elements containing..." => "Create a new array of strings containing `<li>` elements displaying..."

### 5

This one is a bit out of place, as it doesn't follow the original instructions (of solving two different ways). Also it's a bit tricky, as `localeCompare` isn't mentioned anywhere in the labs or text. (I'm all for a bit of independent research, but a nudge would be useful here.)

This reminds me: there should be something in either the text or in a lab exercise that illustrates a big gotcha with `sort` when used with arrays of numbers: they're sorted as strings!

Maybe make 5 its own little exercise to address both issues?

## Prototypes, Classes, and Modules

- [ ] "Prototypes are more memory efficient..." => "Prototypes are a more memory efficient..."

## 10.2

### 10.2.1

- [ ] perhaps add a reference to what likely seems like a magic incantation to many readers? :)

### 10.2.3

- [ ] add a couple of sample lines, so that folks can get a feel for whether they've done things properly?

### 10.2.4

- [ ] (I still think "constructor function" is the way to go, but...)
- [ ] I think I'm getting too pedantic here...but shouldn't it be "...and the luminance function defined in Color's prototype"?

## 10.3

### 10.3.1

- [ ] I know that dropping articles is necessary sometimes, but for the love of God, please put the "the" back in "It contains code from previous exercise." :)
- [ ] "Add the following." => "Add the following to the end of the file."? (or change the comment in the starting file a bit..."add module code here" might be a bit confusing, as the const declaration has nothing to do with modules)

### 10.3.3

- "Notice that modules can only be ued within a module." sounds a bit infinite!

## TYK#2

### 1

- [ ] 1 doesn't have an action the reader needs to perform...perhaps combine 1 and 2?

### 2

- [ ] "...take two arguments: the gallery name and the gallery id" => "...the gallery id and the gallery name" (if the reader follows the given order, the results isn't going to be what they expect...though it does provide an interesting little debugging moment! :) )

### 5

- [ ] I wonder whether "retrieve the sample data" is going to be enough guidance. Should the reader be explicitly told to store the result in a variable?

## 10.4

### 10.4.1

- [ ] "Browser APIs are simply web pages..." => aren't browser APIs things like the Fetch API and the Canvas API? Should it be Third-party API?

### 10.4.2

- [ ] as much as I'm a fan of foo (and trust me - I'm a HUGE fan), I feel there are a lot of learners out there (esp from other countries?) who have NO clue what this foo thing is
- [ ] "...which is a way to handle..." => "...which is an object used to handle..."?
- [ ] you might actually want to use `console.log` here, since it'll decorate the displayed promise with `{<pending>}`, which is kinda educational?

### 10.4.3

- [ ] ah, bar...I love you almost as I love foo, but perhaps you do not belong here as well?
- [ ] might be a good place to call out the fact that the Promise is displayed first in the console? (I understand that the note on this one is getting long, though!)
  - [ ] ...but I now see that's done in 4, so forget this? Or use 4 to repeat it and hammer it home?
- [ ] "Notice that the fetch returns a request..." => have to be careful here...doesn't it return a Promise?

### 10.4.5

- [ ] "Modify the URL in the fetch..." => "Modify the URL used by the fetch..."

### 10.4.6

- [ ] "...the second promise still executes..." => Promises can't execute, can they?
- [ ] change the `console.log(err)` to `console.error(err)` to sync up with the other error examples later?

### 10.4.7

- [ ] OK this is weird, but I see absolutely no change with the suggested code added - the logs to console are exactly the same as they were before the change!

## 10.5

### 10.5.3

- [ ] might be useful to suggest where in the code...though it functions fine wherever you put it, I suppose....

### 10.5.6

- [ ] put the `let fetchedData;` back in the code

### 10.5.7

- [ ] "Remove the changes made in steps 5 and 6..." => "...made in step 6..." (since step 6 includes all the changes made in 5?)
- [ ] Should make it clear that the code should be added directly after the `fetch`
- [ ] in the name of all that is holy...please, no `alert`s! :)

## 10.6

"The next example provides an example." Um.... :)

### 10.6.2

- [ ] provide guidance where the code goes
- [ ] use "input" event for input...that's why it's there!
- [ ] should `innerHTML` use be encouraged? If there were handlers on the list elements, wouldn't there be a memory leak?

### 10.6.3

- [ ] replace `var` with let/const?

### 10.6.4

- [ ] provide guidance where the code goes
- [ ] "obj" => "universityName" ?
- [ ] define the regex outside of the filter call

## 10.7

- [ ] shouldn't everything after the import be wrapped in a DOMContentLoaded handler?

### 10.7.2

- [ ] provide guidance where the function should go

### 10.7.3

- [ ] "...you will event delegation" => "...you will use event delegation"

### 10.7.4

- [ ] double semicolon `new FormData();;`

### 10.7.5

- [ ] "Add the following after code..." => "Add the following after the code..."

### 10.7.6

- [ ] provide guidance for placement
- [ ] maybe have the server respond to one of the buttons with a failure?
- [ ] it is likely confusing whether the `received` property that is coming back is something that all responses have or whether it was constructed by the server handling the request...

## 10.8

Seems ok.

## TYK#3

- [ ] why the change in comment style? (from `//` to `/* */`?)
- [ ] what is the difference between the two comments "then handle button click" and "When button is clicked, fetch data...."?
- [ ] I suspect you want the TYKs to be a little less prescriptive, but I wonder whether 2 points is enough for this sucker. Each point is pretty dense with information. (Which may be the point?)

### 1

- [ ] Instead of "will do" and "will use", how about just "do" and "use"?
- [ ] It's not labelled as a "load" button, so there might be some confusion.
- [ ] manipulating the DOM via `innerHTML` is a bit fraught with peril, isn't it? You could do `select.replaceChildren()` perhaps?
- [ ] emptying the select is said to happen first ("first empty the `<select>` element..."), but the comments in the starting code don't mention this

- [ ] couldn't the `<main>` be hidden right off the bat, alosng with the two animations?
- [ ] be explicit that the text of the `<option>s` should be the country name?

### 2

- [ ] "...to the photo URL that contains..." => to the photo API URL that contains..."
- [ ] "...must have the name iso..." => "...must have the field name iso..."

## 10.9

### 10.9.2

- [ ] `lab10-ex09.js` doesn't exist in provided files!
- [ ] brace up the if/else in the timeout

### 10.9.3

- [ ] is `function simplePromise` gray because it's in the starting file?
- [ ] perhaps a different name for the function? The current name sounds like it's returning a simple promise...
- [ ] change to `console.error` for catch block?

### 10.9.5

- [ ] reader might not know what ML is....
- [ ] semicolon missing after `thumbURL` string

### 10.9.6

- [ ] semicolon after `return tagImageContent(url)`
- [ ] continue using template strings throughout to be consistent?
- [ ] `console.error` for the catch?
- [ ] "...create thumbnail and create thumbnail..." => "...tag image content and create thumbnail..."

### 10.9.7

- [ ] can't this be moved into 8?

### 10.9.9

- [ ] "To do so..." => "To simulate this..."?
- [ ] `console.error` for the catch?
- [ ] add a bit of commentary about `Promise.all`?
- [ ] I wonder if the "potentially **happen**" might make the user focus on the fact that fate could decide that both things happen at the same point in time, as opposed to focusing on the fact that "the order doesn't matter here - just that these jobs get done"?

## 10.10

### 10.10.2

- [ ] "...from existing function" => "...from the existing function"
- [ ] could also use `opt.value` instead of `setAttribute`

### 10.10.6

- [ ] can't we just keep `getCountryData()`?
  - `const countries = await getCountryData();`

### 10.10.8

- [ ] should the try/catch from 7 be included here?

## TYK#4

# 1

- [ ] "..of the four APIs..." => "...of the first four APIs..."? or do you want them to test all 5?

# 2

## 10.11

There is no `lab10-ex11.js`...but there is a `lab10-ex11-tester.js`!

Skipping this one, because it jumps immediately to the alert - is the tester file what students will start their work with?

## 10.12

### 10.12.1

- [ ] `e` not needed in click handler...

### 10.12.2

- [ ] maybe instead of commenting out, just delete it? It's going to be relocated to within the handler introduced in 3 and if it's not deleted, readers might think they have to modify the one they have here later? Of course, if you DO delete it, you'll probably want to have a little note explaining why they did step 1!

### 10.12.3

- [ ] using an arrow function for the listener doesn't work here...`this` is binding to `document`, not `window.speechSynthesis`

### 10.12.4

- [ ] is the `createTextNode` bit just a reminder of how to do things differently? (because `opt.textContent = blah` seems less confusing to my brain....)
- [ ] would `select.length == 1` be any more expressive?

### 10.12.5

- [ ] why the `e.preventDefault`?

## 10.13

### 10.13.1

- [ ] Currently, the instructions at the given link say that users shout restrict their keys...but the "Application Restriction" steps are such that a new user is prolly going to get bogged down if they try to follow along.

### 10.13.2

- [ ] "...inserted by Google's (API?)"

### 10.13.3

- [ ] mention explicitly that this has to go after the `<script src>` tag? And is there a reason why that tag isn't in the `<head>`?

### 10.13.4

- [ ] move this earlier? (to become the new step 3?)

### 10.13.5

- [ ] go back to `//` comment style used in almost every other example?
- [ ] show in the code example the "Creates map" comment so that users aren't confused over where to put the code shown here in step 5?
- [ ] Hey, look! A `var`!

### 10.13.12

- [ ] "to simplify no error handling..." => "to simplify, no error handling..."
- [ ] the createMarker call formatting is pretty wonky - that poor city.AsciiName....
- [ ] should the `console.log(error)` be in braces? Do you want to make it `console.error`?
