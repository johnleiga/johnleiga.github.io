# Industrial Furnace System Optimization

A mechanical and controls-focused redesign of a multi-furnace industrial process to improve stability, eliminate startup waste, and increase operational reliability.

## Overview

At Nestlé Purina, I worked on a perlite expansion system made up of 14 furnaces operating under a custom process-control architecture. The system had recurring instability issues, waste during startup, and mechanical bottlenecks that affected reliability and throughput.

This project stands out to me because it was a real production problem with immediate operational consequences. The work required a combination of mechanical troubleshooting, process analysis, controls thinking, and practical implementation in an active manufacturing environment.

## The Problem

The system was not consistently operating in a stable, repeatable way. Performance losses showed up in multiple forms:

- process instability
- waste during startup
- shutdown events caused by upstream/downstream interactions
- heavy dependence on manual intervention

To improve the system in a meaningful way, I needed to understand both the mechanical and process-control sides of the problem rather than treating them separately.

## My Approach

I started by creating better visibility into the process. That included installing process sampling points so performance could be evaluated with real operating data instead of assumptions. Once the process behavior was better understood, I worked through the system to isolate the main drivers of instability and waste.

From there, the work focused on two major areas:

### 1. Stabilizing the Running Process

I evaluated how the furnaces were interacting with the surrounding feed and control systems and tuned multiple control loops in the correct sequence to improve overall system behavior.

I also implemented a density-based feedback strategy so furnace temperature could be adjusted based on finished-product density rather than relying only on fixed settings and manual checks. This improved consistency and reduced the need for hourly manual sampling.

At the same time, I identified an undersized rotary airlock as a mechanical bottleneck. That component was creating backpressure and contributing to system shutdowns. Finding that root cause was important because it showed that part of the instability was mechanical, not just controls-related.

### 2. Eliminating Startup Waste

A separate issue was material loss during startup. The process was wasting product every time the system initialized because startup conditions were not aligned with how the system actually behaved.

To solve that, I designed an automated startup sequence from the ground up. This included:

- running density-testing experiments
- determining the correct startup parameters
- developing startup logic that could be implemented in the control system

The result was a zero-waste startup protocol that removed a recurring source of loss from normal operations.

## Engineering Work Performed

My contribution included both analysis and implementation work, including:

- process sampling and empirical data collection
- mechanical root-cause analysis
- process-control tuning and sequencing
- development of density-based control logic
- identification of mechanical constraints affecting system behavior
- startup testing and parameter development
- implementation support for automated startup logic
- documentation of the optimized configuration for reuse

I also scoped and executed approximately $500K in equipment upgrades related to feed-system temperature control, including coordination with vendors, contractors, installation teams, and commissioning activities.

## Result

The project produced measurable improvements in both process performance and operating cost:

- Stabilized performance across a 14-furnace expansion system
- Identified and addressed a key mechanical bottleneck causing shutdown events
- Reduced manual intervention through improved feedback control
- Eliminated startup material loss through an automated startup sequence
- Delivered approximately **$200K in annual savings**
- Received an internal engineering award and bonus for the work

## Why This Project Matters

I like this project because it reflects the type of engineering work I enjoy most: solving real problems in live systems where the answer is not contained within a single discipline.

This was not purely a controls problem and it was not purely a mechanical problem. The value came from understanding the full system, identifying what was actually driving poor performance, and implementing changes that held up in production.

It also reinforced something I care about in engineering: the best solutions are usually the ones that improve technical performance and operational usability at the same time.

## Key Takeaways

This project strengthened my ability to:

- troubleshoot complex mechanical systems in production environments
- connect physical system behavior to process performance
- work across mechanical and controls boundaries
- implement changes that produce measurable operational impact
- move from observation to root cause to permanent corrective action
