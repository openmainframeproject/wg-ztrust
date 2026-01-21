# Code Signing

This page is a simple overview of code signing.
Details of specific code signing methods are discussed in per-method
files as the need arises.

## Code Signing Purpose

We sign software packages ("deliverables" or "artifacts" or "packages")
to ensure intact and undisrupted delivery of the code. In the 21st
century there is concern about the software supply chain. (Indeed,
concern about *all* supply chains, though our focus is software.)

## Code Signing Trust Models

There are two popular "trust models" used for code signing:
* PKI, using the same services as are used for web site certification
* PGP, using traditional peer-to-peer cryptographic trust

In the PKI model, the signator must acquire a code signing certificate
from the Certificate Authority (CA) of choice.

In the PGP model, the signator must create a key pair and should then
have the public half signed by others in the PGP space.

In either case, the content to be delivered is hashed and then
encrypted with the key. That key (the private key associated with the
PKI cert or the private half of the PGP pair) is used to encrypt the
signature hash. Upon verification, the hash is decrypted using the
public key (or public half of the pair). If the decrypted hash
matches an immediate re-hash, the content is verified, confirmed.

## Code Signing Methods

There are two primary means of code signing:
* internal or embedded
* external or detached

In either case, a signature is derived which can then be used
to cryptographically ensure the content.

With an external or "detached" signature
the payload remains unchanged. The file comprising the deliverable
is scanned (i.e., hashed), a signature is created, and that signature
is stored as a separate file.

With an internal or "embedded" signature
the payload and signature are held together in one file.
The payload might be taken from an original separate file
or it might have pre-defined structure for holding signatures.


