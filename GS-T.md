---
title: <GS title>
Created: <date created on,(mm-dd-yyyy) format>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets)
discussions-to: <URL>
status: <Draft>
type: <To be assigned by review team, leave empty>
requires (*optional): <GS number(s)>
replaces (*optional): <GS number(s)>
---  

This is the suggested template for new GSs.

Note that an GS type will be assigned by the reviewing editor. When opening a pull request to submit your Galactic Standard proposal, please use an abbreviated title in the filename, `GS-draft_title_abbrev.md`.

The title should be 44 characters or less.

## Simple Summary

Provide a simplified and layman-accessible explanation of the Galactic Standard proposed.

## Abstract
A short description of the network issue being addressed.

## Motivation

Should clearly explain why the existing protocol specification is inadequate or why a new protocol specificatioon is needed to solve a specific problem.

## Specification
  
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Ethereum or Cosmos platforms.

## Rationale

The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

## Backwards Compatibility

All GSs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The GS must explain how the author proposes to deal with these incompatibilities. GS submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases

Test cases for an implementation are mandatory for GSs that are affecting consensus changes. Other GSs can choose to include links to test cases if applicable.

## Implementation

The implementations must be completed before any GS is given status "Final", but it need not be completed before the GS is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.
