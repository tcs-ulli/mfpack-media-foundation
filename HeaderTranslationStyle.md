# The Header Translation Style #

The translated headers are as close to the original headers, unless there is no possible way to insert or to alter.
These translations differ from the earlier translation styles in a way that Delphi pointers and types, as well C++ Builder compiler directives are no longer supported.

Translated headers have the following structure:

  * **Header**: Contains information about origin, project, copyrights, license etc.
  * **Unit**: Name of the unit. The unitname is capitalized but has the same name as the original header (.h) file.
  * **Interface**
  * **Uses clause**
  * **Blocks(s) of pre-defined constants, types etc.**
  * **Type block with forwarded interface declarations** followed by the Interfaces themselves.
  * **Additional blocks**: Here all helpers and Delphi/Free Pascal specific additions are placed (in between the comment blocks "//Additional Prototypes for all interfaces" and "//End of Additional Prototypes". So, here the translations might differ from the official Microsoft implementations.
  * **implementation**: All functions, classes etc. defined (if needed) in earlier blocks.

NOTE: This page is under construction.