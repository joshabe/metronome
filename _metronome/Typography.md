# Typography

> **Last Updated:**  
> 09/10/18 — Updated heading rules, no more scaling for breakpoints  
> 08/28/18 — Rewrote page in MD format

---

In 2016 we moved from ~~Helvetica~~ to the friendlier **Lato**.
/_img/latospecimen.png
Lato has rounded corners and angled terminals which give it a more friendly vibe. The i's and j's are dotted with perfectly round circles. Very friendly. Even if you don't notice it, you feel it.

## Type Scale
We use a typographic scale so that the sizes across our site fall into a consolidated list of relative intervals. This way we don't have a lot of different sizes that become difficult to maintain.

| Labels | Authenticated | Body | H4 | H3 | H2 | H1 |
|:----:|:-----:|:--:|:--:|:--:|:--:|:--:|
| 11px | 14px | 16px | 20px | 24px | 30px | 36px |

**Update as of 09/10/18**  
Typography no longer scales down on smaller breakpoints. 

## Line Height
The default **line-height is `1.5`** for all typography.

### Example
/_img/line-height_example.png

> __Pro Tip:__  
> To calculate the line-height for any given font size in Sketch, just type __"1.5 * x"__ in the line height box where __"x" = your font size__

## Headings
Headings follow the typographic scale, and **should be nested according to a parent/child relationship** where possible.   

All headings are bold, with a line height of 1.5 and 10px of bottom padding.
H1 and H2 are **`#650360`**  
H3 and H4 are **`#2a2a2a`**

### Example
/_img/heading_example.png

## Paragraphs
Paragraphs are **`#2a2a2a`**  
Paragraphs are **`16px` on medium and large breakpoints**, and scale down to **`14px` on the mobile breakpoint**  
Paragraphs have a line height of `1.5`  
For optimum readability, **the width of a paragraph should not exceed 8 columns**. [^for more information about column layouts, see the grid page.]

### Example
/_img/bodycopy_example.png

## Links
Links are **16px, bold, and `#006899`** and change to **`#0079b3`** on hover with a 150ms linear transition.  
Visited links are styled the same.  
Links have no underline


### Example

/_img/link_example.png

### Inline Link Example
/_img/inlinelink_example.png

**Links on dark backgrounds**    
Links on dark backgrounds should be the lighter color: `#C1E8FA` in order to meet accessibility requirements:
<div style="width:50%;float:left;padding-top:20px;">
/_img/linkondark.png
#### Do use lighter color link on a dark background
</div>
<div style="width:50%;float:left;padding-top:20px;">
/_img/linkondark_dont.png
#### Don't use a regular link on a dark background
</div>
<div style="clear:both"></div>

## Titles/Labels
Use as a label for tables, lists, and forms.  
A label should be `11px`, `bold`, and should use the `text-transform:uppercase` property.
If a label flows into more than one line, it should use the standard line height of **`1.5`**, which comes out to **`16.5px`** for an 11px font size.

/_img/titleheading_example.png


**Restrictions on length**
Labels should be **limited to 5 words or less**. 
/_img/sentencelabel_dont.png
> **Don't use when** you just need a font size smaller than 14px. If you need something smaller than 14px, submit this for review as an exception.

## Lists
There are various types of lists that can be used. Each one should have an indent of 20px. If 

### Example
/_img/list_example.png

**Lists with Titles**
When listing links in a navigation item, or some other list that needs a label, combine the list style with the label/title style.
/_img/listheading_example.png 

## Price and Rate Callouts

Hero banners and cards with price and rate callouts have their own unique style. There are 3 sizes to choose from, and they each have a corresponding size for their accompanying symbol:

|   | Large | Medium | Small |
|--:|:--:|:--:|:--:|
| **Number Size** | 80px | 60px | 40px | 
| **Symbol Size** | 52px | 39px | 26px | 

### Example

/_img/percentagecallout_example.png

**Other Symbol Types**  
All symbols follow the same size guidelines, though the positioning may be different.
/_img/dollarcallout_example.png

**Rate Callout Title**
Use the title/label style to label the Annual Percentage yield for rate callouts. 
The stacked 3 columns should be **centered vertically** and use a line-height of **`1.5`.** [^ See guidelines for titles/labels]
/_img/percentagelabel_example.png

Use a label above or below if necessary, but **limit to no more than 4 words**.[^See titles/labels for restrictions on length]


## A11y
**Color Contrast**  
Large text (text that is 20px Bold or 24px Regular and larger) needs to meet a 3:1 ratio  
Regular text (text that is under 20px Bold or 24px Regular) needs to meet a 4.5:1 ratio