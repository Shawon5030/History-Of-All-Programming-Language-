
Python (programming language)

Article
Talk
Read
Edit
View history

Tools
Appearance hide
Text

Small

Standard

Large
Width

Standard

Wide
Color (beta)

Automatic

Light

Dark
From Wikipedia, the free encyclopedia
Python

Paradigm	Multi-paradigm: object-oriented,[1] procedural (imperative), functional, structured, reflective
Designed by	Guido van Rossum
Developer	Python Software Foundation
First appeared	20 February 1991; 34 years ago[2]
Stable release	
3.13.2 / 4 February 2025; 3 months ago
Typing discipline	duck, dynamic, strong;[3] optional type annotations (since 3.5, but those hints are ignored, except with unofficial tools)[4]
OS	
Tier 1: 64-bit Linux, macOS; 64- and 32-bit Windows 10+[5]
Tier 2: E.g. 32-bit WebAssembly (WASI)
Tier 3: 64-bit Android,[6] iOS, FreeBSD, and (32-bit) Raspberry Pi OS
Unofficial (or has been known to work): Other Unix-like/BSD variants) and a few other platforms[7][8][9]
License	Python Software Foundation License
Filename extensions	.py, .pyw, .pyz,[10]
.pyi, .pyc, .pyd
Website	python.org
Major implementations
CPython, PyPy, Stackless Python, MicroPython, CircuitPython, IronPython, Jython
Dialects
Cython, RPython, Starlark[11]
Influenced by
ABC,[12] Ada,[13] ALGOL 68,[14]
APL,[15] C,[16] C++,[17] CLU,[18] Dylan,[19]
Haskell,[20][15] Icon,[21] Lisp,[22]
Modula-3,[14][17] Perl,[23] Standard ML[15]
Influenced
Apache Groovy, Boo, Cobra, CoffeeScript,[24] D, F#, GDScript, Go, JavaScript,[25][26] Julia,[27] Mojo,[28] Nim, Ring,[29] Ruby,[30] Swift,[31] V[32]
 Python Programming at Wikibooks
Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation.[33]

Python is dynamically type-checked and garbage-collected. It supports multiple programming paradigms, including structured (particularly procedural), object-oriented and functional programming. It is often described as a "batteries included" language due to its comprehensive standard library.[34][35]

Guido van Rossum began working on Python in the late 1980s as a successor to the ABC programming language, and he first released it in 1991 as Python 0.9.0.[36] Python 2.0 was released in 2000. Python 3.0, released in 2008, was a major revision not completely backward-compatible with earlier versions. Python 2.7.18, released in 2020, was the last release of Python 2.[37]

Python consistently ranks as one of the most popular programming languages, and it has gained widespread use in the machine learning community.[38][39][40][41]

History
Main article: History of Python

The designer of Python, Guido van Rossum, at PyCon US 2024
Python was conceived in the late 1980s[42] by Guido van Rossum at Centrum Wiskunde & Informatica (CWI) in the Netherlands; it was conceived as a successor to the ABC programming language, which was inspired by SETL,[43] capable of exception handling and interfacing with the Amoeba operating system.[12] Python implementation began in December 1989.[44] Van Rossum assumed sole responsibility for the project, as the lead developer, until 12 July 2018, when he announced his "permanent vacation" from responsibilities as Python's "benevolent dictator for life" (BDFL); this title was bestowed on him by the Python community to reflect his long-term commitment as the project's chief decision-maker.[45] (He has since come out of retirement and is self-titled "BDFL-emeritus".) In January 2019, active Python core developers elected a five-member Steering Council to lead the project.[46][47]

The name Python is said to derive from the British comedy series Monty Python's Flying Circus.[48]

Python 2.0 was released on 16 October 2000, with many major new features such as list comprehensions, cycle-detecting garbage collection, reference counting, and Unicode support.[49] Python 2.7's end-of-life was initially set for 2015, and then postponed to 2020 out of concern that a large body of existing code could not easily be forward-ported to Python 3.[50][51] It no longer receives security patches or updates.[52][53] While Python 2.7 and older versions are officially unsupported, a different unofficial Python implementation, PyPy, continues to support Python 2, i.e., "2.7.18+" (plus 3.10), with the plus signifying (at least some) "backported security updates".[54]

Python 3.0 was released on 3 December 2008, with some new semantics and changed syntax. At least every Python release since (the now unsupported) 3.5 has added some syntax to the language; a few later releases have removed outdated modules and have changed semantics, at least in a minor way.

As of 8 April 2025, Python 3.13.3 is the latest stable release (it's highly recommended to upgrade to it, or upgrade any other older 3.x release). This version currently receives full bug-fix and security updates, while Python 3.12—released in October 2023—had active bug-fix support only until April 2025, and since then only security fixes. Python 3.9[55] is the oldest supported version of Python (albeit in the 'security support' phase), because Python 3.8 has become an end-of-life product.[56][57] Starting with Python 3.13, it and later versions receive two years of full support (which has increased from one and a half years), followed by three years of security support; this is the same total duration of support as previously.

Security updates were expedited in 2021 and again twice in 2022. More issues were fixed in 2023 and in September 2024 (for Python versions 3.8.20 through 3.12.6)—all versions (including 2.7)[58] had been insecure because of issues leading to possible remote code execution[59] and web-cache poisoning.[60]

Python 3.10 added the | union type operator[61] and the match and case keywords (for structural pattern matching statements). Python 3.11 expanded exception handling functionality. Python 3.12 added the new keyword type. Notable changes from version 3.10 to 3.11 include increased program execution speed and improved error reporting.[62] Python 3.11 is claimed to be 10–60% faster than Python 3.10, and Python 3.12 increases by an additional 5%. Python 3.12 also includes improved error messages (again improved in 3.14) and many other changes.

Python 3.13 introduces more syntax for types; a new and improved interactive interpreter (REPL), featuring multi-line editing and color support; an incremental garbage collector, which results in shorter pauses for collection in programs that have many objects, as well as increasing the improved speed in 3.11 and 3.12); an experimental just-in-time (JIT) compiler (such features, can/needs to be enabled specifically for the increase in speed);[63] and an experimental free-threaded build mode, which disables the global interpreter lock (GIL), allowing threads to run more concurrently, as enabled inpython3.13t or python3.13t.exe.

Python 3.13 introduces some changes in behavior, i.e., new "well-defined semantics", fixing bugs, and removing many deprecated classes, functions and methods (as well as some of the Python/C API and outdated modules). "The old implementation of locals() and frame.f_locals was slow, inconsistent and buggy, and it had many corner cases and oddities. Code that works around those may need revising; code that uses locals() for simple templating or print debugging should continue to work correctly."[64]

Python 3.13 introduces the experimental free-threaded build mode, which disables the Global Interpreter Lock (GIL); the GIL is a feature of CPython that previously prevented multiple threads from executing Python bytecode simultaneously. This optional build, introduced through PEP 703, enables better exploitation of multi-core CPUs. By allowing multiple threads to run Python code in parallel, the free-threaded mode addresses long-standing performance bottlenecks associated with the GIL. This change offers a new path for parallelism in Python, without resorting to multiprocessing or external concurrency frameworks.[65]

Some additional standard-library modules will be removed in Python 3.15 or 3.16, as will be many deprecated classes, functions and methods.[66][67]

Python 3.11 adds Sigstore digital verification signatures for all CPython artifacts (in addition to the now deprecated PGP signatures); the use of PGP has been criticized by security practitioners, Python is transitioning to Sigstore exclusively and plans to drop PGP in version 3.14.[68]

Python 3.12 removed wstr meaning Python extensions[69] need to be modified,[70] and 3.10 added pattern matching to the language.[71]

Python 3.12 dropped some outdated modules, and more will be dropped in the future, deprecated as of 3.13; already deprecated array 'u' format code will emit DeprecationWarning since 3.13 and will be removed in Python 3.16. The 'w' format code should be used instead. Part of ctypes is also deprecated and http.server.CGIHTTPRequestHandler will emit a DeprecationWarning, and will be removed in 3.15. Using that code already has a high potential for both security and functionality bugs. Parts of the typing module are deprecated, e.g. creating a typing.NamedTuple class using keyword arguments to denote the fields and such (and more) will be disallowed in Python 3.15.

Python 3.14 is now in the alpha 3 phase. With regard to possible change to annotations, "In Python 3.14, from __future__ import annotations will continue to work as it did before, converting annotations into strings."[72]

Python Enhancement Proposal (PEP) 711 proposes PyBI—a standard format for distributing Python binaries.[73]

Python 3.15 will "Make UTF-8 mode default";[74] This mode is supported in all current Python versions, but it currently must be opted into. UTF-8 is already used by default on Windows (and other operating systems) for most purposes; an exception is opening files. Enabling UTF-8 also makes code fully cross-platform.

Design philosophy and features
Python is a multi-paradigm programming language. Object-oriented programming and structured programming are fully supported, and many of their features support functional programming and aspect-oriented programming (including metaprogramming[75] and metaobjects).[76] Many other paradigms are supported via extensions, including design by contract[77][78] and logic programming.[79] Python is often referred to as a 'glue language'[80] because it can seamlessly integrate components written in other languages.

Python uses dynamic typing and a combination of reference counting and a cycle-detecting garbage collector for memory management.[81] It uses dynamic name resolution (late binding), which binds method and variable names during program execution.

Python's design offers some support for functional programming in the Lisp tradition. It has filter,mapandreduce functions; list comprehensions, dictionaries, sets, and generator expressions.[82] The standard library has two modules (itertools and functools) that implement functional tools borrowed from Haskell and Standard ML.[83]

Python's core philosophy is summarized in the Zen of Python (PEP 20), which includes aphorisms such as these:[84]

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Readability counts.
However, Python features regularly violate these principles and have received criticism for adding unnecessary language bloat.[85] Responses to these criticisms note that the Zen of Python is a guideline rather than a rule.[86] The addition of some new features had been controversial: Guido van Rossum resigned as Benevolent Dictator for Life after conflict about adding the assignment expression operator in Python 3.8.[87][88]

Nevertheless, rather than building all functionality into its core, Python was designed to be highly extensible via modules. This compact modularity has made it particularly popular as a means of adding programmable interfaces to existing applications. Van Rossum's vision of a small core language with a large standard library and easily extensible interpreter stemmed from his frustrations with ABC, which represented the opposite approach.[42]

Python claims to strive for a simpler, less-cluttered syntax and grammar, while giving developers a choice in their coding methodology. In contrast to Perl's motto "there is more than one way to do it", Python advocates an approach where "there should be one—and preferably only one—obvious way to do it.".[84] In practice, however, Python provides many ways to achieve a given goal. There are, for example, at least three ways to format a string literal, with no certainty as to which one a programmer should use.[89] Alex Martelli is a Fellow at the Python Software Foundation and Python book author; he wrote that "To describe something as 'clever' is not considered a compliment in the Python culture."[90]

Python's developers usually try to avoid premature optimization; they also reject patches to non-critical parts of the CPython reference implementation that would offer marginal increases in speed at the cost of clarity.[91] Execution speed can be improved by moving speed-critical functions to extension modules written in languages such as C, or by using a just-in-time compiler like PyPy. It is also possible to cross-compile to other languages; but this approach either fails to achieve the expected speed-up, since Python is a very dynamic language, or only a restricted subset of Python is compiled (with potential minor semantic changes).[92]

Python's developers aim for the language to be fun to use. This goal is reflected in the name—a tribute to the British comedy group Monty Python[93]—and in playful approaches to some tutorials and reference materials. For instance, some code examples use the terms "spam" and "eggs" (in reference to a Monty Python sketch), rather than the typical terms "foo" and "bar".[94][95] A common neologism in the Python community is pythonic, which has a wide range of meanings related to program style. Pythonic code may use Python idioms well; be natural or show fluency in the language; or conform with Python's minimalist philosophy and emphasis on readability.[96]

Syntax and semantics
Main article: Python syntax and semantics
Block of Python code showing sample source code
An example of Python code and indentation
C code featuring curly braces and semicolon
Example of C# code with curly braces and semicolons
Python is meant to be an easily readable language. Its formatting is visually uncluttered and often uses English keywords where other languages use punctuation. Unlike many other languages, it does not use curly brackets to delimit blocks, and semicolons after statements are allowed but rarely used. It has fewer syntactic exceptions and special cases than C or Pascal.[97]

Indentation
Main article: Python syntax and semantics § Indentation
Python uses whitespace indentation, rather than curly brackets or keywords, to delimit blocks. An increase in indentation comes after certain statements; a decrease in indentation signifies the end of the current block.[98] Thus, the program's visual structure accurately represents its semantic structure.[99] This feature is sometimes termed the off-side rule. Some other languages use indentation this way; but in most, indentation has no semantic meaning. The recommended indent size is four spaces.[100]

Statements and control flow
Python's statements include the following:

The assignment statement, using a single equals sign =
The if statement, which conditionally executes a block of code, along with else and elif (a contraction of else if)
The for statement, which iterates over an iterable object, capturing each element to a local variable for use by the attached block
The while statement, which executes a block of code as long as its condition is true
The try statement, which allows exceptions raised in its attached code block to be caught and handled by except clauses (or new syntax except* in Python 3.11 for exception groups[101]); the try statement also ensures that clean-up code in a finally block is always run regardless of how the block exits
The raise statement, used to raise a specified exception or re-raise a caught exception
The class statement, which executes a block of code and attaches its local namespace to a class, for use in object-oriented programming
The def statement, which defines a function or method
The with statement, which encloses a code block within a context manager, allowing resource-acquisition-is-initialization (RAII)-like behavior and replacing a common try/finally idiom[102] Examples of a context include acquiring a lock before some code is run, and then releasing the lock; or opening and then closing a file
The break statement, which exits a loop
The continue statement, which skips the rest of the current iteration and continues with the next
The del statement, which removes a variable—deleting the reference from the name to the value, and producing an error if the variable is referred to before it is redefined [a]
The pass statement, serving as a NOP (i.e., no operation), which is syntactically needed to create an empty code block
The assert statement, used in debugging to check for conditions that should apply
The yield statement, which returns a value from a generator function (and also an operator); used to implement coroutines
The return statement, used to return a value from a function
The import and from statements, used to import modules whose functions or variables can be used in the current program
The match and case statements, analogous to a switch statement construct, which compares an expression against one or more cases as a control-flow measure
The assignment statement (=) binds a name as a reference to a separate, dynamically allocated object. Variables may subsequently be rebound at any time to any object. In Python, a variable name is a generic reference holder without a fixed data type; however, it always refers to some object with a type. This is called dynamic typing—in contrast to statically-typed languages, where each variable may contain only a value of a certain type.

Python does not support tail call optimization or first-class continuations; according to Van Rossum, the language never will.[103][104] However, better support for coroutine-like functionality is provided by extending Python's generators.[105] Before 2.5, generators were lazy iterators; data was passed unidirectionally out of the generator. From Python 2.5 on, it is possible to pass data back into a generator function; and from version 3.3, data can be passed through multiple stack levels.[106]

Expressions
Python's expressions include the following:

The +, -, and * operators for mathematical addition, subtraction, and multiplication are similar to other languages, but the behavior of division differs. There are two types of division in Python: floor division (or integer division) //, and floating-point division /.[107] Python uses the ** operator for exponentiation.
Python uses the + operator for string concatenation. The language uses the * operator for duplicating a string a specified number of times.
The @ infix operator is intended to be used by libraries such as NumPy for matrix multiplication.[108][109]
The syntax :=, called the "walrus operator", was introduced in Python 3.8. This operator assigns values to variables as part of a larger expression.[110]
In Python, == compares two objects by value. Python's is operator may be used to compare object identities (i.e., comparison by reference), and comparisons may be chained—for example, a <= b <= c.
Python uses and, or, and not as Boolean operators.
Python has a type of expression called a list comprehension, and a more general expression called a generator expression.[82]
Anonymous functions are implemented using lambda expressions; however, there may be only one expression in each body.
Conditional expressions are written as x if c else y.[111] (This is different in operand order from the c ? x : y operator common to many other languages.)
Python makes a distinction between lists and tuples. Lists are written as [1, 2, 3], are mutable, and cannot be used as the keys of dictionaries (since dictionary keys must be immutable in Python). Tuples, written as (1, 2, 3), are immutable and thus can be used as the keys of dictionaries, provided that all of the tuple's elements are immutable. The + operator can be used to concatenate two tuples, which does not directly modify their contents, but produces a new tuple containing the elements of both. For example, given the variable t initially equal to (1, 2, 3), executing t = t + (4, 5) first evaluates t + (4, 5), which yields (1, 2, 3, 4, 5); this result is then assigned back to t—thereby effectively "modifying the contents" of t while conforming to the immutable nature of tuple objects. Parentheses are optional for tuples in unambiguous contexts.[112]
Python features sequence unpacking where multiple expressions, each evaluating to something assignable (e.g., a variable or a writable property) are associated just as in forming tuple literal; as a whole, the results are then put on the left-hand side of the equal sign in an assignment statement. This statement expects an iterable object on the right-hand side of the equal sign to produce the same number of values as the writable expressions on the left-hand side; while iterating, the statement assigns each of the values produced on the right to the corresponding expression on the left.[113]
Python has a "string format" operator % that functions analogously to printf format strings in the C language—e.g. "spam=%s eggs=%d" % ("blah", 2) evaluates to "spam=blah eggs=2". In Python 2.6+ and 3+, this operator was supplemented by the format() method of the str class, e.g., "spam={0} eggs={1}".format("blah", 2). Python 3.6 added "f-strings": spam = "blah"; eggs = 2; f'spam={spam} eggs={eggs}'.[114]
Strings in Python can be concatenated by "adding" them (using the same operator as for adding integers and floats); e.g., "spam" + "eggs" returns "spameggs". If strings contain numbers, they are concatenated as strings rather than as integers, e.g. "2" + "2" returns "22".
Python supports string literals in several ways:
Delimited by single or double quotation marks; single and double quotation marks have equivalent functionality (unlike in Unix shells, Perl, and Perl-influenced languages). Both marks use the backslash (\) as an escape character. String interpolation became available in Python 3.6 as "formatted string literals".[114]
Triple-quoted, i.e., starting and ending with three single or double quotation marks; this may span multiple lines and function like here documents in shells, Perl, and Ruby.
Raw string varieties, denoted by prefixing the string literal with r. Escape sequences are not interpreted; hence raw strings are useful where literal backslashes are common, such as in regular expressions and Windows-style paths. (Compare "@-quoting" in C#.)
Python has array index and array slicing expressions in lists, which are written as a[key], a[start:stop] or a[start:stop:step]. Indexes are zero-based, and negative indexes are relative to the end. Slices take elements from the start index up to, but not including, the stop index. The (optional) third slice parameter, called step or stride, allows elements to be skipped or reversed. Slice indexes may be omitted—for example, a[:] returns a copy of the entire list. Each element of a slice is a shallow copy.
In Python, a distinction between expressions and statements is rigidly enforced, in contrast to languages such as Common Lisp, Scheme, or Ruby. This distinction leads to duplicating some functionality, for example:

List comprehensions vs. for-loops
Conditional expressions vs. if blocks
The eval() vs. exec() built-in functions (in Python 2, exec is a statement); the former function is for expressions, while the latter is for statements
A statement cannot be part of an expression; because of this restriction, expressions such as list and dict comprehensions (and lambda expressions) cannot contain statements. As a particular case, an assignment statement such as a = 1 cannot be part of the conditional expression of a conditional statement.

Methods
Methods of objects are functions attached to the object's class; the syntax for normal methods and functions, instance.method(argument), is syntactic sugar for Class.method(instance, argument). Python methods have an explicit self parameter to access instance data, in contrast to the implicit self (or this) parameter in some object-oriented programming languages (e.g., C++, Java, Objective-C, Ruby).[115] Python also provides methods, often called dunder methods (because their names begin and end with double underscores); these methods allow user-defined classes to modify how they are handled by native operations including length, comparison, arithmetic, and type conversion.[116]

Typing

The standard type hierarchy in Python 3
Python uses duck typing, and it has typed objects but untyped variable names. Type constraints are not checked at definition time; rather, operations on an object may fail at usage time, indicating that the object is not of an appropriate type. Despite being dynamically typed, Python is strongly typed, forbidding operations that are poorly defined (e.g., adding a number and a string) rather than quietly attempting to interpret them.

Python allows programmers to define their own types using classes, most often for object-oriented programming. New instances of classes are constructed by calling the class, for example, SpamClass() or EggsClass()); the classes are instances of the metaclass type (which is an instance of itself), thereby allowing metaprogramming and reflection.

Before version 3.0, Python had two kinds of classes, both using the same syntax: old-style and new-style.[117] Current Python versions support the semantics of only the new style.

Python supports optional type annotations.[4][118] These annotations are not enforced by the language, but may be used by external tools such as mypy to catch errors.[119][120] Mypy also supports a Python compiler called mypyc, which leverages type annotations for optimization.[121]

Summary of Python 3's built-in types
Type	Mutability	Description	Syntax examples
bool	immutable	Boolean value	True
False
bytearray	mutable	Sequence of bytes	bytearray(b'Some ASCII')
bytearray(b"Some ASCII")
bytearray([119, 105, 107, 105])
bytes	immutable	Sequence of bytes	b'Some ASCII'
b"Some ASCII"
bytes([119, 105, 107, 105])
complex	immutable	Complex number with real and imaginary parts	3+2.7j
3 + 2.7j
dict	mutable	Associative array (or dictionary) of key and value pairs; can contain mixed types (keys and values); keys must be a hashable type	{'key1': 1.0, 3: False}
{}
types.EllipsisType	immutable	An ellipsis placeholder to be used as an index in NumPy arrays	...
Ellipsis
float	immutable	Double-precision floating-point number. The precision is machine-dependent, but in practice it is generally implemented as a 64-bit IEEE 754 number with 53 bits of precision.[122]	
1.33333

frozenset	immutable	Unordered set, contains no duplicates; can contain mixed types, if hashable	frozenset([4.0, 'string', True])
int	immutable	Integer of unlimited magnitude[123]	42
list	mutable	List, can contain mixed types	[4.0, 'string', True]
[]
types.NoneType	immutable	An object representing the absence of a value, often called null in other languages	None
types.NotImplementedType	immutable	A placeholder that can be returned from overloaded operators to indicate unsupported operand types.	NotImplemented
range	immutable	An immutable sequence of numbers, commonly used for iterating a specific number of times in for loops[124]	range(−1, 10)
range(10, −5, −2)
set	mutable	Unordered set, contains no duplicates; can contain mixed types, if hashable	{4.0, 'string', True}
set()
str	immutable	A character string: sequence of Unicode codepoints	'Wikipedia'
"Wikipedia"
"""Spanning
multiple
lines"""
Spanning
multiple
lines
tuple	immutable	Tuple, can contain mixed types	(4.0, 'string', True)
('single element',)
()
