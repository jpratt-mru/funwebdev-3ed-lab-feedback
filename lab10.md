# Lab 10 Feedback

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