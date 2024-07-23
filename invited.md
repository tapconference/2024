---
layout: page
title: Invited Speakers
permalink: /invited-speakers.html
---

# Rosemary Monahan

<p align="center"><img src="/2024/assets/images/rmonahan.jpg" width="500"/></p>

### Title: Formalising Requirements for Systems Verification

### Abstract:

The verification of software systems often relies on a combination of formal methods, testing and simulation based approaches. Knowing what to specify for verification cannot be achieved without clear, unambiguous  descriptions of the system requirements. This makes detailed requirements elicitation and formalisation a crucial step in the process. In this talk, I will share experiences from case studies where we have used NASA's Formal Requirement Elicitation Tool (FRET) to formalise natural language requirements, enabling the use of mathematically-based techniques to guarantee that the system obeys certain properties. These formalised requirements subsequently guide the systems verification using a combination of paradigms, providing for  system-level modelling and verification using model checkers and deductive verifiers. Insights gained during this process are shared, and we explore the expressiveness and the potential interoperability of these approaches. 

Our experience confirms FRET's suitability as a framework for the elicitation and understanding of requirements and for providing traceability from requirements to specification. In addition to providing requirements traceability, we have provided extensions to FRET with adaptations of software code refactoring's for requirements, making requirements more manageable.  We support this in Mu-FRET, a version of FRET which enables refactoring of requirements and proof that the refactored requirements have the same behaviour as the original requirements.

### About Rosemary:

<a href="https://www.maynoothuniversity.ie/faculty-science-engineering/our-people/rosemary-monahan">Rosemary</a> is a Professor in the Department of Computer Science and an affiliate of the Hamilton Institute at Maynooth University. She holds BSc and MSc degrees in Computer Science from UCD and a PhD from DCU.

# Rüdiger Ehlers

<p align="center"><img src="/2024/assets/images/rehlers.png" width="500"/></p>


### Title: Efficient Temporal Logic Runtime Monitoring for Tiny Systems

Abstract: While the theory and practice of runtime monitoring are overall well developed, in embedded systems, runtime monitoring is not as common as one would expect. Especially small-scale embedded systems, which are found in many household devices, are often somewhat safety-critical and could benefit from the possibility to detect software or hardware defects that cannot be uncovered with verification alone. While monitoring frameworks such as RTLola and Copilot are available to address this problem, employing them leads to a gap between verification and runtime monitoring by these frameworks having specialized specification languages for monitoring, and what can be expressed in them is incomparable to the capabilities of the temporal logics traditionally employed in formal verification.

This talk discusses why that is the case and how (linear) temporal logic runtime monitoring for small-scale embedded systems can be made more efficient and attractive to the embedded systems practitioner. This includes identifying why monitoring for traditional temporal logics is somewhat inefficient in software, how this problem can be addressed in a low-cost way, and how runtime monitors can become a more useful component of an embedded system.
By providing a push-button solution for translating a specification to monitor code that also tracks the reason for a specification violation, the overall approach discussed in the talk makes spending developer time on writing a relatively precise specification of a system to build attractive, which also helps paving the way to make up-front verification for small-scale embedded systems more common.

### About Rüdiger:

<a href="https://www.ruediger-ehlers.de">Rüdiger</a> is Professor for Embedded Systems
at Clausthal University of Technology. He is working on making the design process of correct-by-construction computational systems more efficient. 


