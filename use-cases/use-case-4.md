# Use Case 4: Produce a report on the salary of employees of a given role

**Primary Actor:** HR Advisor
**Scope:** HR System
**Level:** Summary
**Goal in Context:** As an HR advisor I want to produce a report on the salary of employees of a given role so that I can support financial reporting of the organisation.
**Preconditions:** Database contains employee roles and salaries.
**Success Condition:** A report is generated showing all employees of that role and their salaries.
**Failed Condition:** No report is generated, or database connection fails.
**Trigger:** HR Advisor requests the report for a specific role (e.g., "Engineer").
**Main Success Scenario:**
1. HR Advisor requests salary report for a role.
2. System captures role input.
3. System extracts employee data matching that role from the database.
4. System formats data into a readable report.
5. System displays report to HR Advisor.