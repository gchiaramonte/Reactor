# Introduction

Reactor is a domain specific language (DSL) for modeling both insurance and reinsurance contracts. Inspired by the paper, "Composing Contracts, an adventure in financial engineering," by Simon Peyton Jones, Jean-Marc Eber and Julian Seward. I have extended their work to the domain of re/insurance contracts. 

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
Attachment
AggregateLimit
Reinstatement
```

# Support

Twitter: [@waahhoo](https://twitter.com/waahhoo)  
Linked-In: [Gene Chiaramonte](https://www.linkedin.com/in/gene-chiaramonte-8a153a55/)

# Contribute

# License

GNU GENERAL PUBLIC LICENSE - Version 3, 29 June 2007
