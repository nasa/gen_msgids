# Core Flight System : Framework : Tool : Generate Message Ids

This repository contains NASA's Generate Message Ids Tool (gen_msgids), which is a framework component of the Core Flight System.

This lab application is a ground utility to Generate Message Ids used by cFE for cFS. It is intended to be located in the `tools/gen_msgids` subdirectory of a cFS Mission Tree.  The Core Flight System is bundled at https://github.com/nasa/cFS (which includes this tool as a submodule), which includes build and execution instructions.

## Release Notes

gen_msgids version 1.0a is released as part of cFE 6.6.0a under the Apache 2.0 license, see [LICENSE](LICENSE-18128-Apache-2_0.pdf).

## Known issues

This ground utility has not been updated to use the cmake framework.  The include path defined in Makefile will likely need to be updated for distributions.

## Getting Help

The cFS community page http://coreflightsystem.org should be your first stop for getting help. Please post questions to http://coreflightsystem.org/questions/. There is also a forum at http://coreflightsystem.org/forums/ for more general discussions.

Official cFS page: http://cfs.gsfc.nasa.gov

