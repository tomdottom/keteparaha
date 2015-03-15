0.0.10 2015-03-13
-----------------

Bugfix - All components in a list of components had the text of the first
component...

0.0.9 2015-03-12
----------------

Added
=====

- Adds a hover method so that we can trigger dropdowns and the like
- Add a clear method that takes a selector
- Components refresh their element before returning their text
- Adds a has_text method to all pages and components. Remove the assertions
  from the page/component class. These should live in the test case

0.0.8 2015-03-11
----------------

Added
=====

- Subclasses of component can be passed as the value of the open argument to
a page or components click method.


0.0.7 2015-03-11 
----------------

Added
=====

- Breaking change of the of api to use new automatic page and component
  discovery
- CNAME file so that the project can be found at keteparaha.aychedee.com
- Action methods of Page and Component automatically return the appropriate 
  page or component. Pages and Components are registered using a metaclass 
  mechanism similar to Django's ORM. 

