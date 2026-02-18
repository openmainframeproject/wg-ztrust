# Public PGP Key Servers

The greatest value of the PGP trust model is the "web of trust".
PGP keys which have been vetted in face-to-face meetings are
cross-signed. Other keys may be signed by core participants,
providing electronic introduction.

Signed keys can be published several ways, one being a PGP key server.
Can you trust the keys retrieved from a key server? Yes! The signatures
on those keys are the assurance of their authenticity. So always check
signatures.

We recommend that you upload your signed keys to one or more key servers.
This eliminates issues like no access (e.g., to this collection)
or having to hand the keys around.

## Publishing to a Key Server

Some PGP implementations have built-in capability to publish
your public key. In other cases, you can upload your public key
by a web interface (hosted on the key server).

To publish your keys using `gpg` use the command ...

    gpg --send-keys 0xfb4891ee59e24586

 ... where in this example `0xfb4891ee59e24586` is the key ID
of the key you wish to publish.

To publish your keys using a web interface, export the key in question
and then copy-n-paste it.

    gpg --armor --export 0xfb4891ee59e24586 > tempfile.asc

Use `tempfile.asc` for the content to copy.
Be sure to include the top and bottom dashed lines.

## Key Server Risks

It is difficult to control access to the public key servers
because they are *intentionally* open to submissions and uploads.

A serious threat occurred in 2019 when malicious actors flooded
certain targetted PGP keys with multiple useless signatures.
The result was several keys which were (because of the signatures)
too big to be usable. The damage was not limited to the key servers
but to anyone who might download the affected public keys.

Steps have been taken since this attack to prevent this kind
of problem. But many of the popular PGP key servers from before
this date have fallen out of service.

## Using Public Key Servers

When you retrieve a key from a public key server,
verify one or more signatures on that public key.
When you find a signature that you can trust, you are then
assured of the authenticity of the key.

Some public key servers follow.

* `https://keys.openpgp.org/`

`https://keys.openpgp.org/`
 is a public site that can hold keys and is easily integrated into
 some e-mail clients (like Thunderbird).

The OpenPGP site is better than most: requires email verification
 of the primary identity on the key. (That does limit an identity
 to just one key and it's common to have more than one PGP key
 for a given identity.)

* `https://pgp.surf.nl/`

`https://pgp.surf.nl/`
 is another viable public PGP server.
It may be vulnerable to the signature flooding attack,
 but for the moment it is working.

* `https://keyserver.ubuntu.com/`

`https://keyserver.ubuntu.com/`
 is an alternative public PGP key server
with similar characteristics to that of the Dutch key server.


