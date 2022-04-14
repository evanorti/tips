# Terra Improvement Proposal (TIP) Example

The following example is not a real TIP and for education purposes only. None of the info in this document applies to any real protocol change. 

# New credit module (TIP 01)

**TIP number**: 01
<br>
**Author**: Satoshi
<br>
**Network**: Magellan-7 <!---Add the mainnet version this change will apply to. -->
<br>
**Date**: 25 December 2090
<br>

## Summary

<!--- A 1-2 sentence non-technical explanation of the change. Summaries should be easily understood by the general community. -->

Credit logic will be moved to its own module.


## Motivation

<!--- An explanation of why the change is necessary. What is the problem that needs to be solved? Why do these changes need to be implemented? -->

The loan module is being depracated, but credit is still needed for the protocol to function properly. The credit logic needs to be moved to it's own module.

## Tech Spec

**Modules:** <!--- List affected modules with short notes on alterations. --> 

- Loan: module depracated.
- Market: credit determination logic derives from the market module.
- Credit: module created.

### Overview

<!---A technical summary of the change and how it will solve the problem. --> 

The Loan module will be depracated due to it's mostly vestigil code. A new module will be created called the Credit module. This module will house all logic for credit swaps made between Credit-coins. The Credit module structure will be based off of the market modules determination logic.

Let `n = 1` 

### Rationale

<!--- Why are you doing it this way and not another way? What is the reasoning for using this method vs another route? -->
No other module can logically house the credit logic, so a new module needs to be made. 

### Method

<!--- An outline of how the change will be implemented. This can include a numbered list of steps necessary for completion. -->

1. 
2. 
3. 

### Code

<!--- Include any applicable code blocks or pseudocode describing the changes. -->

### Considerations

<!--- Describe any special or general considerations. Is there anything that we should be cautious about? Are there any invariants to keep in mind? -->

## Outcome

<!--- Briefly describe the desired outcome of this change. -->

## Timeline

<!--- If applicable, include an estimated project completion time. You can break this up into a list of events. -->

## Test cases

<!--- If applicable, include any test cases or preliminary research related to the change. -->