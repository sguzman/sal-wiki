# Research in mathematics

## Summary
- [[Research in Mathematics (Legacy)]]

This page gathers the main mathematical research directions in this wiki. It is not a record of completed results. It is a programmatic page: a place to describe what kinds of mathematics are being pursued, why these questions recur, and what larger ambitions unify them. The underlying list of topics ranges across analysis, topology, operator theory, symbolic systems, curvature, coordinate formalisms, functional iteration, and speculative foundational questions.

The dominant character of this research is not narrow specialization. It is an attempt to build new bridges across mathematical traditions. In particular, it treats mathematics as a field of possible translations: from symbolic expressions to functions, from functions to operators, from curves to matrices, from geometry to dynamics, and from discrete procedures to continuous formalisms. Many of the individual topics are short prompts rather than full theories, but they repeatedly point in the same direction.

At the center of this program is a strong attraction to [[Analysis]], especially to the possibility that analytic structure may serve as a deep common medium for many other branches of mathematics. Around that core sit several related ambitions: to understand function application itself as a mathematical object, to treat curvature as an informational and program-like quantity, to reinterpret spaces and curves through new encodings, and to use [[Operator theory]] as a language for iteration, dynamics, and hard discrete problems such as the [[Collatz conjecture]].

## General orientation

The mathematical research gathered here is guided by a few recurring instincts.

First, it is guided by the idea that many existing mathematical formalisms may be too locally specialized. Different fields often develop their own native objects and operations, but one ambition of this project is to ask whether those objects can be translated into more universal media, especially continuous and operator-theoretic ones. This is visible in questions about mapping algebraic objects back to integers, building programming primitives from analysis, representing curves by infinite matrices of zeros and ones, or translating real curves into holomorphic structure.

Second, it is guided by a desire to treat mathematical operations themselves as first-class objects. Instead of taking function application, iteration, integration, homotopy, or algebraic manipulation for granted, this research repeatedly asks whether those acts can themselves be formalized, decomposed, fractionalized, localized, or turned into operators. That is why the notes repeatedly return to topics such as fractional application of a function, analytic formalisms for function application, functional iterators, linear homotopy as fractional function application, and extracting an “iterator” object from an integral range.

Third, it is driven by a structural rather than merely computational view of mathematics. The main question is often not “How do I calculate this faster?” but “What kind of thing is this operation really?” and “Can it be re-described in a way that reveals hidden unity?” Even when a topic begins with a concrete image, such as scrolling over a subset of (R^2), intersecting boolean-valued curve matrices, or scanning a function with a dot product, the deeper interest is usually formal: how to turn local manipulations into a general mathematical language.

## Major lines of research

## Analysis as a universal encoding medium

The largest and most important research direction is the attempt to use [[Analysis]] as a broad framework for representing and transforming other mathematical structures.

This ambition appears in many entries. There are notes on convolution with $e^{-x^2}$ as a “cursor,” on convolution as an incremental application of one function onto another substrate, on analytic formalisms for function application and composition, on using the Laplacian to convert one function into another in a continuous way, on generalized integral transforms that extract or destructure properties of functions and algebraic objects, and on turning discrete mathematical activity into continuous form.

In plain terms, the project here is to ask whether continuous mathematics can do more than study already-continuous things. The hope is that it may also serve as a language for _rewriting_ symbolic, algebraic, or algorithmic processes into a continuous setting where new tools become available. This is closely connected to the speculative ambition, already described elsewhere in this wiki, of using the continuum as a kind of Rosetta stone for many mathematical traditions.

Several notes point toward a theory of function application as an analytic process. Instead of viewing a function as a black-box rule from input to output, this research asks whether function application can be decomposed into smaller continuous motions or transforms. That is the intuition behind phrases such as “incrementally apply and compose functions,” “computing analytical and continuous version of function application,” and “fractional application of a function.”

This line of work would sit near [[Real analysis]], [[Functional analysis]], [[Integral transform]]s, and possibly [[Operator theory]]. It also overlaps with questions about iteration, recursion, and programming semantics, because once one begins formalizing function application, one is already close to formalizing programs.

## Function semantics, iteration, and self-reference

A second major research line studies functions not merely as static mappings, but as processes that can reference themselves, iterate themselves, and generate complex behavior over time.

This appears in notes about “having a function reference itself,” “develop an operator that can iterate a number an indefinite number of times,” “creating a general functional iterator that takes a function and composes itself once,” “process oriented function semantics to represent recursive functions,” and “function semantics that comprehensively handles recursive call bombs.”

The basic motivation is that mathematics often defines functions extensionally, meaning by what outputs they give on inputs. But in programming and dynamics, one often cares about _how_ a transformation unfolds as a process. This research direction tries to build a mathematics of that unfolding. It wants a language in which iteration itself is formalized, where recursive self-reference becomes mathematically tractable rather than merely syntactic, and where repeated application can be studied as a genuine object rather than just an instruction.

This is one reason the notes frequently blur the line between mathematics and programming. Phrases like “an expression as a program,” “normalizing a program to a mathematical expression,” and “compressed executable that is semantically equivalent to uncompressed” are all part of the same conceptual tendency. The hope is that symbolic expressions, programs, and functions may be studied inside one larger framework of transformation and normalization.

In more standard mathematical language, this line of thought sits near [[Dynamical system]]s, [[Operator theory]], [[Lambda calculus]], [[Recursion]], and parts of [[Mathematical logic]]. But the ambition here is broader than any one of those fields alone. It is to create a unified semantics of application, iteration, and symbolic compression.

## Curvature, geometry, and information

A third major line of research treats curvature as far more than a geometric measurement. In these notes, curvature is repeatedly treated as an informational and program-like quantity.

This appears in entries such as “multiplying by x as imbuing of curvature,” “all single-term polynomials have complete curvature of 2,” “curvature as a measure of information,” “curvature as a program to steer function,” “using complex numbers to model curvature,” and “the more curvy, the more linear terms is needed to duplicate it.”

The underlying thought seems to be that curvature may encode complexity, deviation, expressiveness, or steering behavior in a way that deserves a more general theory. A straight line is simple because its direction does not change. A more curved object may carry more local variation and therefore require more descriptive resources to reproduce. In that sense, curvature begins to look like a measure of informational content rather than merely a geometric invariant.

This is especially interesting because it pulls together several mathematical regions at once. [[Differential geometry]] studies curvature geometrically. [[Complex analysis]] and holomorphic methods can encode rotations and local structure. Approximation theory studies how many simple components are needed to represent more complex forms. This research seems to want a synthesis in which curvature is not just “how bent something is,” but a quantity tied to representation, information, and control.

This line is still speculative, but it has a clear possible future: a theory where local geometric deviation corresponds to formal complexity, and where operators acting on curvature become a way of steering or programming functions.

## Operator-theoretic dynamics

Another central research direction uses [[Operator theory]] as a general language for dynamics.

This is visible in notes on solving the [[Collatz conjecture]] using operator theory, constructing an integral transform for Collatz orbit lengths, modifying the Collatz function by adjoining fixed terminal values at 0 and 1, using operator theory to study arbitrary state spaces, and even using operator theory to study genome states and genetic mutation.

The common idea is that many evolving systems can be understood as repeated action of a transformation on a state space. Instead of focusing on individual sequences case by case, one tries to build an operator that captures the global behavior of the system. Once that operator exists, one may hope to study its spectrum, invariant sets, fixed points, orbit lengths, stability, or asymptotic behavior with the tools of analysis.

In plain language, this is the attempt to replace “watching the process one input at a time” with “studying the machine that generates all such processes.” That shift is mathematically powerful. It is standard in some parts of analysis and dynamics, but here it is being pushed into more speculative territory, especially with hard arithmetic problems and biological state spaces.

The Collatz-related notes are especially revealing. They suggest a desire not merely to prove a specific conjecture, but to build a more general operator-theoretic framework for iteration in number theory. Even if the specific conjecture remains unsolved, the surrounding framework could still become valuable.

## Alternative coordinate systems and geometric encodings

A further research cluster concerns alternative ways of representing space, curves, and geometric information.

This includes notes on the Cartesian plane as a binary switchboard, unit circle projection, representing (R^2) as an infinite matrix centered at the origin, representing curves as boolean-valued fields on (R^2), multiplying curve-matrices to find intersections, extending dimensions by padding rows and columns with zeros, creating a relativized version of (R^2) where one reference curve is treated as equivalent to another, and creating a coordinate system based on dot product and function/vector relations rather than standard Cartesian coordinates.

What ties these together is a dissatisfaction with inherited coordinate systems as the only natural way to describe geometric objects. The project seems to ask: what if a curve were not primarily represented as an equation, but as occupancy data in an infinite field? What if geometry were encoded in a matrix-like substrate that supports algebraic operations such as multiplication, zooming, scrolling, or local padding? What if one could define a coordinate system relative to a privileged curve rather than relative to straight axes?

In standard mathematics, similar impulses appear in [[Differential geometry]], [[Geometric measure theory]], [[Digital geometry]], [[Integral geometry]], and parts of [[Topology]]. But here the interest is more synthetic and interface-driven. Some notes clearly imagine not only a theory, but also a toolset: scrolling over subsets of (R^2), building 2D user artifacts for mathematical interaction, and treating the Euclidean plane itself as a manipulable workspace.

This makes the line important not only mathematically but also epistemically. It is partly a search for better mathematical _representations_, and therefore for better mathematical thinking tools.

## Topology, homotopy, and ambient reformulation

Another family of topics concerns [[Topology]] and the attempt to reinterpret topological questions through ambient space, boundary behavior, and linearized transformations.

This includes notes such as “does homeomorphism always imply homeomorphism between boundaries?”, “when does linear homotopy allow homeomorphism?”, “linear homotopy as a semigroup of bounded linear operators,” “using ambient space to exogenously study connectedness and holes,” “distinguishing between homology and connectedness,” “mapping neighborhoods across homeomorphism,” and “treating all topological spaces as compact” by adjoining disconnected pieces as aggregate spaces.

The common pattern here is an attempt to make topology less purely intrinsic and more operational. Classical topology often studies spaces through open sets, continuous maps, and invariants internal to the space. These notes suggest an interest in studying topological structure _from the outside_: via embeddings, boundary geometry, ambient neighborhoods, or linear operators that interpolate between maps.

That is an interesting instinct. It asks whether the connectedness or hole-structure of a space might sometimes be better understood through the geometry of the surrounding environment rather than solely through internal axioms. It also asks whether homotopy, usually treated as a continuous deformation between maps, may in some cases be recast in operator-theoretic or fractional terms.

This line is still exploratory, but it has a clear aim: to make topological structure more tractable by giving it new encodings and more operational descriptions.

## Algebra, expressions, and symbolic mechanics

A further cluster concerns algebraic expressions and symbolic structures treated as manipulable objects in their own right.

This appears in phrases such as “algebra as a crude mechanic process,” “algebraic expressions as a sequence of associative function compositions,” “an equation as a manipulable algebraic object,” “normal form of an expression as the compressed symbolic version of un-normalizable variants,” and “inside a sum is a more expressive language.”

The deeper concern here seems to be that ordinary algebraic notation hides the processual and compositional structure of what it is doing. Instead of seeing an equation as a finished statement, this research wants to see it as something like a machine, or at least as an object that can be transformed, compressed, normalized, and interpreted semantically.

That fits with the broader project of turning syntax into substance. It also explains why symbolic normalization and compression appear so often. The aim is not merely to simplify expressions for convenience, but to understand simplification itself as revealing some deeper equivalence between different symbolic realizations of the same mathematical content.

This area lies near [[Algebra]], [[Term rewriting]], [[Programming language theory]], and [[Mathematical logic]], but with a more explicitly semantic and structural emphasis.

## Number, coding, and universal indexing ambitions

Some of the most ambitious notes concern the dream of mapping very different mathematical objects back into integers or other universal coding domains.

This appears directly in the idea that all mathematical fields should have some way of uniquely mapping their idiosyncratic algebraic objects back to integers.

The aspiration here is foundational. Integers are the clearest and most discrete coding medium in mathematics. If one could map more complex objects back to integers in a faithful and structured way, then one might hope to compare fields, compress formal objects, or transport questions from one domain into another. This idea resonates with classical coding methods, Gödel-like encodings, symbolic compression, and computability, but the tone here is broader and more metaphysical: it is a search for a common representational substrate.

This also helps explain related notes about (e), sums, nested operations, and expressive syntax. They all circle around questions of expressive economy: what kinds of primitive objects or operations can generate a very large class of mathematical structures with maximal compactness?

## Measure, randomness, and deterministic reformulation

A smaller but important line of inquiry concerns [[Measure]], randomness, and the possibility of deterministic formalisms for apparently random phenomena.

This is visible in the notes on generalized unit measure, measuring the health of mathematical formalisms by open problems, deterministic formalisms for random phenomena, nested Riemann sums for error estimation, and using the Dirac delta as a zero detector.

The underlying idea seems to be that many notions of randomness, error, and detectability may be reformulated through carefully chosen measures or transforms. Rather than accepting randomness as primitive, one asks what structure beneath it can be extracted. Rather than accepting a measurement convention as fixed, one asks whether a more generalized relative unit system is possible.

This fits naturally with the larger analytic program, since analysis is already the natural home of measure, integration, approximation, and error control.

## Meta-mathematical concerns

Not every topic in the research list is a direct mathematical construction. Some concern the practice and psychology of mathematics itself.

This includes explicit mention of symbol fatigue and math anxiety, as well as the proposal to measure the health of a formalism by the number of open problems attached to it.

These topics matter because they show that the project is not only about producing theorems. It is also about examining the usability and vitality of mathematical languages. A formalism may be technically powerful but cognitively exhausting. A subject may be fertile because it generates hard but meaningful questions. These are not trivial side comments. They belong to a broader vision in which mathematics is studied both as an objective body of structure and as a human system of symbolic work.

## Long-term ambition

Taken as a whole, this research program aims at a kind of mathematical unification, but not in the simplistic sense of reducing everything to one formula.

The larger ambition is to develop translation principles between major mathematical modes:

- between the discrete and the continuous
    
- between syntax and semantics
    
- between functions and operators
    
- between curves and algebraic encodings
    
- between geometry and information
    
- between local operations and global structure
    
- between symbolic processes and analyzable dynamics
    

That is why the research list can look eclectic at first glance. Its unity is not topical but structural. The repeated question is always some version of: **What is the deeper operational form of this thing, and into what larger mathematical language can it be translated?**

## Candidate subpages

As this section grows, it would make sense to split major themes into their own pages. Likely future pages include:

- [[Research in analysis]]
    
- [[Research in operator theory]]
    
- [[Research in topology]]
    
- [[Research in curvature]]
    
- [[Research in function semantics]]
    
- [[Research in mathematical encoding]]
    
- [[Research in Collatz]]
    
- [[Research in coordinate systems]]
    

## See also

- [[Research]]
    
- [[Mathematics]]
    
- [[Analysis]]
    
- [[Operator theory]]
    
- [[Topology]]
    
- [[Functional analysis]]
    
- [[Curvature]]
    
- [[Integral transform]]
    
- [[Function]]
    
- [[Iteration]]
    
- [[Recursion]]
    
- [[Representation]]
    
- [[Formal system]]
    
- [[Collatz conjecture]]