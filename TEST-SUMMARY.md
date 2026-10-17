# SauceDemo Manual QA — Test Summary

**Application:** https://www.saucedemo.com/  
**Scope:** Login, catalogue, sorting, cart, checkout, order completion, logout, and a project-defined login timing check.

## Current recorded results

- **24 test cases** in the test-case workbook.
- **22 PASS**.
- **1 FAIL — known seeded behavior:** `problem_user` shows product-image problems; this is an intentional demo-account behavior and is not counted as a confirmed unexpected product defect.
- **1 NOT VERIFIED:** the response-time check for `performance_glitch_user` has no recorded elapsed-time measurement in the supplied evidence. Re-run before assigning PASS/FAIL.
- **Confirmed unexpected defects supported by this package: 0.**

## Evidence and limitations

Screenshots are supplied for locked-user login, the product-image behavior, and checkout overview. No timing measurement was supplied. The execution environment (OS, browser/version, and execution date) still needs to be recorded from an actual run. Do not claim retesting or regression completion without execution records.

## Important classification note

SauceDemo's special accounts are designed to demonstrate different behaviors. Findings observed only with `problem_user` or `performance_glitch_user` should be described as seeded demo-account behavior unless independently shown to be an unexpected defect. The 2-second response-time threshold is a project-defined criterion, not an official SauceDemo SLA.
