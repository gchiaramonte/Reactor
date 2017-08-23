# Introduction

Reactor.DSL is a domain specific language (DSL) for modeling both insurance and reinsurance contracts. Inspired by the paper, "Composing Contracts, an adventure in financial engineering," by Simon Peyton Jones, Jean-Marc Eber and Julian Seward. I have extended their work to the domain of re/insurance contracts. 

Contracts in the re/insurance domain have unique terms such as limits, attachments aggregate limits, franchise deductibles and reinstatements. These terms are combined to create all sorts of contracts such as quota shares, excess of loss, annual aggregates, industry loss warranty triggers, corroridors, reverse corridors. Also, given the ability of re/insurance contract terms to change state in respones to an event during it's lifetime, the method of evaluation needs to capture the changing contract state through time.

# Features

# Examples

## Contract Primitives

```
Zero
One
Scale
And 
Or
Cond 
When 
Anytime
Until
Limit
Attach
AggLimit
AggAttach
Reinstatement
```

# Observables

Observables are functions that represent time varying values. Then can represent real world values such as the high temperature on a give day or they can be used to model unknow valus such as hurricane or earthquake losses. 

# Lifting Functions

Ordinary functions can be lifted to work with observable values. For example, if you wanted to take the maximum rainfall across a set of locations you would lift the function Max to work with the rainfall observabations. Another example would be taking the sum of losses to properties from a natural catastrophe, in which case you would lift the function Sum to total the ovservable losses in a portfolio of homeowners policies.

# Support

Twitter: [@waahhoo](https://twitter.com/waahhoo)  
Linked-In: [Gene Chiaramonte](https://www.linkedin.com/in/gene-chiaramonte-8a153a55/)

# Contribute

# License

GNU GENERAL PUBLIC LICENSE - Version 3, 29 June 2007
