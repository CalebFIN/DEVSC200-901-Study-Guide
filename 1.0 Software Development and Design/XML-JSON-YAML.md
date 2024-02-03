## _XML-JSON-YAML OVERVIEW_




Data within these formats
  - Structured for Code
  - Annotated For Humans
  - Open Source
  - Platform Agnostic
  - Describes its own data 

SEE: [**Parsing XML-JSON-YAML**](<Parsing XML, JSON, and YAML Python.md>)

| Feature                | YAML                                  | JSON                                      | XML                                           |
|------------------------|---------------------------------------|-------------------------------------------|-----------------------------------------------|
| **Human Readability**  | Very readable                         | Readable                                  | Less readable due to verbose syntax           |
| **Data Formats**       | Supports strings, numbers, lists, and associative arrays | Supports objects, arrays, strings, numbers, booleans, and null | Supports a wide range of data types through schemas |
| **Comments**           | Supports comments                     | Does not support comments                  | Supports comments                             |
| **Hierarchy**          | Indentation                           | Braces and brackets                        | Tags and attributes                           |
| **File Extension**     | `.yaml` or `.yml`                     | `.json`                                    | `.xml`                                        |
| **Support for Metadata** | Limited support through tags         | No direct support                          | Extensive support through attributes and namespaces |
| **Parsing**            | Generally requires external libraries (though widely available) | Native support in most programming languages | Requires external libraries (though widely available) |
| **APIs and Config Files** | Commonly used in configuration files and less often in APIs | Widely used in web APIs                     | Used in legacy systems, SOAP APIs, and configurations where metadata is important |
| **Error Tolerance**    | More tolerant due to its readability and flexibility | Less tolerant to errors; strict syntax    | Less tolerant; strict syntax but can be more complex to parse correctly |
| **Use Cases**          | Configuration files, simpler data serialization | Web APIs, data interchange between server and web applications | Complex data structures, document markup, legacy systems |


  
### _[XML](XML.md)_

  - Legacy Support
  - SOAP USES XML
  - Strongly Verbose

XML (eXtensible Markup Language) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable.

### _[JSON](JSON.md)_
_JAVASCRIPT_ _OBJECT_ _NOTATION_
 - Popular
 - Light Wieght
 - Native To Javascript


### _[YAML](YAML.md)_
  - Highly Ledgible
  - Compact / Smaller Data transfer
  - IDEAL For Configuration


