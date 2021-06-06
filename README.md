# mort8088.XML.XmlHelper

The XmlHelper is a static class containing methods to complete a number of common tasks while working with XmlDocuments.

**Updated to be used with .NET Core**

## Methods

* NewDoc  
  Creates an empty XmlDocument object with an Xml Declaration assigned as version 1.0 encoding UTF-8
* AddRootNode  
  Create a root node on a given document
* AddAttrib  
  Adds the Named attribute with a given value to an existing Node, returns a link to the new attribute created.
* AddNode  
  Create a new node on a given node, returns a reference to the newly created node.
* AddComment  
  Create a new comment node in a given node
* AddTextNode  
  Create a new text node on a given node with a given value, returns a reference to the newly created node.
* PrettyPrint  
  Attractively format the XML with consistent indentation, returns an XML string with carriage returns and indentations.
* ReadAttrib  
  Read a value from a given attribute on an existing node, returns value of the attribute or NULL if not found.
* ReadTextNode  
  Read a value from a given text node on an existing node, returns inner text of the node.