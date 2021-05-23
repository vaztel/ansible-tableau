# infraAsCode

## Introduction
This project uses ansible to install Tableau on several OS.

## How to

><code>ansible-playbook tableauFactory.yml -e "variable_host=instance1"</code>

tableauFactory.yml contains the call to all the appropriate playbooks/roles that are included in the profile of a tableau server

-e : serves to pass an extra variable which can be called in the code during execution. Here we provide the list of machine we want to execute the playbook on.
