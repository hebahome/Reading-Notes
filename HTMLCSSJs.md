# How to Add an Anchor Link to Jump to a Specific Part of a Page


![How to code a link in HTML](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR04flpr_pBY3ImnISFVGwAsvfD7669F4Z3Jw&usqp=CAU)

## An anchor link is a link, which allows the users to flow through a website page. It helps to scroll and skim-read easily. A named anchor can be used to link to a different part of the same page (like quickly navigating) or to a specific section of another page.

### Creating an anchor link¶  

Let’s see how to jump to a marked section of the page by using the <a> tag. It’s quite simple!

Add an id attribute to the anchor element to give a name to the section of the page. The value of the attribute may be a word or a phrase (when using phrases remember not to have spaces, use dashes or underscores instead).


 ## Alternatively you can also have the following types of anchors:

- anchor within a header: <h2 id="anchor-name">Section name</h2>
- anchor within an image
- anchor within a paragraph: <p id="anchor-name">Paragraph name</p>


2. Create a hyperlink by using the id of the link target, preceded by #.

# How to style a jumping anchor link¶
It is also possible to give additional styling to the jumping anchor. For that, use a <style> tag in the <head> element and give styling to the section to be jumped by using color and background properties.

# Link to the anchor from another web page¶
You can link to your anchor link from other websites, as well. For that, add the URL followed by # and the anchor value. There are two types of such usage.



# hsla()

![Hsla](https://res.cloudinary.com/practicaldev/image/fetch/s--APW5p13I--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/5zkceofkmps0jdxfjmx8.png)



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

  # JPEG vs PNG vs GIF — which image format to use and when?


  
  ## There are hundreds of image formats available each with a specific use case. I bet most of us wouldn’t have come across 90% of the image formats listed on Wikipedia.


## In this post, we would only be looking at the three most commonly used image formats in websites and mobile applications — JPEG, PNG and GIF. Several statistics reports, including the one from HTTP Archive, indicate that these 3 formats together comprise of more than 95% of all images loaded on websites. However, these 3 image formats have significant differences amongst themselves thus making each of them suitable for specific use cases. Understanding these major differences would help us deliver the best possible images to our website and mobile app users.



  

# TL;DR
### Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.


## Compression


### Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.
### Compression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression. This is not the case in lossy compression i.e. data loss in lossy compression is irreversible. Lossy compression algorithms always have a superior compression ratio (the ratio of size of compressed image to original image) as compared to lossless compression. However, this compression ratio comes at a cost of reduced quality that becomes more evident after zooming in on the image. This noticeable reduction in quality or distortion of the image is called compression artefact.
### JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels (read Discrete Cosine Transform), JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.

