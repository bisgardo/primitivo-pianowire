# Primitivo Pionowire

Small utility library for working with "raw" strings in Java (i.e. char- and byte-arrays).
To that end, various useful package-private features in the `java.lang` package are exposed in a safe way.

The library was extracted from
[string-surgery](https://github.com/halleknast/string-surgery.git)
because the exposed classes have had breaking changes in Java 9.
They also may not have fit well into that project,
or really be all that useful in the first place...

The only dependencies of the project are JDK 1.5-1.8 and [primitivo](https://github.com/halleknast/primitivo).
