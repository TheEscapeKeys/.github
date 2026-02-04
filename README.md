# .github
This repository contains organization-wide GitHub configurations that apply to all repositories in the organization.

Issue Templates
All repositories inherit the following issue templates unless they define their own.
  Bug Report: Report a bug or defect
  Change Request: Request a new feature or change
  Research: Research or spike investigation
  Other: General issues that don't fit other categories
  Blank issues are disabled. All issues must use one of the templates above.

Template Locations
.github/
  ISSUE_TEMPLATE/
    bug_report.yml
    change_request.yml
    research.yml
    other.yml
    config.yml
    
Overriding Templates
If a repository needs custom templates, add a .github/ISSUE_TEMPLATE/ folder to that repository. This will override the organization-wide templates entirely (no merging).
Questions

Contact George (george.livingston@theescapegame.com) if you have questions or need changes to these templates.
