This folder holds all PKI root certificates in the ZTRUST collection
in armored or PEM-encoded format.

The collection includes root certificates which chain to leaf certs
of any kind, including web servers and email encryption, but especially
for code signing.

## Naming

PEM-encoded certificates have a file type extension of `.crt`.

DER-encoded certificates (that is, binary) are not recommended here.

Human readable "text" form certs have a file type extension of `.txt`.
The PEM-encoded certificate will be found at the end of such a file.

Detached PGP signatures have a file type extension of `.asc`
indicating that they are ASCII-armored. The full extension is `.crt.asc`.

## Rationale

These root certificates exist to fill the gap where Z community
contributions cannot be supported by the usual CA-provided root certs.


