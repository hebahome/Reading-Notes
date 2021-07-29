# How to Add an Anchor Link to Jump to a Specific Part of a Page


![How to code a link in HTML](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR04flpr_pBY3ImnISFVGwAsvfD7669F4Z3Jw&usqp=CAU)

## An anchor link is a link, which allows the users to flow through a website page. It helps to scroll and skim-read easily. A named anchor can be used to link to a different part of the same page (like quickly navigating) or to a specific section of another page.

### Creating an anchor link¶  

Let’s see how to jump to a marked section of the page by using the <a> tag. It’s quite simple!

Add an id attribute to the anchor element to give a name to the section of the page. The value of the attribute may be a word or a phrase (when using phrases remember not to have spaces, use dashes or underscores instead).


 ## Alternatively you can also have the following types of anchors:

- anchor within a header: <h2 id="anchor-name">Section name</h2>
- anchor within an image: <img id="anchor-name" src="/images/imgname.jpeg"/>
- anchor within a paragraph: <p id="anchor-name">Paragraph name</p>


2. Create a hyperlink by using the id of the link target, preceded by #.

# How to style a jumping anchor link¶
It is also possible to give additional styling to the jumping anchor. For that, use a <style> tag in the <head> element and give styling to the section to be jumped by using color and background properties.

# Link to the anchor from another web page¶
You can link to your anchor link from other websites, as well. For that, add the URL followed by # and the anchor value. There are two types of such usage.



# hsla()

![https://res.cloudinary.com/practicaldev/image/fetch/s--APW5p13I--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/5zkceofkmps0jdxfjmx8.png](hsl() and hsla() in css)
The hsla() functional notation expresses a given color according to its hue, saturation, and lightness components. An optional alpha component represents the color's transparency.



## Syntax
hsla(100, 100%, 50%, 1) /* #5f0 */
hsla(235, 100%, 50%, .5) /* #0015ff with 50% opacity */
hsla(235 100% 50% 1); /* CSS Colors 4 space-separated values */
Copy to Clipboard
## Values
Functional notation: hsl[a](H, S, L[, A])
H (hue) is an <angle> of the color circle given in degs, rads, grads, or turns in CSS Color Module Level 4. When written as a unitless <number>, it is interpreted as degrees, as specified in CSS Color Module Level 3. By definition, red=0deg=360deg, with the other colors spread around the circle, so green=120deg, blue=240deg, etc. As an <angle>, it implicitly wraps around such that -120deg=240deg, 480deg=120deg, -1turn=1turn, etc.

- S (saturation) and L (lightness) are percentages. 100% saturation is completely saturated, while 0% is completely unsaturated (gray). 100% lightness is white, 0% lightness is black, and 50% lightness is “normal.”

  - A (alpha) can be a <number> between 0 and 1, or a <percentage>, where the number 1 corresponds to 100% (full opacity).

