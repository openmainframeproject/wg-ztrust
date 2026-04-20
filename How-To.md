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
binary gibberish). <br/> When you `--export` your key, it's talking about
the public half of the pair, so called (public) because it is intended
to be distributed publicly.

The `.asc` suffix on the filename indicates that it is "ASCII armored".
This "armored" file can (should) be emailed to others. It can (should)
also be uploaded to the ztrust WG repository.

You should email your armored public key to one or more other community
members asking them to "sign your key". (Be patient with the requirements
for authenticating your key to these others.) These people will return
your key, now having their signature(s), and you should "import" your
now-signed public key.

Note: You can delete keys from your keyrings, including deleting
private/secret keys. Recommend that you NOT delete a secret/private
key without first generating a revokation certificate.


