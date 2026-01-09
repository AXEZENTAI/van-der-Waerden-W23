# W23 — Certified Finite Verification

This repository contains a complete, finite, and exhaustive certification of the van der Waerden number **W(2,3) = 9**.

## What is certified

The result is established by:

- An explicit 2-coloring of \([8]\) with no monochromatic 3-term arithmetic progression (an avoider), and  
- An exhaustive enumeration of all \(2^9\) two-colorings of \([9]\), showing that no avoiders exist.

Together, these imply:
\[
W(2,3) = 9.
\]

## Scope and intent

This repository is **verification-oriented**.  
It records a fully checkable finite certificate for a known value and makes **no broader claims** beyond this specific result.

## Contents

- `AXEZENT_W23_CERTIFIED.zip`  
  Contains the verifier logic, enumeration data, and supporting artifacts used in the certification.

## Reproducibility

The certification is finite and exhaustive.  
All claims can be independently verified by inspecting or re-running the contents of the provided archive.

## Attribution

Prepared by **Shawn Calvin Snelling**  
Axezent AI Research
