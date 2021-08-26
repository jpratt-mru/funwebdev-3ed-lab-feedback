# funwebdev-3ed-lab-feedback

## Lab 8

### 8.2

#### step 1

- [ ] editor names should likely be capitalized
- [ ] visual code => VS Code (or Visual Studio Code)
- [ ] brackets is no longer supported by Adobe as of Sept. 1, 2021 (their site now suggests using VS Code!)

### 8.3

#### step 2

- [ ] The "since the file does not exist" doesn't make sense, since it was created in step 1

### 8.6

#### step 2

- [ ] closing bracket missing "...and then view the JavaScript console)."

#### step 3

- [ ] remove comma after "...since const, variable can't be changed"

#### step 4

- [ ] last sentence: "...which, **as** this example illustrates...."

#### step 6

- [ ] would personally have added an additional entry for isNull (the "object" result is...interesting)

#### step 10

- [ ] NaN (not Nan)
- [ ] might be useful to mention what happens if Cancel is pressed at the prompt...

### TYK 1

#### step 3

- [ ] The "simply multiply the user input by 0.1" and "use a const" seem at odds with each other....

#### step 4

- [ ] Perhaps some mention of formatting decimal places should be made here? (If they use certain inputs to test - like 12 - they're likely going to be surprised/distracted by the result.....

### 8.7

#### step 2

- [ ] the formatting of the msg string is a bit wonky (notice the + before "million" and the "million" line itself).

#### step 4

- [ ] move the note about the word wrapping to the "Add the following and test" portion instead?
- [ ] was the use of **var** intentional?

### 8.8

- [ ] maybe call this "Using the Console and Native **Objects**"? (the "Natives" is both a bit vague...and could be misconstrued)

### TYK #2

- [ ] the given solution has two potential issues
  - [ ] it doesn't allow for $0 bills (which is reasonable...but should probably be mentioned in the question), and
  - [ ] it involves a logical operator, which hasn't been mentioned in previous exercises


### TYK #3

#### step 4

- [ ] "loop through this array" doesn't make sense, because the "this" seems to refer to the tips array...which is empty!

#### step 5

- [ ] (each) tip by multiplying (each) individual billAmount element ....

#### step 7

- [ ] ...each bill total and (associated) tip amount
- [ ] ...will iterate (through?) the billTotals array, but....

### 8.12

Would it make sense to put the dynamic properties bit _after_ the object literal form?

### 8.13

I must admit, I've always found this one a bit odd: by putting JS code in a json file, you're both sending a mixed signal (this file with a json extension actually holds JS!) and confusing/annoying any linters that you have installed. :)

### TYK #4

#### step 1

- [ ] the link is busted ... Reader is only linking a URL that stops at /JavaScript, not /Javascript/Reference/Global_Objects/Array

#### step 3

- [ ] bullet 1: isn't csv.split(",") called?
- [ ] bullet 2: (comma)-delimited string? semicolon-delimited? is the original countries variable being altered, or is a new variable being created? (the solution shows the latter, but the wording here.....)
- [ ] bullet 3: what's being asked here doesn't match up with the solution

#### step 4

- [ ] bullet 3: task is already complete in starting file!
- [ ] bullet 5: rbb (not rgp)

#### step 5

- [ ] ...to use (the) document.write() function.... (I know some articles can be left out, but this one sounds....)
- [ ] bullet2: luminosity => luminance

### 8.16

#### step 4

- [ ] is the outer let actually in global scope? To muddy the waters, it does not show up as such in the DevTools debugger - it shows up at the "script" level...but is that just a DevTools creation? Dunno!

### TYK #5

#### step 3

- [ ] It's not clear that the tip array from TYK #3 should be recreated here.  Perhaps "...so that the loop that populates the array of tips now does so using the function"?

### 8.17

#### step 3

- [ ] "...ever used by the calculateFunction()..." => calculateTax()

### 8.18

Missing a period: "...objects can also have behaviors (functions)."

### 8.19

- [ ] The exercise is labelled 10.19 instead of 8.19
- [ ] The starting file should have "param f5" instead of "param f4" on line 26


#### step 2

- [ ] "data from f1" = "data from f1a"

#### step 4

- [ ] you can only leave out the () if it's a *single* parameter

### 8.20

Should this be title "Constructor Function" instead? Function constructors are a [different beast](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/Function) aren't they?


### TYK #6

- [ ] Numbering is off: there are 2 step 3's!
- [ ] It is a *bit* odd that the numbers for Apple in the starting doc differ from the ones you *should* be getting when your work is done correctly (and that are shown in Figure 8.9.

#### step 2

- [ ] this does that "is it JSON...or JS" thing (see 8.13)
- [ ] is the conversion supposed to be done in the json file? or in the test06.js?

#### step 3 (the first one)

- [ ] would be helpful if it was explicitly stated that the constructor should take in a company
- [ ] day50 and day200 moving average methods are not mentioned (and it's not mentioned that these are the same thing as Share Price in the output)

#### step 3 (the second one)

- [ ] "You can (call) it...."
- [ ] Maybe say "You should alter your methods from step 3 so that they call currency()"?

#### step 4

- [ ] since "output" can be a bit vague, it might be best say "output, using document.write,..."?

#### step 5

- [ ] maybe say "...output a single tag from the tag array in the company data..."? (to differentiate from *HTML* tag)
