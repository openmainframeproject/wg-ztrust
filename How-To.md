# How-To

Here are some quick how-to guides.

## How do I get a PGP key?

It's actually a key *pair* because the primary key in PGP speak
is asymmetric. There is a public half, which you distribute widely,
and there is a private or secret half, which you guard carefully.

Actually using PGP keys is discussed elsewhere, but if you're
new to PGP, the simplest way to create your own key pair is ...

    gpg --gen-key

`gpg` will prompt you for your full name and your email address and
then prompt for a pass-phrase. (Record that pass-phrase somewhere safe.)

Next you will want to share your public key with others. At this point
(new to the game and taking the defaults) an unqualified "export"
operation will provide your public key in a sharable form.

    gpg --armor --export > mykey.asc

The `--armor` flag says to "ASCII armor" the key (which is otherwise
binary gibberish). When you `--export` your key, it's talking about
the public half of the pair, so called (public) because it is intended
to be distributed.

The `.asc` suffix on the filename indicates that it is "ASCII armored".


