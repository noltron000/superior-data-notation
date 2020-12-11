# Superior Data Notation
Imagine this for a moment, dear developer.
Comments in your `JSON`.
Variables in your `CSV`.
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
