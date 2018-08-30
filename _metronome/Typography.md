# Typography

### Changelog

| Last Updated  | Description |
| --- | :------ |
| 08/28/18 | Rewrote page in MD format |

---

In 2016 we moved from ~~Helvetica~~ to the friendlier **Lato**.
/_img/latospecimen.png
Lato has rounded corners and angled terminals which give it a more friendly look. The i's and j's are dotted with perfectly round circles. Very friendly. Even if you don't notice it, you feel it.

## Type Scale
We use a typographic scale so that the number of font sizes across the site feels consistent.

| Labels | Authenticated | Body | H4 | H3 | H2 | H1 |
|:----:|:-----:|:--:|:--:|:--:|:--:|:--:|
| 11px | 14px | 16px | 20px | 24px | 30px | 36px |

On the small breakpoint, each style scales down one size where possible. 

| Labels | Authenticated | Body | H4 | H3 | H2 | H1 |
|:----:|:-----:|:--:|:--:|:--:|:--:|:--:|
| 11px | 14px | 14px | 16px | 20px | 24px | 30px |

## Line Height
The default **line-height is `1.5`** for all typography.

### Example
/_img/line-height_example.png

> __Pro Tip:__
> To calculate the line-height for any given font size in Sketch, just type __"1.5 * x"__ in the line height box where __"x" = your font size__

## Headings
Headings are **`#2a2a2a`** and **`bold`**  
Headings follow the typographic scale, and **should be nested according to a parent/child relationship** if possible.   
Headings have a line height of `1.5`  
Headings have **`10px` of bottom padding**

### Example
/_img/heading_example.png

## Paragraphs
Paragraphs are **`#2a2a2a`**  
Paragraphs are **`16px` on medium and large breakpoints**, and scale down to **`14px` on the mobile breakpoint**  
Paragraphs have a line height of `1.5`  
For optimum readability, **the width of a paragraph should not exceed 8 columns**. [^for more information about column layouts, see the grid page.]

### Example
/_img/body_example.png

## Links
Links are **16px, bold, and `#006899`** and change to `#0079b3` on hover with a 150ms linear transition.  
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


## A11Y
**Color Contrast**  
Large text (text that is 20px Bold or 24px Regular and larger) needs to meet a 3:1 ratio  
Regular text (text that is under 20px Bold or 24px Regular) needs to meet a 4.5:1 ratio