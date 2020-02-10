** Diagnostic Message Codes **

Diagnostics are categorized into general ranges. If adding a new diagnostic message, use the first integral number greater than the last used number in the appropriate range.

1000 range for syntactic messages
2000 for semantic messages
4000 for declaration emit messages
5000 for compiler options messages
6000 for command line compiler messages
7000 for noImplicitAny messages

** General Constructs **

For a variety of reasons, we avoid certain constructs, and use some of our own. Among them:

Do not use for..in statements; instead, use ts.forEach, ts.forEachKey and ts.forEachValue. Be aware
 of their slightly different semantics.
Try to use ts.forEach, ts.map, and ts.filter instead of loops when it is not strongly inconvenient.
