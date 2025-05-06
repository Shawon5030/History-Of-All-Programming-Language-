
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
