This folder holds PKI root certificates specifically for email use.
Intermediate PKI certs for email which chain-up to root certs need not
be here or may be here for facilitating intermediate certification
deployment. Leaf certificates *should not* be here.

PKI certificates found here should be detach signed by PGP keys.

## Naming

PEM-encoded certificates have a file type extension of `.crt`.

DER-encoded certificates (that is, binary) are not recommended here.

Human readable "text" form certs have a file type extension of `.txt`.
The PEM-encoded certificate will be found at the end of such a file.

Detached PGP signatures have a file type extension of `.asc`
indicating that they are ASCII-armored. The full extension is `.crt.asc`.


