What is this?
=

A C program to place ShellCode in an environment variable.


WHAT?
=
As part of the level 6 of the IO challenge from [SmashTheStack](http://smashthestack.org/) it is required to exploit environment variables. This small C program puts the hardcoded ShellCode into the environment variable $EGG.

The code is inspired from the mighty <http://www.phrack.org/issues.html?issue=49&id=14&mode=txt>

Run it
=

1. gcc -Wall -o /tmp/exploit\_env /tmp/exploit_env.c
1. /tmp/exploit_env

Improve it
=

- Parametrize shell code
- Parametrize environment variable
