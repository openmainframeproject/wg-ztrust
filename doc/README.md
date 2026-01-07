# ztrust/pgp

This is the ztrust/doc folder with documentation
explaining PKI, PGP, cryptographic signing, and cryptographic trust.

## Purpose

The purpose of the ZTRUST working group, and of this repository,
is to provide a trust anchor for the mainframe ("Z") software
supply chain. Software vendors can acquire signing certificates
from several well known certificate authorities (CAs). Other providers
of mainframe software are not in a for-profit operation and may not
be able to get or maintain a recognized signing certification.
The trust anchor provided by the PKI certificates and PGP keys
included here supplement the services of the for-profit operators.

This repository, and the working group, exists also to educate
mainframe software developers, administrators, and managers
about cryptographic verification and provenance.

## Rationale

The following observation is from Dan Rathbun, CIO/CISO for
several enterprises:

*"One of the inherent problems of standard HTTPS is that trust put in
a website is defined by certificate authorities: a hierarchical and
closed set of companies and governmental institutions approved by your
web browser vendor. This model of trust has long been criticized
and proven ... to be vulnerable to attacks ..."*

This trust anchor is intended to remedy that problem
in the context of the mainframe community.


