This folder holds all PGP keys in the collection in "armored" format.
The collection includes keys used for signing (the primary purpose of
the working group and project) but also for encrypting email.

The file `pgp-bundle.asc` one level up from here is a concatenation
of all of these `.asc` armored files.

The recommended filename format here is ...

keyid `-` identity `-public.asc`

 ... or ...

keyid `-` identity `-email.asc`

The keyid should be the long form, 16 hex digits prepended with `0x`.

The "identity" is usually a working email address, but the concept of
identity is much broader than just email. It is completely acceptable
to have an identity which is not an actual email address, but it is
recommended that such identities still have an at sign `@` to indicate
the domain where the key has meaning and/or was created.


