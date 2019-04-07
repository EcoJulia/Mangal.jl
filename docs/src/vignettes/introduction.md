# Introduction to `Mangal.jl`

The goal of this vignette is to explain the core design principles of the
**Mangal** package.

````julia
using Mangal
````





## Types

The package exposes resources from the <mangal.io> database in a series of
types, whose fields are all documented in the manual. 

## A note on speed

## Queries

*Almost* all functions in the package accept query arguments, which are simply
*given as a series of pairs.