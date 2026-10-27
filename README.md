# CMPUT 301: Lab 8 Participation Exercise

## Student Details
- **Full Name:** Jingchao Yang
- **CCID:** `jingcha2`

## References and Resources
- CMPUT 301 Lab 8 instructions (`lab-08-description.md`).
- CMPUT 301 Lab 8 lecture slides, Michelle Deng, University of Alberta, 2026.
- OpenAI Codex: assistance with implementation, unit tests, and documentation.

## Verbal Collaboration
N/A

## Implementation
- `restoreMana(amount)` adds mana and caps the result at 100.
- `train()` increases spell power by 1 and consumes 5 mana when at least 5 mana is available. Otherwise, both values remain unchanged.
- Unit tests cover mana restoration, successful and unsuccessful training, exactly 5 mana, and zero mana.

## Validation and Submission
Tests and GitHub Actions have not been run for these changes.

From the `lab8` directory on Windows, run:

```powershell
.\gradlew.bat testDebugUnitTest
.\gradlew.bat build --configuration-cache
```

The lab requires a failing GitHub Actions run with the tests and method skeleton committed before implementing `train()`, followed by a passing run after implementation. Final code alone does not demonstrate that TDD process. Complete and verify the required TDD workflow before submitting the repository link on Canvas.
