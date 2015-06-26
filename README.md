## aws-codedeploy-scripts

This repository includes a set of re-useable scripts, that are meant to be
used in conjunction with AWS CodeDeploy. These scripts can be included in a
project as a git submodule for example.

### Usage

These scripts expect a 'aws_codedeploy_variables.sh' file to be available at the project root, which they will source.
In addition, you will need an appspec.yml AWS CodeDeploy manifest file pointing to the appropriate scripts.

See the [examples/](examples/) sub-directory for example appspec.yml and aws_codedeploy_variables.sh files in various common usage scenarios.

### Contribute

**Find this project useful?** Help us make it even better by submitting any bugs or improvement suggestions you have
as GitHub Issues and Pull Requests.

**Like what we're doing?** There's much more AWS and Node.js goodness where this came from! drop us a line if you wanna chat about potential career opportunities at [Globality](http://www.globality.com): careers at globality dot com
