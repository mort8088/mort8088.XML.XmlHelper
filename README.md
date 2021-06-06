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

## Licensing
Copyright (C) 2021 by Dave 'mort8088' Henry

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.