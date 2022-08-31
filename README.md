PAW datasets from mineralscloud have been generated with a version of atompaw which has problems for the Kresse formulation of PAW:
http://www.mineralscloud.com/resources/repaw/index.shtml

With the latest release of atompaw (>4.2) the input files for La/Ce can't be used to generate UPF files anymore due to warnings about negative density. This repo contains jupyter notebooks to run a bisection search and find a valid rc_core radius.
