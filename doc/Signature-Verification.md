# Signature Verification

Here are command sequences for verifying different kinds of signatures.

## Detached PGP Signature

To verify a "detached" PGP signature, use the following single command:

   gpg --verify sendfile.vmarc.asc

In the above example, `sendfile.vmarc` is the original artifact
which was detached-signed using "armor" (hence the `.asc` suffix).
There must be two files in the working directory `sendfile.vmarc.asc`
(the signature) and `sendfile.vmarc` (the original file).

If you do not have the public key of the signer, `gpg` will tell you.
Acquiring public keys is discussed elsewhere. If you *do have*
the public key of the signer, and the signature is authentic,
and the file has not been corrupted or tampered with,
then `gpg` will immediately tell you that it is authentic.


