# Self-Service Proof of Insurance – AI-Boosted Modeling Demo

## Business context

We are working with Hiscox Retail (UK).  
Currently, many customers call support to request a Proof of Insurance document for their active policy.

We want to design a small, self-service capability:

- The customer logs into the existing retail portal.
- They select one of their active policies.
- They request a Proof of Insurance.
- The system generates a PDF and:
  - sends it via email, and/or
  - allows download in the portal.

This demo shows how we move **from words to structure** using an LLM:
- Socratic clarification of the requirement,
- generation of diagrams,
- creation of a PRD,
- creation of `agents.md` for AI developer agents.

## Initial feature description (intentionally incomplete)

> “A customer wants to request a Proof of Insurance document for an active policy.  
> They log in, choose a policy, and receive a PDF by email or download.”

The goal of the session is to refine this description and turn it into:
- a sequence diagram,
- an architecture (C4 Container) view,
- a Product Requirements Document (PRD),
- an `agents.md` specification.
