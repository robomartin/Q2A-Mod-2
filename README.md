No Plain-Text Passwords on Welcome Message
==========================================================

This code is intended for Question2Answer 1.5.3
http://www.question2answer.org/

The patch will prevent a plain-text password from being sent to a newly registered user in the welcome message.  


Installation
------------------------------------------------------------

Simply install over your existing Question2Answer installation.

This can be done any time after having installed Question2Answer.

The following files are affected:

```
MODIFIED
<site-root>/qa-include/qa-app-users-edit.php
```
