<!-- .slide: data-auto-animate -->

# Requirements

## DFIs

- **MUST** define one or more methods
- Method definitions **SHOULD NOT** overlap
- **MUST NOT** extend ARIs
- **MAY** extend other DFIs
- **MUST NOT** be used for class constructor type definitions
- **SHOULD NOT** be implemented by a class directly

***

<!-- .slide: data-auto-animate -->

# Requirements

## (Pure) ARIs

- **MUST NOT** define methods
- **MUST** extend one or more DFIs
  - This is where method definition comes from
- **MAY** extend other ARIs
- **SHOULD NOT** be used for function parameter type definitions

***

<!-- .slide: data-auto-animate -->

# Requirements

## One Final Rule

## You will break these rules! <!-- .element: class="fragment" -->
