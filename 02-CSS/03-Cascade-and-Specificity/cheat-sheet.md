# CSS Module 03 — Cheat Sheet

## Cascade 

CSS system used to resolve conflicts between competing declarations.

## Inheritance

Certain property values pass from a parent to its descendants.

**Common inherited:**`color`, `font-family`, `font-size`, `line-height`

**Common non-inherited:**`margin`, `padding`,`border`,`width`,`height`

### `inherit`
Uses the parent element's value.

## Specificity

Determines which selector has priority when rules conflict.

``` text
ID > Class / Attribute / Pseudo-class > Element / Pseudo-element
```
## Source Order

If completing declarations have equal specificity and importance, the **later rule wins.**

`!important`

Gives a declaration higher importance than normal declarations.

**Best Practice:** Avoid unnecessary use of `!important`.

## Quick Memory

``` text
Cascade         -> Resolves CSS conflicts
Inheritance     -> Parent -> Child
Specificity     -> Selector Priority
Source Order    -> Later wins if specificity is equal
!important      -> Higher importance than normal declarations
```
