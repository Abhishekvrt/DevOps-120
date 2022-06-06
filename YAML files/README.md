## YAML - YAML ain't a mark-up Language
YAML Ain't Markup Language (YAML) is a serialization language that has steadily increased in popularity over the last few years. It's often used as a format for configuration files, but its object serialization abilities make it a viable replacement for languages like JSON.

** Yaml specializations
- data format is used for exchange data
- Similar like Json and XML file
- In Yaml you can store only data and Not any commands, and this process called Serialization.

Note - Objects are nothing but a collection pf data

Objects ------> file (called Serialization)
Files --------> Objects {called de-serialization} 

YAML is a kind of data Serialization
Yaml, Json and XML all three are kind of same data Serialization languages

when a Obj Serialized, it deconstruct into three parts
1. YAML file
2. Database
3. Memory

## Benefits
1. very simple code mean Human Readable
2. Very strict syntax - Indentation Important
3. easily convertable in Json or XML
4. Most programming lang uses YAML
5. most powerful when representing complex data
6. use various tools available in YAML
7. passing is easy   

---
The file starts with three dashes. These dashes indicate the start of a new YAML document. YAML supports multiple documents, and compliant parsers will recognize each set of dashes as the beginning of a new one.

yaml works in Key and Pair bond
'sunday' : "first day of week"
"monday" : "Second day of week"
 
## List
- Apple
- apple note - yaml is case sensitive
- Orange
- mango

## Block style
cities:
    - new delhi
    - Gurugram
    - Varanasi
    - meerut
YAml have indentation problem like Python
> if you don't want indentation problem than put inputs inside [] or {}

### YAML Datatypes
Values in YAML's key-value pairs are scalar. They act like the scalar types in languages like Perl, Javascript, and Python. It's usually good enough to enclose strings in quotes, leave numbers unquoted, and let the parser figure it out. But that's only the tip of the iceberg. YAML is capable of a great deal more.

### Key-Value Pairs and Dictionaries
The key-value is YAML's basic building block. Every item in a YAML document is a member of at least one dictionary. The key is always a string. The value is a scalar so that it can be any datatype. So, as we've already seen, the value can be a string, a number, or another dictionary.

### Numeric types
YAML recognizes numeric types. We saw floating point and integers above. YAML supports several other numeric types. An integer can be decimal, hexidecimal, or octal.
`
---
 foo: 12345
 bar: 0x12d4
 plop: 023332
 
 `
### Nulls
You enter nulls with a tilde or the unquoted null string literal.

`---
foo: ~
bar: null`

### Booleans
YAML indicates boolean values with the keywords True, On and Yes for true. False is indicated with False, Off, or No.