# genericBeheer

The createNode script is based on an infra environment based on saltstack.
Creating nodes from a debian10+ template-qcow, and than testing infra-thingies 
with /.../top/int.sls and templates to build, configure, reconfigure and 
rebuilt the whole.

The Systemen file I used had this syntax. You are free after cloning a node
to create a dns-node on last-octet(16), for example
