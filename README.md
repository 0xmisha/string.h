# Summary of string+ Project

In the `s21_string+` project, the aim was to create a custom implementation of the `string.h` library in the C programming language, enriching it with additional features.

## Installation:
````
git clone https://github.com/0xmisha/string.h.git
cd string.h/src
make
````

## Requirements:

- Gcc
- Make
- check.h (for tests)

## Key Deliverables:

1. **Standard string.h Functions**: The core part of the project was to replicate the functionality found in the standard `string.h` library. Functions such as `memchr`, `memcpy`, `strncpy`, and `strtok` are a few to mention.

2. **sprintf and sscanf Functions**: The standard `sprintf` and `sscanf` functions, which deal with formatted input and output to and from strings, were also to be implemented.

3. **Special String Processing Functions**: Inspired by the String class in C#, the project also required the addition of some advanced string manipulations. These functions, like `to_upper`, `to_lower`, `insert`, and `trim`, augment the traditional string processing capabilities.

4. **Quality Assurance Measures**: 
   - Adherence to the Google coding style was mandated.
   - The entire codebase, encompassing headers, the library, and even the Makefile, was to reside in the `src` folder on the `develop` branch.
   - The project had a strong emphasis on structured programming, mandating minimal code repetition.
   - Unit-testing, with at least 80% coverage per function, was enforced, using the `Check` library.
   - A `gcov` report in the form of an HTML page was to be generated to validate the coverage.

5. **Compliance and Restrictions**: 
   - The C11 standard was to be followed throughout, utilizing the `gcc` compiler.
   - Direct copying from the standard `string.h` or other string processing libraries was strictly prohibited, barring unit tests.
   - Functions were supposed to work specifically with single-byte ASCII characters.

6. **Bonus Tasks**: For additional credit, participants could implement advanced format modifiers for `sprintf` and `sscanf`, and further special string processing functions from the C# String class.

In essence, the `s21_string+` project is a comprehensive endeavor to understand, reimplement, and expand upon the classic `string.h` library. The meticulous requirements ensure not just functional accuracy, but also coding best practices and rigorous testing.