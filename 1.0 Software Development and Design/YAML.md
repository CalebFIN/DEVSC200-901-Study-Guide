# __YAML__
``` YAML Ain't Markup Language ```
Indentation Specific
YAML, which stands for "YAML Ain't Markup Language" (a recursive acronym), is a human-readable data serialization standard that can be used for all programming languages. It is particularly popular in configuration files and applications where data is being stored or transmitted.

### Key Features
* Human Readable: Designed to be easily read and written by humans.
* Indentation-Based: Uses spaces for indentation to represent hierarchy, similar to Python.
* Data Types: Supports scalar types (strings, integers, floats), sequences (arrays/lists), and mappings (hashes/dictionaries).
* Cross-Language: Portable between programming languages.
* Comments: Allows comments using the # symbol.
* Basic Syntax

#### Important info
* Indentation: Use spaces (typically 2 or 4) for indentation. Tabs are not allowed.

* Consistency: Be consistent with the indentation level to avoid errors.

* Quoting: Strings in YAML do not require quotes. ( Example: "1234" is a string of digits.)

Scalars: Plain text or numbers.

```yaml
Copy code
key: value
number: 123
```

Sequences: Lists of items prefixed by dashes.

```yaml
items:
  - item1
  - item2
```
Mappings: Key-value pairs (dictionaries or objects).
```yaml
person:
  name: John Doe
  age: 30
```
Nested Structures: Combine sequences and mappings.
```yaml

employees:
  - name: John Doe
    role: Developer
  - name: Jane Doe
    role: Manager
```

