# Repository Guidelines for Ventech CMS

**What code belongs here?**

*  Source code that was created by Ventech as part of the CMS HCQIS contract.
  * This is probably *NOT* the location for official deliverables.
  * This is probably  *NOT* the location for day-to-day scripts.
  * This *IS* the place for those rare scripts or programs that would be useful to others.
* 3rd party libraries may be included but must be properly licensed.
* Files cannot include any Personal Health Information (PHI) or Personally Identifiable Information (PII).
  * However, developers may include their own PII, such as name and email address.
* Files cannot contain any information that identifies anything specific to a Government information system, computer, or network.
  * For example, there should be no server names, IP addresses, user names, passwords, etc.
  * That information should be configurable anyway, not hard-coded.

**What should each project include?**

* Each project should include a README file with the following information:
    1. The status and version of the software.
    2. A short description of the software.
    3. An OSI-approved license, see https://opensource.org/licenses
    4. Any documentation required to create and use the software.

**How is code released?**

* Create a personal GitHub account and ask the admin for an invitation to join the team.
* Everything should be done through the GitHub repository - code, issues, and documentation should all live in the repository. This is not merely a code dump.
* New projects require a code review from another team member.
  * The code review is only meant to verify that the above steps were followed and that there are no security or privacy concerns.
  * After the code review is done, the reviewer should add a line to the file code_reviews.txt.

For more information about Open Source Software, see https://sourcecode.cio.gov/
