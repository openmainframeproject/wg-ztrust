# Code Signing

Code Signing with PGP often really only means "file signing".

This page discusses code signing and file signing using PGP.


## Cryptographic Trust with PGP

It's simple:
If the public key of the signer is on your public keyring
then when you verify the signature the verification will pass.
PGP implementations do not necessarily walk the full chain of trust.

When adding public keys to your local collection (`pubring`),
be sure to vet them.

## Sign a File

In these examples we are using "detached" signatures.
A detached signature resides in a separate file from the signed object.
This has the advantage that the signed thing remains unchanged
but requires that you carry two files (payload and signature).

To sign a file with "armor", use the command ...

    gpg --armor --detach-sign file-to-sign

The result will be a secondary file with extension `.asc`.

To sign a file without "armor" (that is, binary), use the command ...

    gpg --detach-sign file-to-sign

The result will be a secondary file with extension `.sig`.

## Verify a File

Verification is similarly easy:

    gpg  --verify  file-to-sign.asc

`gpg` will know to remove the `.asc` suffix and comare against
`file-to-sign`, extracting key ID and related info from the signature file.






## Special Case for RPM

RPM packaging supports an internal signature.
Sign an RPM package file with the command ...

    rpmsign --addsign package-file.rpm

On the receiving end, verify the signature with ...

    rpm --checksig package-file.rpm

For package verification, RPM maintains its own keyring.
Add the public key of interest with the command ...

    rpm --import public-key-file

(Above will require privileges.)

















