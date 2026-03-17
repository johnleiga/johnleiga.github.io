# Aerospace Pressure Transducer Redesign

A first-principles redesign of a high-reliability aerospace pressure transducer to preserve a major program under aggressive cost constraints.

## Overview

At Tavis Corporation, I worked on high-reliability pressure transducers used in demanding aerospace environments including launch vehicle propulsion systems, satellite propellant tanks, and cryogenic fuel applications. These products had to operate under severe shock and vibration, extreme temperatures, and challenging pressure ranges while maintaining measurement accuracy.

One program faced a serious commercial risk: the customer required an approximately 30% cost reduction, and the existing architecture was too expensive to remain competitive on a contract worth more than $40M. The original design used a secondary reference pressure gage along with a specialized electronics package that cost roughly 3x more than the standard alternative.

Rather than treating the problem as a pure cost-cut exercise, I approached it as a mechanical design problem.

## The Problem

The existing transducer architecture depended on a built-in reference pressure correction approach that added both hardware complexity and electronics cost. That made the product difficult to discount far enough to meet customer expectations without destroying margin.

A straightforward option would have been to remove the correction feature and compensate elsewhere, but that would have pushed the problem downstream without solving the underlying source of error. I wanted to understand whether the reference pressure error itself could be reduced enough through geometry and structural behavior to eliminate the extra hardware entirely.

## My Approach

I used a first-principles analysis of the sensing structure to identify the likely sources of reference pressure error. From there, I redesigned the diaphragm and gage geometry so the structure operated in a more favorable way mechanically.

The key design move was changing the direction of deflection so the structural elements were working primarily in compression rather than expansion. That reduced the underlying error mechanism enough to make the secondary reference correction gage unnecessary.

This redesign also enabled the use of a lower-cost standard electronics architecture instead of the more specialized package used in the original design. Along the way, I incorporated features that also improved assembly efficiency and reduced the mechanical cost of the gage components.

## Engineering Work Performed

I owned the mechanical design work needed to turn the concept into real hardware, including:

- 3D design and full assemblies in SolidWorks
- Structural analysis and FEA
- GD&T drawing package creation
- Tolerance considerations affecting diaphragm motion and sensor gap
- Prototype build and validation testing on the most difficult pressure ranges

This was not just a paper study. I selected the two hardest pressure ranges to build, assembled prototypes, and tested them to confirm that the new design reduced the reference pressure error to well below the acceptable limit while still meeting the original product requirements.

## Result

The redesign achieved the business objective without compromising the technical objective:

- Preserved competitiveness on a program worth more than **$40M**
- Enabled approximately **30% system cost reduction**
- Reduced mechanical gage component cost by approximately **50%**
- Eliminated the secondary reference pressure gage
- Enabled use of lower-cost standard electronics
- Validated performance through prototype build and test

## Why This Project Matters

I like this project because it captures the kind of engineering work I enjoy most: combining first-principles reasoning, mechanical design, cost awareness, and hands-on validation to solve a problem that mattered both technically and commercially.

This was not a bracket-design exercise. It was a case where the mechanical architecture itself was the lever that made the program viable.

## Related Work

On the same family of products, I also developed a numerical diaphragm modeling tool for cases where legacy internal tools did not capture mechanical nonlinearity and standard FEA struggled with pre-stressed geometries. The tool predicted diaphragm deflection and linearity behavior, included magnetic sensor-gap effects, and was validated through manufacturing testing.

---

## Optional Figures To Add Later

If I expand this page, I would add:

1. A simplified cross-section sketch of the original architecture vs. redesign  
2. A diagram showing the shift from expansion-dominant to compression-dominant behavior  
3. A simple validation table showing target vs. prototype performance  
4. A short “design tradeoffs” section on cost, manufacturability, and accuracy