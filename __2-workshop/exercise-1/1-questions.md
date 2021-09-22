# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ False ] `<div><span>hello</div></span>`
closed div before child span

b) [ False ]
no closed ul,
no opened ol

```html
<ul>
<li>one</li>
</ol>
```

c) [ True ] `<ul></ul><img/><ol><li>one</li></ol>`
ul renders nothing,
rest is closed and ordered properly

## Q2 - What is a screenreader and why should we care about them?

in the context of a website, a screenreader is a program that takes the semantic html & content, and outputs a description of it through text read out loud or via braille.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
webpage - HTML HEAD BODY, HEADER MAIN FOOTER
(something)s - UL / OL, LI
photo - IMG, FIGURE + FIGCAPTION ?

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
website - HTML HEAD BODY, HEADER MAIN FOOTER
list - UL / OL, LI
links - A
others depending on list content, such as P or IMG

c) You want to sell designer hats. You need to receive orders from the user.
website - HTML HEAD BODY, HEADER MAIN FOOTER
orders page - FORM INPUT LABEL, 
cart - UL / OL, LI, A, IMG FIGURE FIGCAPTION, BUTTON or FORM


## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
technically yes, you can. <button><button></button></button> does render.
semantically no, a button should have a single action connected to it.

## Q5 - What is the most generic tag you can use?
DIV

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` un ordered list

d) `li` list item

e) `tr` table row

f) `th` table header

g) `td` table data / cell

## Q7 - Usually, `td` elements are children of what kind of elements?
table row - <tr>{child}</tr>

## Q8 - What is the difference between td and th?
one is a header, a "title". - th
the other is the actual data, "cell". - td

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1. first header

## Q10 - In which situation can you use self closing tags?
using an element that contains no child element. or one of the self closing tag list.

## Q11 - What is autofilling and why is it important?
as in autocomplete? for better user experience. faster user flow. leads to more sales. 

## Q12 - Which attributes are always present in an img element?
src, alt

## Q13 - Which attribute is always present for an anchor tag?
href
