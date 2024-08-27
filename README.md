# rhis-builder-day-2-ops

This is a set of playbooks, roles, etc.. that are useful in managing a Red Hat Infrastructure Standard implementation on Day N. You will find many of these roles used in the rhis-builder-pipeline code.

Each role has a README.md file that describes what it does. There are sample configurations for the role usages in the group_vars and host_vars directories. 
e.g. To synchronize your private automation hub repositories. Look at the data in the host_vars directory. Set up and automation_hubs group in your inventory and call the ah_repositories_sync role to your automation hubs. 
