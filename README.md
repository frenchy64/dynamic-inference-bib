This is a compilation of papers relating to _dynamic type inference_, that is,
using the results of a running program to summarise its execution, mostly for type inference.

# Dynamic type inference

##### Dynamic Type Inference to Support Object-Oriented Reengineering in Smalltalk
Pascal Rapicault, Mireille Blay-Fornarino, Stephane Ducasse, Anne-Marie Dery
http://scg.unibe.ch/archive/famoos/Rapi98a/type.pdf

##### JavaScript Type Inference Using Dynamic Analysis
Morten Passow Odgaard
Master thesis
http://cs.au.dk/fileadmin/site_files/cs/Masters_and_diplomas/MortenPassowOdgaard.pdf


##### Dynamic Analysis from the Bottom Up
Markus Mock
https://people.cs.pitt.edu/~mock/papers/woda03.pdf

##### The Concept of Dynamic Analysis
Thomas Ball
http://research.microsoft.com/en-us/um/people/tball/papers/fse-concept.pdf

##### Dynamically discovering likely program invariants to support program evolution
Michael D. Ernst, Jake Cockrell, William G. Griswold, and David Notkin
https://homes.cs.washington.edu/~mernst/pubs/invariants-tse2001.pdf

Synopsis:
Ersnt et al.'s work instruments program to record the values that variables take on in one or more executions. This information is input into an
\invariant detection engine" the checks for a number of invariants, such as that
a variable has a constant value or takes on a small number of values; or that a variables value is bounded by some range, etc. Restated, they discover logical
invariants over a set of program executions, where the types of logical invariants
that can be identifed is another input to the analysis engine

##### Value Profiling and Optimization
Brad Calder, Peter Feller, and Alan Eustace
http://www.jilp.org/vol1/v1paper2.pdf

#### Dynamic Inference of Static Types for Ruby
http://www.cs.umd.edu/~jfoster/papers/popl11.pdf

#### Profile-Guided Static Typing for Dynamic Scripting Languages
https://www.cs.umd.edu/projects/PL/druby/papers/druby-tr-4935.pdf

#### JSTrace: Run-time Type Discovery for JavaScript
http://cs.brown.edu/research/plt/dl/flowtyping/v1/saftoiu-typediscovery-thesis.pdf
