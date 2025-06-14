# clon

Clon Locates Obvious Nonsense

## Algorithm

Clon implements the anti-unification algorithm for clone detection described in:

**"Duplicate code detection using anti-unification"**  
*Peter E. Bulychev & Marius Minea*  
*Spring Young Researchers Colloquium on Software Engineering (2008)*

This approach detects semantic duplicates by identifying code fragments where one can
be obtained from another by replacing subtrees in the Abstract Syntax Tree.
