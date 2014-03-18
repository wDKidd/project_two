Layout rules divide the page into sections. Layouts hold one or more modules together.
This includes all types of layout containers such as header, footer, content, sidebar, etc.  
The layout elements don't really have any styles of their own, but are simply containers.  
Obviously, this is the layer where grid systems would be living.  
All selectors in this category should be prefixed with .layout- (e.g. .layout-header, .layout-sidebar).

##########################################################################################################

Layout Rules

CSS, by its very nature, is used to lay elements out on the page. However, there is a distinction between layouts dictating the major and minor components of a page. The minor components—such as a callout, or login form, or a navigation item—sit within the scope of major components such as a header or footer. I refer to the minor components as Modules and will dive into those in the next section. The major components are referred to as Layout styles.

Layout styles can also be divided into major and minor styles based on reuse. Major layout styles such as header and footer are traditionally styled using ID selectors but take the time to think about the elements that are common across all components of the page and use class selectors where appropriate.

Some sites may have a need for a more generalized layout framework (for example, 960.gs). These minor Layout styles will use class names instead of IDs so that the styles can be used multiple times on the page.

Generally, a Layout style only has a single selector: a single ID or class name. However, there are times when a Layout needs to respond to different factors. For example, you may have different layouts based on user preference. This layout preference would still be declared as a Layout style and used in combination with other Layout styles.

