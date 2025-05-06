
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
