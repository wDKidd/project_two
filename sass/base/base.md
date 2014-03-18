Base rules are the defaults. 
They are almost exclusively single element selectors but it could include 
attribute selectors, pseudo-class selectors, child selectors or sibling selectors. 
Essentially, a base style says that wherever this element is on the page, it should look like this.

###################################################################################################

Base Rules

A Base rule is applied to an element using an element selector, a descendent selector, or a child selector, along with any pseudo-classes. It doesn’t include any class or ID selectors. It is defining the default styling for how that element should look in all occurrences on the page.

Base styles include setting heading sizes, default link styles, default font styles, and body backgrounds. There should be no need to use !important in a Base style.

I highly recommended that you specify a body background. Some users may define their own background as something other than white. If you work off the expectation that the background will be white, your design may look broken. Worse, your font colour choice may clash with the user’s setting and make your site unusable.

CSS Resets
A CSS Reset is a set of Base styles designed to strip out—or reset—the default margin, padding, and other properties. Its purpose is to define a consistent foundation across browsers to build the site on.

Many reset frameworks can be overly aggressive and can introduce more problems than they solve. Removing margin and padding from elements only to introduce them again creates duplicated effort and increases the amount of code needed to be sent to the client.

Many find resetting styles a helpful tool in site development. Just be sure to understand the drawbacks of the framework you wish to use and plan accordingly.

Developing your own set of default styles that you consistently use from project to project can also be advantageous.