# Commands

Here are some common PGP commands.
We are using `gpg` here as a PGP-workalike
because it is common on Unix systems and standard on Linux.

## Some GPG Commands

* for collecting keys from other people

    gpg  --allow-weak-key-signatures  --import  keyfile

* to share your public key with others

    gpg  --armor  --export  mykeyid  >  mykeyid.asc

* for signing keys of other people

    gpg  --default-cert-level 3  --sign-key  hiskeyid

You can then export keys of other people (now with your signature)
the same way as you export your own public key (above).

* for signing a file

    gpg  --armor  --detach-sign  file-to-sign

* for verifying a file

    gpg  --verify  signed-file.asc


