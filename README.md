# XmlHelper

## mort8088.XML.XmlHelper

A static class containing methods to complete a number of common tasks while working with XmlDocuments. **Updated to be used with .NET Core**

---

### XmlDocument NewDoc()

Creates an empty XmlDocument object with an Xml Declaration assigned as version 1.0 encoding UTF-8

Returns: Empty XmlDocument object

---

### XmlElement AddRootNode(System.Xml.XmlDocument, System.String)

Create a root node on a given document

|Name | Description |
|-----|------|
|addTo: |Xml document to add the new root node to|
|nodeName: |Name of the new root node|
Returns: A reference to the newly created root node

---

### XmlAttribute AddAttrib(System.Xml.XmlElement, System.String, System.String)

Adds the Named attribute with a given value to an existing Node

|Name | Description |
|-----|------|
|addTo: |Node to add the new attribute|
|attribName: |New attribute name|
|attribValue: |Value to set|
Returns: A reference to the newly created attribute

---

### XmlAttribute AddAttrib(System.Xml.XmlElement, System.String, System.Boolean)

Adds the Named attribute with a given value to an existing Node

|Name | Description |
|-----|------|
|addTo: |Node to add the new attribute|
|attribName: |New attribute name|
|attribValue: |Value to set|
Returns: A reference to the newly created attribute

---

### XmlAttribute AddAttrib(System.Xml.XmlElement, System.String, System.Int32)

Adds the Named attribute with a given value to an existing Node

|Name | Description |
|-----|------|
|addTo: |Node to add the new attribute|
|attribName: |New attribute name|
|attribValue: |Value to set|
Returns: A reference to the newly created attribute

---

### XmlAttribute AddAttrib(System.Xml.XmlElement, System.String, System.Single)

Adds the Named attribute with a given value to an existing Node

|Name | Description |
|-----|------|
|addTo: |Node to add the new attribute|
|attribName: |New attribute name|
|attribValue: |Value to set|
Returns: A reference to the newly created attribute

---

### XmlElement AddNode(System.Xml.XmlElement, System.String)

Create a new node on a given node

|Name | Description |
|-----|------|
|addTo: |Node to add the new node to|
|nodeName: |Name of the new node|
Returns: A reference to the newly created node

---

### void AddComment(System.Xml.XmlElement, System.String)

Create a new comment node in a given node

|Name | Description |
|-----|------|
|addTo: |Node to add the comment to|
|comment: |String to go in the Comment section|
Returns: nothing

---

### XmlElement AddTextNode(System.Xml.XmlElement, System.String, System.String)

Create a new text node on a given node with a given value

|Name | Description |
|-----|------|
|addTo: |Node to add the new node to|
|nodeName: |Name of the new node|
|nodeValue: |Text value to set the new node to|
Returns: A reference to the newly created node

---

### string PrettyPrint(System.String)

Attractively format the XML with consistent indentation.

|Name | Description |
|-----|------|
|strXml: |A well formed XML string|
Returns: An XML string with carriage returns and indentations

---

### string PrettyPrint(System.Xml.XmlDocument)

Attractively format the XML with consistent indentation.

|Name | Description |
|-----|------|
|doc: |The Xml Document you want to convert|
Returns: An XML string with carriage returns and indentations

---

### string ReadAttrib(System.Xml.XmlElement, System.String)

Read a value from a given attribute on an existing node

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|attribName: |Name of the Attribute|
Returns: value of the attribute or NULL if not found

---

### Boolean ReadAttrib(System.Xml.XmlElement, System.String, System.Boolean)

Read a bool value from a given attribute on an existing node

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|attribName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### Int32 ReadAttrib(System.Xml.XmlElement, System.String, System.Int32)

Read a int value from a given attribute on an existing node

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|attribName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### Single ReadAttrib(System.Xml.XmlElement, System.String, System.Single)

Read a float value from a given attribute on an existing node

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|attribName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### String ReadAttrib(System.Xml.XmlElement, System.String, System.String)

Read a string value from a given attribute on an existing node

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|attribName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### String ReadTextNode(System.Xml.XmlElement, System.String)

Read a text node from an existing node

|Name | Description |
|-----|------|
|readFrom: |Node with the node to read|
|nodeName: |Name of the node to read the value|
Returns: inner text of the node or null if not found.

---

### Boolean ReadTextNode(System.Xml.XmlElement, System.String, System.Boolean)

Read a Boolean value text node from an existing node returns a default value if not found

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|nodeName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### Int32 ReadTextNode(System.Xml.XmlElement, System.String, System.Int32)

Read an integer text node from an existing node returns a default value if not found

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|nodeName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### Single ReadTextNode(System.Xml.XmlElement, System.String, System.Single)

Read a float text node from an existing node returns a default value if not found

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|nodeName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---

### String ReadTextNode(System.Xml.XmlElement, System.String, System.String)

Read a text node from an existing node returns a default value if not found

|Name | Description |
|-----|------|
|readFrom: |node that has the attribute|
|nodeName: |Name of the Attribute|
|defaultValue: |The default value to return if the attribute is not found|
Returns: value of the attribute or value of defaultValue if not found

---
