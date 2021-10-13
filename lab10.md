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

- [ ] "...take two arguments: the gallery name and the gallery id" => "...the gallery id and the gallery name"  (if the reader follows the given order, the results isn't going to be what they expect...though it does provide an interesting little debugging moment! :) )

### 5

- [ ] I wonder whether "retrieve the sample data" is going to be enough guidance. Should the reader be explicitly told to store the result in a variable?