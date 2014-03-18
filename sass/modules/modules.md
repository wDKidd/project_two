Modules are the reusable, modular parts of our design. 
They are the callouts, the sidebar sections, the product lists and so on.

The bulk of (SMA)CSS is made up of independent modules and submodules.  
Examples for modules could be things like: search-box, dialog, navigation, menu, content-box.  
While submodules are more specific versions of these modules such as:  
dialog-wide, navigation-tabbed, menu-dropdown. 

The ideal module is completely independent of its context and 
should work within any layout container or other module.  If a specific context requires
changes to a module you rather create a submodule that describes the context, 
instead changing styles based on the parent (e.g. .content-box-narrow instead of #sidebar .content-box).