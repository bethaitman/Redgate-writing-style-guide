##Release notes
Our release notes have been wildly inconsistent over the years. Here's our recommended format, with an example afterwards:

###Features
* Exclude words like "you can..." For example, don't write: "You can now change the number of items shown in the History dialog". Instead, write: "Change the number of items shown in the History dialog".

* List new features (and enhancements, performance improvements etc) in the release as bullet points, without full stops.

* List the features approximately in order of importance. If there's one major new feature, put it before smaller ones.

* Link to relevant documentation where appropriate (eg a page describing the feature in more detail). 

* If a feature involves changes to the UI, consider including a screenshot. This is good advertising; everyone likes a new UI.

###Fixes
* Use terms such as "now" and "no longer" to clarify that you're describing how the tool behaves in this release. Otherwise, it may sound as if you're describing the bug, not the fix. For example, don't write "Materialized views script hidden fields", as it's not clear if that's what used to happen, or what happens now. Instead, describe what the fix has changed; eg write "Materialized views no longer script hidden fields", or "Materialized views now script hidden fields", depending on what's changed.

* If the bug has a Jira reference (eg SB-5415), include it at the start of each bullet point, followed by a colon. If the same issue has multiple bug codes, include them all in the same bullet point.

* List the fixes in numerical order according to the bug code.

* If the fixes have relevant documentation, link to it.

###Known issues
* If the release introduces new issues or bugs, list them.

* If the issues have bug numbers, list them.

* Link to any relevant resources.

###Example release notes

####Features

* Upload backup copies to a SQL Backup Pro Hosted Storage account
* Manage offsite backups from the SQL Backup Pro Hosted Storage website
* View results of copying backups to hosted storage or a network location from the Activity History and Backup Properties

####Fixes

* SB-5415: When installing the server components with the /Log switch, account passwords are no longer recorded in plain text in the log
* SB-5446: The SQL Backup server components installer now checks that the user is a member of the SQL Server sysadmin role before attempting the installation

####Known issues

* SQL Backup Pro doesn't support installation on Windows Server 2012 with Failover Clustering. For more information, see Installing

---

##Usage reports
[ ] Send anonymous usage statistics and error reports to Redgate

We use these statistics to improve our tools.