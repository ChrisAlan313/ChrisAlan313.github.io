# Markdown Syntax Guide

A quick reference showcasing all major Markdown syntax elements.

---

## Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6


## Emphasis


*Italic* or _Italic_

**Bold** or __Bold__

***Bold and Italic*** or ___Bold and Italic___


## Blockquotes


> This is a blockquote.
>> Nested blockquote.


## Lists

### Unordered


- Item A
  - Subitem A1
- Item B
* Item C


### Ordered


1. First
2. Second
   1. Subsecond
3. Third


### Task Lists


- [x] Completed task
- [ ] Incomplete task


## Code

### Inline


Here is `inline code`.


### Block

```js
function nestedLoop() {
  for (let i = 0; i < 10; i++) {
    for (let j = 0; j < 10; j++) {
      console.log(i, j);
    }
  }
}
```

```html
<div>
  <h1>Hello, world!</h1>
</div>
```

```css
.container {
  width: 100%;
  height: 100%;
}
```

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```

## Horizontal Rule


---


## Links


[Text](https://example.com)

[Text with Title](https://example.com "Title")

<https://example.com>


## Images


![Alt text](https://via.placeholder.com/150)

![Alt with Title](https://via.placeholder.com/150 "Title text")


## Tables


| Name  | Age | Role       |
|-------|-----|------------|
| Alice |  30 | Developer  |
| Bob   |  25 | Designer   |


## HTML in Markdown


<div style="color: red;">Red text using HTML</div>


## Escaping Characters


\*Not italic\*


## Footnotes


This is a statement with a footnote.[^1]

[^1]: This is the footnote text.


## Definition Lists (Not widely supported)


Term 1
: Definition 1
