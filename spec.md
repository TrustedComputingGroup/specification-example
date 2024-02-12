---
title: "Document Title"
type: SPECIFICATION
...

---

# Disclaimers, Notices, and License Terms

THIS SPECIFICATION IS PROVIDED "AS IS" WITH NO WARRANTIES WHATSOEVER, INCLUDING
ANY WARRANTY OF MERCHANTABILITY, NONINFRINGEMENT, FITNESS FOR ANY PARTICULAR
PURPOSE, OR ANY WARRANTY OTHERWISE ARISING OUT OF ANY PROPOSAL, SPECIFICATION OR
SAMPLE.

Without limitation, TCG disclaims all liability, including liability for
infringement of any proprietary rights, relating to use of information in this
specification and to the implementation of this specification, and TCG disclaims
all liability for cost of procurement of substitute goods or services, lost
profits, loss of use, loss of data or any incidental, consequential, direct,
indirect, or special damages, whether under contract, tort, warranty or
otherwise, arising in any way out of use or reliance upon this specification or
any information herein.

This document is copyrighted by Trusted Computing Group (TCG), and no license,
express or implied, is granted herein other than as follows: You may not copy or
reproduce the document or distribute it to others without written permission
from TCG, except that you may freely do so for the purposes of (a) examining or
implementing TCG specifications or (b) developing, testing, or promoting
information technology standards and best practices, so long as you distribute
the document with these disclaimers, notices, and license terms.

Contact the Trusted Computing Group at www.trustedcomputinggroup.org for
information on specification licensing through membership agreements.

Any marks and brands contained herein are the property of their respective
owners.

---

# Change History

--------------------------------------------------------------------------------
**Version** **Date**   **Description**
----------- ---------- ---------------------------------------------------------
0.1         2024/01/29 Initial draft
--------------------------------------------------------------------------------

# Document Style

**Key Words**

The key words "MUST," "MUST NOT," "REQUIRED," "SHALL," "SHALL NOT," "SHOULD,"
"SHOULD NOT," "RECOMMENDED," "MAY," and "OPTIONAL" in this document's normative
statements are to be interpreted as described in
[RFC 2119: Key words for use in RFCs to Indicate Requirement Levels](https://www.ietf.org/rfc/rfc2119.txt).

**Statement Type**

Please note an important distinction between different sections of text
throughout this document. There are two distinctive kinds of text: _informative
comments_ and _normative statements_. Because most of the text in this
specification will be of the kind _normative statements_, the authors have
informally defined it as the default and, as such, have specifically called out
text of the kind _informative comment_. They have done this by flagging the
beginning and end of each informative comment and highlighting its text in gray.
This means that unless text is specifically marked as of the kind _informative
comment_, it can be considered a _normative statement_.

EXAMPLE:

::: Informative ::::
Reach out to <admin@trustedcomputinggroup> with any questions about this document.
::::::::::::::::::::

---

\tableofcontents

\listoffigures

\listoftables

---

# Checklist for users of this template

* Ensure the repository is set to private
* Add the correct GitHub team(s) to Collaborators
* Add TCGadmin to Admin
* Add a branch protection rule on `main`
  * Require a pull request before merging
  * Require approvals
  * Do not allow bypassing the above settings
  * (Optional) Require review from Code Owners (Requires setting up CODEOWNERS file)
* (Optional) rename spec.md and update all references in `actions.yml`
* Check for newer [pandoc](https://github.com/trustedcomputinggroup/pandoc) and
  [markdown](https://github.com/trustedcomputinggroup/markdown) action versions
  for `actions.yml`
* Update the document title and type in the YAML front matter
* (Optional) Do an initial release to set baseline version (e.g., if migrating
  from an existing Word doc).
* (Optional) Review the guidance about release naming in the latest User's
  Guide from <https://github.com/trustedcomputinggroup/pandoc>.