# Superior Data Notation
Imagine this for a moment, dear developer.
Comments in your `JSON`. <!-- Variables in your `CSV`. -->
Ordered keys in your dictionary.
Unordered sets to contain unique items.
Arrays as dictionary keys, even.

But alas, such a thing does not exist!
...until now.
Introducing, the Superior Data Notation (`.SDN`) filetype!
\**Cough*\* the proposal, anyway. \**Cough*\*

The idea is, this format supports a larger variaty of types and structures than other traditional data formats like json.
And why not?
Ha, answer that question if you want, but the truth is, *I* would absolutely want to use this format.

## Data Types
Here is the list of data types available to the `.SDN` filetype.

Void Primitives
- `undefined`
- `null`

Boolean Primitives
- `true`
- `false`

Numeric Primitives
- `#` (integer)
- `#.#` (decimal)
- `infinity`
- `nonnumeric`

Text Primitives
- `'...'` (single-line string)
- `"..."` (multi-line capable string)

List Data Types
- `[ ..., ]` (standard array)
- `[[ ..., ]]` (array; a list with ordered values)
- `[( ..., )]` (collection; a list with unique, ordered values)
- `[{ ..., }]` (set; a list with unique, unordered values)

Lookup-Table Data Types
- `{ ...: ..., }` (standard dictionary)
- `{{ ...: ..., }}` (dictionary; a lookup-table with unique, unordered keys)
- `{( ...: ..., )}` (ordered dictionary; a lookup-table with unique, ordered keys)
- `{[ ...: ..., ]}` (slot-book; a lookup-table with ordered keys that don't have to be unique)

### Void Primitives
### Boolean Primitives
### Numeric Primitives
Quantifiable numbers, such as decimals and integers, only use a certain set of characters.
These characters include `+-–e.0123456789`.
- A plus symbol (`+`) put in front of a number can be used to explicitly indicate a positive number, although omitting a sign implicitly indicates a positive number.
- A hyphen symbol (`-`) or minus symbol (`–`) put in front of a number can be used to explicitly indicate a negative number.
- No combination of plus and minus symbols may be used.
- A single decimal point (`.`)

There are five parts to a number. `-100.007E32`
1. the signage `+`/`-`/`–`
1. the integer digits `100`
1. the decimal `.`
1. the fractional digits `007`
1. euler's number `e`, `E`
1. euler's signage  `+`/`-`/`–`
1. the exponent factor `32`

### Text Primitives
### List Data Types
### Lookup-Table Data Types

## Comments
You can use `//...` or `#...` for single-line comments, and `/*...*/` or `<!--...-->`for multiline comments.

## Operators
There is no arithmatic or logic permitted within a `.SDN` file.
