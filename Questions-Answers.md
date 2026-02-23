# Questions and Answers

Here are some common questions and some hopefully helpful answers.

* Q:
Should customers be getting signed artifacts only?

* A:
It depends.
In the 21st century, there is increasing concern over supply chain.
In the software industry, that is specifically concern over the
(no surprise here) *software* supply chain. With respect to code signing,
regulators, administrators, and executives require assurance that the
software artifacts have not been tampered with.

The real answer to the question depends on the risks.
Any software which might impact production work or operations
must be trustworthy. Signed software extends the chain of trust
from the vendor to the user/consumer. Code signing is an increasingly
important means of conveying trust. In absence of a signature,
the software *must* come by way of a trustworthy channel.

 * Q:
 What should I do with this PGP public key that I have generated?

First, get at least one other community member to sign it. <br/>
After that, use your key pair to cryptographically sign files as needed.

You can also use PGP encryption for email.
In that case, people will use your public key to encrypt a message
and you would decrypt it (having your secret key) when you receive it.

 * Q:
 What is the "fingerprint" of a PGP key and what is it used for?

* Q:
How do we "manage" keys?





* Q:
What is code signing?

* A:
Code signing is a method to confirm that code or other
digital binaries have not been altered. This method
leverages the Public Key Infrastructure (PKI) framework
to attests to the integrity of the code or binaries. Code
signing acts like a digital shrink wrap: the process
of code signing creates a "package" with the signed
code or file, if the "packaging" was not damaged when
received, then the file has not been tampered with and
can be trusted. And vice-versa: if the "packaging" was
damaged then the file has been tampered with and
cannot be trusted.

* Q:
Why is code signing important?

* A:
Code signing minimizes the risks of code tampering.
With signed code, the recipient gets a security warning
when the integrity check fails during download. This
helps recipients to avoid downloading tampered code
which may contain malware.

* Q:
What types of files can be signed?

* A:
You can sign all types of digital binaries including
drivers, firmware, containers, applications, mobile apps
as well as source code artifacts.



