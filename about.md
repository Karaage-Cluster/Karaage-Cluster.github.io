---
layout: page
title: About
permalink: /about/
---

Overview
--------

Karaage manages users and projects in a cluster and can store the data in
various backends.

Features
--------
* Can store user information and/or posix account information in LDAP/Active Directory/passwd file.
* Email notifications.
* Auto account creation - Allow project leaders to manage their users.
* Applications work flow - Users can apply for accounts and be approved by project leaders.
* Usage reporting. Report on a per institute, per project or per user for CPU usage.
* Track usage of software and versions. Keep track of what software (and version) and type of jobs a user

Admin access
------------
When an administrator logs into karaage, they can do the following:

* See/modify information about all users/projects/institutes/applications/usage etc.
* Many changes are logged.
* Anything a normal user can.

User access
-----------
When a normal user logs into Karaage (or an administrator), they can do the
following.

Allows users to:

* Modify their own account.
* Change password.
* Manage what projects they are in.

Allow project leaders to:

* Approve/Decline applications to join their project.
* Reset passwords for their members.
* Track their resource utilisation and software utilisation.

Allow institute delegates to:

* Approve/Decline new project applications.
* Manage all projects and users under the institute.

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

Documentation
-------------

* [Karaage 3.x User documentation](http://karaage.readthedocs.org/projects/karaage-user/en/latest/)
* [Karaage 3.x Programmer documentation](http://karaage.readthedocs.org/projects/karaage-programmer/en/latest/)
* [Karaage 3.x Admin documentation](http://karaage.readthedocs.org/en/latest/)

Source code
-----------
Karaage is open source code and available under the GPL3 license.  You can find
the source code for Karaage at
{% include icon-github.html username="Karaage-Cluster" %} /
[karaage](https://github.com/Karaage-Cluster/karaage/)
