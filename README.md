clamav-mirror-boshrelease
=========================

A [BOSH](https://bosh.io) release for https://github.com/mxplusb/clamav.

Note:  you should use a VM type with at least 2GB of memory as the virus
definitions are stored in an in-memory cache.


To create a BOSH 
bosh create-release --tarball=clamav.tgz --final --version=2.0.x

Then add clamav.tgz to Release tab with the same Tag Name 

