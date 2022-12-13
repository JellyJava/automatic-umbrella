# Propositions

* Truth table generator: <https://web.stanford.edu/class/cs103/tools/truth-table-tool/>

# Equivalence Validity

* Logically equivalent: If all the truth table results are same
* Equivalence laws:

<img src="/images/equivalence_laws.jpg" width="70%" height="70%"></img>

* Validity error:

<img src="/images/validity.png" width="70%" height="70%"></img>

* How to check if arguement is valid?
  1. Truth Table: Be aware of T - T - F case
  2. Inference rules

# Inference

* Inference rules:

<img src="/images/inference_rules.jpg" width="70%" height="70%"></img>

# Predicate

* Negation of quantified statements:
  * ~(∀x ∈ D, p(x)) ≡ ∃x ∈ D, ~p(x)
  * ~(∃x ∈ D, p(x)) ≡ ∀x ∈ D, ~p(x)

* Negation of universal conditional statements
  * ~((∀x ∈ D, p(x)) ≡ ∃x, ~(p(x) → q(x)) ≡ ∃x, (p(x) ∧ ~q(x))

* Negation of propositions with multiple quantifiers

<img src="/images/multiple.jpeg" width="70%" height="70%"></img>

# Proof

* Methods of mathematical proof

<img src="/images/proof.png" width="70%" height="70%"></img>

# Sequences

* Recursion proof example with tower of hanoi:

<img src="/images/recursive_hanoi.png" width="70%" height="70%"></img>

# Sets

* Terms
  * Subset
  * Not subset
  * Proper subset
  * Equals: Prove X ⊂= Y and Y ⊂= X
  * Union: A ∪ B
  * Intersection: A ∩ B
  * Difference: B - A
  * Complement: A'
  * Empty set
  * Disjoint
  * Mutually disjoint: If all the sets are disjoint
  * Partition
  * Power set: P(A) = Set of all subsets of A
  * Ordered n-tuple: (x1, x2, ..., xn) "ordered" tuple
    * Two ordered n-tuples (x1, x2, ..., xn) and (y1, y2, ..., yn) are equal if and only if x1 = y1, x2 = y2, ..., xn = yn
 
* Procedural versions of set definitions

<img src="/images/procedural.png" width="60%" height="60%"></img>

* Set identities

<img src="/images/set_identities.png" width="70%" height="70%"></img>

* How to prove a set equals to an empty set
  * Prove X has no elements
  * Suppose X has elements and derive a contradiction

# Functions

* Onto function: f(x) = y
* Composition function: g(f(x))

* Example of proving onto function

<img src="/images/prove_onto.png" width="70%" height="70%"></img>

# Infinite Sets

* Cardinality: a measure of the number of elements of the set
* Sets: Integers are countable, Rationals are countable, Reals are uncountable

# Relation

* Function / Relation
* Properties: Reflexivity, Symmetry, Transitivity
* Equivalence relation: R is reflexive, symmetric, transitive
* Inverse relation:

<img src="/images/inverse.png" width="60%" height="60%"></img>
