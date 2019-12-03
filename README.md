[![Linux CI](https://github.com/mosteo/Ada_CI_Workflows/workflows/CI%20Linux/badge.svg)](https://github.com/mosteo/Ada_CI_Workflows/actions)
[![Windows CI](https://github.com/mosteo/Ada_CI_Workflows/workflows/CI%20Windows/badge.svg)](https://github.com/mosteo/Ada_CI_Workflows/actions)

# Ada CI Workflows
Ready-to-use workflows to add Continuous Integration to Ada projects

## Instructions
1. Copy the .github folder to your own repository. 
1. Edit the `ci-*.yml` files therein to adjust the name of you project file and test executable.

## Notes
- The Windows workflow uses the latest GNAT Community Edition on Windows 10.
- The Linux workflow tests the following combinations:
   - Native GNAT in Ubuntu LTS.
   - Native GNAT in Debian Stable.
   - Latest GNAT Community Edition on Ubuntu LTS.
   - Latest GNAT Community Edition on CentOS.
