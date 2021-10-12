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