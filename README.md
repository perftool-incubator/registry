# registry
A source-of-truth for variables, configurations, etc, for many crucible suboprojects.
This project only provides the information but not the methods to access this information.

Methods to access are:
- Have your script read the JSON file directly
- Use a library found in the toolbox subproject
- Use JQ

Location of registry information:
- When incorporated into the crucible project, a registry-crucible.json is located in a path defined by $CRUCIBLE_REGISTRY, and this variable should be defined in /etc/sysconfig/crucible.
  $CRUCIBLE_REGISTRY is typically defined as $CRUCIBLE_HOME/subprojects/registry/registry-crucible.json
