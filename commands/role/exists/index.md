---
layout: default
title: 'wp role exists'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [role](/commands/role/) &raquo; exists</small>

`wp role exists` - Check if a role exists.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Arole-exists+sort%3Aupdated-desc">Github issues</a></small>

<hr />

##DESCRIPTION

Will exit with status 0 if the role exists, 1 if it does not.

### OPTIONS

&lt;role-key&gt;
: The internal name of the role.

### EXAMPLES

    $ wp role exists editor
    Success: Role with ID editor exists.



