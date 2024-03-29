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

6. https://github.com/OpenSDN-io/tf-common stores common code and library
for Controller and Analytics components of OpenSDN technology.

7. https://github.com/OpenSDN-io/tf-container-builder is used to create
containers for microservices.

8. https://github.com/OpenSDN-io/tf-devstack is a tool for deployment
of OpenSDN from published containers or building and deploying from sources.

9. https://github.com/OpenSDN-io/tf-ansible-deployer keeps a set of playbooks
to install OpenSDN as the microservices architecture.

10. https://github.com/OpenSDN-io/doxygen-docs is a storage for the doxgen
documentation generated from the Controller source code.

11. https://github.com/OpenSDN-io/tf-kolla-ansible contains Kolla-Ansible scripts
for deploying ???

12. https://github.com/OpenSDN-io/tf-packages provides spec files for
RPM packages generation of OpenSDN components and modules.

13. https://github.com/OpenSDN-io/tf-analytics stores the source code of
OpenSDN Analytics component.

14. https://github.com/OpenSDN-io/tf-jenkins stores configuration files
and scripts for OpenSDN CI/CD (https://gerrit.opensdn.io/) using
Jenkins (https://www.jenkins.io/).

15. https://github.com/OpenSDN-io/tf-vnc ??? is empty repository

16. https://github.com/OpenSDN-io/tf-charms stores configuration files for
Juju charms for OpenSDN services.

17. https://github.com/OpenSDN-io/tf-nova-vif-driver stores the source code
of OpenStack Nova VIF driver for OpenSDN.

18. https://github.com/OpenSDN-io/tf-test repository contains the test code
for validating the OpenSDN infrastructure.

19. https://github.com/OpenSDN-io/tf-third-party contains a list of packages
required to build the OpenSDN Virtual Network Controller.

20. https://github.com/OpenSDN-io/tf-web-controller contains front end
Web UI code for the management of OpenSDN network virtualization solution.

21. https://github.com/OpenSDN-io/tf-webui-third-party stores patches for
the third party libraries used in tf-web-controller of OpenSDN.

22. https://github.com/OpenSDN-io/tf-helm-deployer  consists of OpenSDN helm
charts which helps to deploy OpenSDN networking components as microservices.

23. https://github.com/OpenSDN-io/tf-neutron-plugin provides OpenStack Neutron
plugin for OpenSDN.

24. https://github.com/OpenSDN-io/tf-heat-plugin provides OpenSDN heat plugin ???.

25. https://github.com/OpenSDN-io/tf-dev-test is a development tool for 
testing OpenSDN deployments by means of various test suites and methods.

26. https://github.com/OpenSDN-io/tf-deployment-test contains to run deployment
tests of OpenSDN. ??? difference to tf-dev-test ?

27. https://github.com/OpenSDN-io/tf-deployers-containers will be removed soon ???

28. https://github.com/OpenSDN-io/tf-tripleo-puppet contains tripelO
OpenSDN plugin.

29. https://github.com/OpenSDN-io/tf-tripleo-heat-templates keeps tripleO templates
for OpenSDN heat plugin.

30. https://github.com/OpenSDN-io/tf-third-party-packages stores RPM specs to build
third party packages for OpenSDN components and modules.

31. https://github.com/OpenSDN-io/tf-third-party-cache is a cache of third party
libraries sources used in OpenSDN.

32. https://github.com/OpenSDN-io/tf-specs holds specifications (blueprints) of
OpenSDN technical features (including the introduced earlier in Contrail,
OpenContrail and Tungsten Fabric).

33. https://github.com/OpenSDN-io/tf-operator ???

34. https://github.com/OpenSDN-io/tf-dpdk contains DPDK (https://www.dpdk.org/)
technology sources used in the OpenSDN data plane component.

35. https://github.com/OpenSDN-io/tf-build is a collection of SCons 
recipes used to build the OpenSDN Virtual Network Controller. ??? Moved into
other repositories?

36. https://github.com/OpenSDN-io/tf-api-client contains schema files for
the OpenSDN control plane data types and VNC client source code.

37. https://github.com/OpenSDN-io/tf-fabric-utils ???

38. https://github.com/OpenSDN-io/website stores source code of OpenSDN.io
website