
### [Table of Contents](https://wondwosentsige.github.io/code-301-reading-notes/Home)

## Read 01

### Responsive web design & Floats

- With the growth in mobile Internet usage comes the question of how to build websites suitable for all users. The industry response to this question has become __responsive web design__, also known as RWD.

- Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.

#### Responsive vs. Adaptive vs. Mobile

- Responsive and adaptive web design are closely related, and often transposed as one in the same. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. 

- Mobile, on the other hand, generally means to build a separate website commonly on a new domain solely for mobile users

- Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. *This solution has the benefits of being all three, __responsive, adaptive, and mobile.__*

#### Flexible Layouts

- *Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.*

- __Flexible layouts,__ is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

- Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Reason being, the viewport height and width continually change from device to device.

- The formula to help identify the proportions of a flexible layout using relative values is based around taking the target width of an element and dividing it by the width of it’s parent element. The result is the relative width of the target element. i.e. __target/context = result__

#### Media Queries

- Media queries were built as an extension to media types commonly found when targeting and including styles. *Media queries provide the ability to specify different styles for individual browser and device circumstances*, the width of the viewport or device orientation for example.

- __Initializing Media Queries__

- There are a couple different ways to use media queries, using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document.

- Generally speaking it is recommend to use the @media rule inside of an existing style sheet to avoid any additional HTTP requests.

- Logical operators in media queries help build powerful expressions. *There are three different logical operators available for use within media queries, including and, not, and only.*

- Within responsive design the most commonly used features include min-width and max-width. These help build responsive websites on desktops and mobile devices equally, avoiding any confusion with device features. Example:- __@media all and (min-width: 320px) and (max-width: 780px) {...}__

- The __min and max prefixes__ can be used on quite a few media features. The min prefix indicates a values of greater than or equal to while the max prefix indicates a value of less than or equal to.

- The __orientation media feature__ determines if a device is in the landscape or portrait orientation.

- __Mobile First__:- One popular technique with using media queries is called mobile first. The mobile first approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

- The operating belief behind mobile first design is that a user on a mobile device, commonly using a smaller viewport, shouldn’t have to load the styles for a desktop computer only to have them over written with mobile styles later. Doing so is a waste of bandwidth. Bandwidth that is precious to any users looking for a snappy website.

- __Viewport Height & Width__:- *Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively*. Each value accepts either a positive integer or keyword. For the height property the keyword device-height value is accepted, and for the width property the keyword device-width is accepted. Using these keywords will inherit the device’s default height and width value.

- For the best results, and the best looking website, it is recommend that you use the device defaults by applying the device-height and device-width values like 
*meta name="viewport" content="width=device-width">*



#### Float

- There are four valid values for the float property. *Left and Right float* elements those directions respectively. *None* (the default) ensures the element will not float and *Inherit* which will assume the float value from that elements parent element.

- Aside from the simple example of wrapping text around images, floats can be used to create entire web layouts.

- Float’s sister property is __clear__. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.

- *Techniques for Clearing Floats*:- If you are in a situation where you always know what the succeeding element is going to be, you can apply the __clear: both;__ value to that element and go about your business. This is ideal as it requires no fancy hacks and no additional elements making it perfectly semantic.

- __The Empty Div Method__ is, quite literally, an empty div. <\div style="clear: both;"></\div>. Sometimes you’ll see a <\br> element or some other random element used, but div is the most common because it has no browser default styling, doesn’t have any special function, and is unlikely to be generically styled with CSS.

- __The Overflow Method__ relies on setting the overflow CSS property on a parent element. If this property is set to auto or hidden on the parent element, the parent will expand to contain the floats, effectively clearing it for succeeding elements.

- __The Easy Clearing Method__ uses a clever CSS pseudo selector *(:after)* to clear floats. Rather than setting the overflow on the parent, you apply an additional class like “clearfix” to it.
















[>> NEXT (Read-02)](https://wondwosentsige.github.io/code-301-reading-notes/class-02)


