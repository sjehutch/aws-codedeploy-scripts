## aws-codedeploy-scripts

This repository includes a set of re-useable scripts, that are ment to be
used in conjunction with AWS CodeDeploy. These scripts can be included in a
project as a git submodule for example. They expect a 'aws-codedeploy-vars.sh' file
to be available at the project root, which they will source.

See the `examples/` sub-directory for example appspec.yml and aws_codedeploy_variables.sh files for use with these scripts
in various common scenarios
