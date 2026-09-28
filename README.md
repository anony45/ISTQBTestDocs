# PrestaShop Demo - Test Case Design & Bidirectional Traceability

## System Under Test
PrestaShop Demo: https://demo.prestashop.com/

## Objective
Design test cases that verify the main customer-facing functions of the PrestaShop demo storefront and map those test cases bidirectionally to the defined requirements.

## Deliverables
- Test environment and setup
- 20 defined requirements / acceptance criteria
- 25 detailed test cases
- Step-by-step test procedures
- Test data and expected results
- Actual result and execution status fields
- Bidirectional traceability matrix:
  - Requirement -> Test Case
  - Test Case -> Requirement

## Workbook Structure
1. **Summary** - high-level overview of the submission.
2. **Test Setup** - environment, browsers, OS, network, security and test data.
3. **Test Cases** - detailed test cases with steps and expected results.
4. **Requirements** - requirements and acceptance criteria used for traceability.
5. **Bidirectional Matrix** - two-way requirement-to-test mapping.

## Test Execution Status
The test cases are initially marked **Not Run**. During execution, update the **Actual Result** and **Status** fields using:
- Not Run
- Pass
- Fail
- Blocked

## Suggested GitHub Structure
```text
ISTQBTestDocs/
|-- README.md
`-- docs/
    `-- PrestaShop_Test_Cases_Bidirectional_Matrix.xlsx
```

## Suggested Git Commands
```bash
git checkout docs-branch
mkdir -p docs
# Copy the workbook into the docs folder.
git add README.md docs/PrestaShop_Test_Cases_Bidirectional_Matrix.xlsx
git commit -m "Add PrestaShop test cases and bidirectional traceability matrix"
git push -u origin docs-branch
```

## Notes
The test design includes positive, negative, data-integrity, compatibility, responsive, performance and basic transport-security coverage. Actual execution results should be completed against the live demo environment.
