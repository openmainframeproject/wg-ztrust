# Identity

Identities become crucial as a handle on keys and certificates.

An email address is a recognized type of identity.
PGP keys use an email address, yet also have the 16-hex-digit
"key ID" for uniqueness.

We recommend using the key ID because it is consistently unique.

PKI certificates are identified by the "distinguished name" (DN).
The DN unfortunately often includes blanks which make it more difficult
to handle in automation. (Helps to use a blank delimited token.)
The "common name" (CN) may be easier to use, as long as it is unique.

We recommend making the CN as unique as possible, while avoiding
difficult punctuation and/or blanks. The CN is, by definition,
part of the DN.


