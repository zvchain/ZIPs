---
zip: <to be assigned>
title: <ZIP title>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: <URL>
status: <Draft | Last Call | Accepted | Final | Deferred>
type: <Standards Track (Core, Networking, API, ZRC) | Informational>
category (*only required for Standard Track): <Core | Networking | ZRC | API >
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires (*optional): <ZIP number(s)>
replaces (*optional): <ZIP number(s)>
---  

This is the suggested template for new ZIPs.

Note that an ZIP number will be assigned by an editor. When opening a pull request to submit your ZIP, please use an abbreviated title in the filename.

The title should be 44 characters or less.

## Simple Summary 

Provide a simplified explanation of the ZIP.

## Abstract 

A short (~200 word) description of the technical issue being addressed.

## Motivation 

The motivation is critical for ZIPs that want to change the ZV Chain protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the ZIP solves. ZIP submissions without sufficient motivation may be rejected outright.

## Specification 

The technical specification should describe the syntax and semantics of any new feature. 

## Rationale 

The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

## Backwards Compatibility 

All ZIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The ZIP must explain how the author proposes to deal with these incompatibilities. ZIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases 

Test cases for an implementation are mandatory for ZIPs that are affecting consensus changes. Other ZIPs can choose to include links to test cases if applicable.

## Implementation 

The implementations must be completed before any ZIP is given status "Final", but it need not be completed before the ZIP is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.