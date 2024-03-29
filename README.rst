===================================
Community Planning and Coordination
===================================

****************************
List of OpenSDN repositories
****************************

1. https://github.com/OpenSDN-io/community repository is used to coordinate
the community and the project. This repository is used primarily for:

* issues submission https://github.com/OpenSDN-io/community/issues ;

* community discussions: https://github.com/OpenSDN-io/discussions .

2. https://github.com/OpenSDN-io/docs repository stores the documentation for
the project.

3. https://github.com/OpenSDN-io/tf-vrouter stores the data plane components of
OpenSDN (vRouter Forwarder module), namely: a) a kernel module (vrouter.ko)
and b) a DPDK application for forwarding packages between interfaces.

4. https://github.com/OpenSDN-io/tf-controller stores the control plane
components of OpenSDN, such as:

* OpenSDN Controller that stores RIB information;

* OpenSDN vRouter Agent that programmes vRouter Forwarder (converts RIB
    into FIB);

* OpenSDN Config that manages high-level network configurations;

* and other components and modules.

5. https://github.com/OpenSDN-io/tf-dev-env repository is used to initialize
development environment of OpenSDN: a container to compile all components 
and modules of the project and to build the corresponding RPM packages.

