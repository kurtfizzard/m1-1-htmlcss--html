# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screen reader is a form of assistive technology that renders text and image content as speech or braille output. Screen readers are software applications that attempt to convey what people with normal eyesight see on a display to their users via non-visual means, like text-to-speech sound icons, or a Braille device.

Source: https://en.wikipedia.org/wiki/Screen_reader

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img></img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<a href="url"></a>

c) You want to sell designer hats. You need to receive orders from the user.

<form></form>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

Instinctively, I would say that this is not possible, because to implement either button, you would be implementing both simultaneously, which would eliminate the need for two buttons.

## Q5 - What is the most generic tag you can use?

<div></div>

## Q6 - What do the following achronyms stand for?

a) `a`

anchor

b) `ol`

ordered list

c) `ul`

unordered list

d) `li`

list item

e) `tr`

table row

f) `th`

table header

g) `td`

table data

## Q7 - Usually, `td` elements are children of what kind of elements?

Tables.

## Q8 - What is the difference between td and th?

TH is used for table header cells while TD is used for table data cells. This distinction gives user agents a means to render such cells distinctly, for instance by using a larger or heavier font for header cells. It is also needed when rendering to speech.

Source: https://www.w3.org/MarkUp/html3/tablecells.html

## Q9 - Which tag makes the text appear bigger: h1 or h3?

There are 6 gradings or levels of HTML headings: <h1> to <h6>. Graphically, these create decreasingly large text, with h1 being the biggest, and h6 being the smallest of the group.

Source: https://www.yourhtmlsource.com/text/headingfontsize.html

## Q10 - In which situation can you use self closing tags?

In modern HTML, using self-closing tags are not allowed.

Source: https://clearlydecoded.com/anatomy-of-html-tag#:~:text=The%20Self%2DClosing%20Tag&text=It's%20used%20to%20communicate%20lack,closing%20tags%20are%20not%20allowed.

## Q11 - What is autofilling and why is it important?

The autocomplete attribute allows the browser to do a pattern match against a list of values locally stored with the browser, and supplies the appropriate corresponding value when the input is programmatically tagged. This is a User setting that can be turned on or off, or modified by the end user. This reduces typing and reliance on memory because it uses stored values to fill in the fields.

Source: https://www.w3.org/WAI/WCAG21/Techniques/html/H98#:~:text=The%20autocomplete%20attribute%20allows%20the,modified%20by%20the%20end%20user.

## Q12 - Which attributes are always present in an img element?

The <img> tag has two required attributes: src - Specifies the path to the image. alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.

Source: https://www.w3schools.com/tags/tag_img.asp#:~:text=The%20tag%20has%20two,some%20reason%20cannot%20be%20displayed

## Q13 - Which attribute is always present for an anchor tag?

An anchor is a piece of text which marks the beginning and/or the end of a hypertext link. The text between the opening tag and the closing tag is either the start or destination (or both) of a link. 

Source: https://www.w3.org/MarkUp/1995-archive/Elements/A.html#:~:text=The%20text%20between%20the%20opening,anchor%20tag%20are%20as%20follows.&text=OPTIONAL.,the%20start%20of%20a%20link.
