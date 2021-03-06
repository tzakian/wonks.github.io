--- 
layout:  post 
title:   "Verifying Hybrid Systems with Automated Theorem Provers"
authors: "Sarah Loos" 
date:    2014-04-25 04:15:00 
categories: Loos Spring2014
--- 
## Abstract

Formal verification and theorem proving have been used successfully in many
discrete applications, such as chip design and verification.  However,
computation is not confined to the discrete world of desktop computing.
Increasingly, we depend on discrete software to control safety-critical
components of continuous physical systems (for example, adaptive cruise control
in cars and collision avoidance in aircraft).  It is vital that these hybrid
(discrete and continuous) systems behave as designed, or they will cause more
damage than they intend to fix.  In this talk, I will present several challenges
associated with verifying hybrid systems and how we can usedifferential dynamic
logic and its proof calculus to ensure safety for hybrid systems under a
continuously infinite range of circumstances. 

In addition to covering the theoretical foundations for deductive verification
of hybrid systems, I will discuss some of the practical uses of our verification
tools: KeYmaera and KeYmaeraD. These tools have been used to verify a class of
distributed collision avoidance controllers designed to work in environments
with arbitrarily many aircraft. We prove that the controllers never allow the
aircraft to get too close to one another, even when new planes approach an
in-progress avoidance maneuver that the new plane may not be aware of. Because
these safety guarantees always hold, the aircraft are protected against
unexpected emergent behavior, which simulation and testing may miss.

