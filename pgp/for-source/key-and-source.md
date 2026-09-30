# Key and Source

This file matches some signing keys with the packages they sign.
Packages are usually compressed TAR. Signatures are usually detached.

This is *far* from an exhaustive list.

Note that many keys are used for signing more than just one package.
Note also that some packages are signed by more than just one key.

See the bottom for example usage and how to verify code signing.

## PGP Keys for Source Signing

    0x00ccb587ddbef0e1-staff@irssi.org-signing.asc                  irssi-1.0.2
    0x00ccb587ddbef0e1-staff@irssi.org-signing.asc                  irssi-1.1.1
    0x00ccb587ddbef0e1-staff@irssi.org-signing.asc                  irssi-1.4.5
    0x0664a76954265e8c-simon@yubico.com-signing.asc                 oathtool-2.6.2
    0x08302db6a2670428-tim.ruehsen@gmx.de-signing.asc               libpsl-0.23.3
    0x0adee10094604d37-mthl@gnu.org-signing.asc                     automake-1.16
    0x0adee10094604d37-mthl@gnu.org-signing.asc                     automake-1.16.1
    0x0d28d4d2a0ace884                                              nano-4.9.2
    0x0d28d4d2a0ace884                                              nano-5.5
    0x0ddcaa3278d5264e-akim@gnu.org-signing.asc                     bison-3.3.2
    0x0ddcaa3278d5264e-akim@gnu.org-signing.asc                     bison-3.5.3
    0x0ddcaa3278d5264e-akim@gnu.org-signing.asc                     bison-3.8.2
    0x126eb563a74b06bf                                              python-2.6.9
    0x13e96b53c005604e                                              gnucobol-3.1
    0x13e96b53c005604e                                              gnucobol-3.1.2
    0x13e96b53c005604e                                              gnucobol-3.2
    0x13fcef89dd9e3c4f-nickc@redhat.com-signing.asc                 binutils-2.34
    0x13fcef89dd9e3c4f-nickc@redhat.com-signing.asc                 binutils-2.35
    0x13fcef89dd9e3c4f-nickc@redhat.com-signing.asc                 binutils-2.38
    0x13fcef89dd9e3c4f-nickc@redhat.com-signing.asc                 binutils-2.40
    0x13fcef89dd9e3c4f-nickc@redhat.com-signing.asc                 binutils-2.41
    0x14e05f16d52460e9-jay@gnu.org-signing.asc                      findutils-4.6.0
    0x151308092983d606-gary@gnu.org-signing.asc                     libtool-2.4.6
    0x182e23579462efaa                                              bind-9.18.17
    0x216094dfd0cb81ef                                              openssl-3.0.19
    0x249b39d24f25e3b6-wk@gnupg.org-signing.asc                     gnupg-1.4.23
    0x249b39d24f25e3b6-wk@gnupg.org-signing.asc                     npth-1.6
    0x29ee58b996865171-nmav@gnutls.org-signing.asc                  gnutls-3.5.9
    0x2a1743eda91a35b6-darnir@gnu.org-signing.asc                   wget-1.20.3
    0x2a1743eda91a35b6-darnir@gnu.org-signing.asc                   wget-1.21.3
    0x2a1743eda91a35b6-darnir@gnu.org-signing.asc                   wget-1.25.0
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-8.6p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-8.9p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.0p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.1p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.3p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.3p2
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.6p1
    0x2a3f414e736060ba-djm@mindrot.org-signing.asc                  openssh-9.8p1
    0x2c3d4e4c17f231a4-derek@ximbiot.com-signing.asc                cvs-1.11.23
    0x2d347ea6aa65421d-nad@python.org-signing.asc                   python-3.6.8
    0x2d347ea6aa65421d-nad@python.org-signing.asc                   python-3.7.2
    0x2d347ea6aa65421d-nad@python.org-signing.asc                   python-3.7.4
    0x2d347ea6aa65421d-nad@python.org-signing.asc                   python-3.7.6
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     cpio-2.12
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     cpio-2.13
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     cpio-2.15
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     tar-1.30
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     tar-1.32
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     tar-1.34
    0x3602b07f55d0c732-gray@gnu.org-signing.asc                     tar-1.35
    0x38ee757d69184620-lasse.collin@tukaani.org-signing.asc         xz-5.2.4
    0x38ee757d69184620-lasse.collin@tukaani.org-signing.asc         xz-5.2.5
    0x38ee757d69184620-lasse.collin@tukaani.org-signing.asc         xz-5.6.2
    0x3c17da8b8a16544f                                              hashcat-5.1.0
    0x41633b9fe837f581-vapier@gentoo.org-signing.asc                acl-2.2.53
    0x41633b9fe837f581-vapier@gentoo.org-signing.asc                attr-2.4.48
    0x41d20965c2e82dc7                                              openvpn-2.6.9
    0x42e86a2a11f48d36-dgoulet@torproject.org-signing.asc           tor-0.4.8.10
    0x42e86a2a11f48d36-dgoulet@torproject.org-signing.asc           tor-0.4.8.15
    0x42e86a2a11f48d36-dgoulet@torproject.org-signing.asc           tor-0.4.8.19
    0x42e86a2a11f48d36-dgoulet@torproject.org-signing.asc           tor-0.4.9.13
    0x46502ef796917195-mail@bernhard-voelker.de-signing.asc         findutils-4.10.0
    0x4f494a942e4616c2                                              gettext-0.20.1
    0x4f494a942e4616c2                                              libiconv-1.15
    0x514bbe2eb8e1961f-bensberg@telfort.nl-signing.asc              nano-7.2
    0x514bbe2eb8e1961f-bensberg@telfort.nl-signing.asc              nano-9.2
    0x520a9993a1c052f8                                              nginx-1.15.9
    0x527466a21ca79e6d                                              openssl-3.0.7
    0x528897b826403ada                                              gnupg-2.3.6
    0x528897b826403ada                                              gnupg-2.4.3
    0x528897b826403ada                                              gnupg-2.5.3
    0x528897b826403ada                                              libassuan-2.5.5
    0x528897b826403ada                                              libassuan-2.5.6
    0x528897b826403ada                                              libassuan-3.0.1
    0x528897b826403ada                                              libgcrypt-1.10.2
    0x528897b826403ada                                              libgcrypt-1.11.0
    0x528897b826403ada                                              libgcrypt-1.12.2
    0x528897b826403ada                                              libgcrypt-1.8.10
    0x528897b826403ada                                              libgpgerror-1.47
    0x528897b826403ada                                              libgpgerror-1.51
    0x528897b826403ada                                              libgpgerror-1.59
    0x528897b826403ada                                              libksba-1.6.4
    0x528897b826403ada                                              libksba-1.6.7
    0x528897b826403ada                                              npth-1.8
    0x533a6860529f23c5                                              openvpn-2.6.12
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.1.24
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.1
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.2
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.3
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.4
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.5
    0x56bcdb593020450f-musl@libc.org-signing.asc                    musl-1.2.6
    0x5831d11a0d4db02a                                              mpfr-4.2.1
    0x5831d11a0d4db02a                                              mpfr-4.2.2
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.61.1
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.67.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.70.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.72.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.78.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.81.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-7.88.1
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-8.2.0
    0x5cc908fdb71e12c2-daniel@haxx.se-signing.asc                   curl-8.22.0
    0x64e628f8d684696d-pablogsal@gmail.com-signing.asc              python-3.11.2
    0x65c26e471f45b123-kim@netbsd.org-signing.asc                   tcsh-6.24.07
    0x65c26e471f45b123-kim@netbsd.org-signing.asc                   tcsh-6.24.10
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.0.6
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.1.10
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.2.6
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.3.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.4.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.5.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.6.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.7.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.8.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-2.9.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.0.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.1.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.2.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.3.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.4.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.5.*
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.6.0
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.6.1
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.6.2
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.6.3
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.7.3
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.8.0
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.8.1
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.8.2
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.8.3
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.8.4
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.9.0
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-3.9.2
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-4.3.1
    0x663af51bd5e4d8d5-bcook@openbsd.org-signing.asc                libressl-4.3.2
    0x6c859fb14b96a8c5-wayned@samba.org-signing.asc                 rsync-3.1.3
    0x6c859fb14b96a8c5-wayned@samba.org-signing.asc                 rsync-3.2.3
    0x6c859fb14b96a8c5-wayned@samba.org-signing.asc                 rsync-3.2.4
    0x6c859fb14b96a8c5-wayned@samba.org-signing.asc                 rsync-3.2.7
    0x6e744acba9c09e30-rse@engelschall.com-signing.asc              pth-2.0.7
    0x6eac957f8eeb55c0-alex.ameen.tx@gmail.com-signing.asc          libtool-2.4.7
    0x6fa6ebc9911a4c02-codesign@isc.org-signing.asc                 dhcp-4.3.3
    0x702353e0f7e48edb-dickey@his.com-signing.asc                   ncurses-6.1
    0x71776baedd20ad42                                              gnucobol-2.2
    0x72d23fbac99d4e75                                              groff-1.22.4
    0x74bb6b9a4cbb3d38                                              bind-9.15.5
    0x783fcd8e58bcafba-madler@alumni.caltech.edu-signing.asc        zlib-1.2.13
    0x783fcd8e58bcafba-madler@alumni.caltech.edu-signing.asc        zlib-1.3.1
    0x78e11c6b279d5c91-daniel@haxx.se-signing.asc                   curl-7.42.1
    0x7f67d5fd1ce1cbce                                              openldap-2.5.18
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 automake-1.16.2
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 automake-1.16.5
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 automake-1.17
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 diffutils-3.10
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 diffutils-3.7
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 grep-3.12
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 grep-3.3
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 gzip-1.12
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 gzip-1.6
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 gzip-1.8
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 sed-4.10
    0x7fd9fccb000beeee-jim@meyering.net-signing.asc                 sed-4.8
    0x80cb727a20c79bb2-psmith@gnu.org-signing.asc                   make-4.3
    0x80cb727a20c79bb2-psmith@gnu.org-signing.asc                   make-4.4.1
    0x81c24ff12fb7b14b                                              bc-1.07.1
    0x82781de46d5954fa                                              apache-2.4.57
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  ed-1.14.2
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  ed-1.15
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  ed-1.19
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  ed-1.9
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  lzip-1.15
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  lzip-1.20
    0x8fe99503132d7742-antonio@gnu.org-signing.asc                  lzip-1.23
    0x91fcc32b6769aa64-zackw@panix.com-signing.asc                  autoconf-2.71
    0x91fcc32b6769aa64-zackw@panix.com-signing.asc                  autoconf-2.72
    0x933b01f40b5ca946                                              node-v9.9.0
    0x96262acffbd3aec6                                              expat-2.5.0
    0x96aec408005d6bb4                                              openvpn-2.5.0
    0x96af6544edf138d9-rmt@casita.net-signing.asc                   cmsfs-1.1.12
    0x96b047156338b6d4-psmith@gnu.org-signing.asc                   make-4.2.1
    0x9766e084fb0f43d8-ph10@cam.ac.uk-signing.asc                   pcre-8.44
    0x980c197698c3739d-vincent.lefevre@inria.fr-signing.asc         mpfr-3.1.3
    0x980c197698c3739d-vincent.lefevre@inria.fr-signing.asc         mpfr-4.0.1
    0x980c197698c3739d-vincent.lefevre@inria.fr-signing.asc         mpfr-4.0.2
    0x980c197698c3739d-vincent.lefevre@inria.fr-signing.asc         mpfr-4.1.0
    0xa0ea981b66b0d967                                              nginx-1.23.1
    0xa186278d426a38e9                                              bc-1.08.2
    0xa2d29b7bf295c759                                              openssl-0.9.8k
    0xa328c3a2c3c45c06-jakub@redhat.com-signing.asc                 gcc-9.2.0
    0xa5526b9bb3cd4e6a-jdelvare@suse.de-signing.asc                 dmidecode-3.7
    0xa7a16b4a2527436a-eblake@redhat.com-signing.asc                autoconf-2.69
    0xa7a16b4a2527436a-eblake@redhat.com-signing.asc                m4-1.4.18
    0xa7a16b4a2527436a-eblake@redhat.com-signing.asc                m4-1.4.19
    0xa9f4c021cea470fb                                              sudo-1.8.28
    0xa9f4c021cea470fb                                              sudo-1.8.29
    0xa9f4c021cea470fb                                              sudo-1.9.10
    0xa9f4c021cea470fb                                              sudo-1.9.5p2
    0xacf8146cae8cbbc4-dana@dana.is-signing.asc                     zsh-5.9
    0xad2744ee58025396-hjl.tools@gmail.com-signing.asc              binutils-2.24.51.0.3
    0xb0b5e88696afe6cb                                              git-2.20.1
    0xb0b5e88696afe6cb                                              git-2.29.2
    0xb1048932dd3aaaa3-michal.trojnara@stunnel.org-signing.asc      stunnel-5.71
    0xb1048932dd3aaaa3-michal.trojnara@stunnel.org-signing.asc      stunnel-5.78
    0xb268e706ff5cf463                                              squid-3.5.25
    0xb26995e310250568                                              python-3.8.2
    0xb26995e310250568                                              python-3.8.9
    0xb26995e310250568                                              python-3.9.15
    0xb708a383c53ef3a4                                              screen-4.6.2
    0xb708a383c53ef3a4                                              screen-4.8.0
    0xb86086848ef8686d-azat@libevent.org-signing.asc                libevent-2.1.11
    0xb86086848ef8686d-azat@libevent.org-signing.asc                libevent-2.1.12
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-3.2
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-4.4.18
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.0
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.1.8
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.2.15
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.2.21
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.2.32
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    bash-5.2.37
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    readline-7.0
    0xbb5869f064ea74ab-chet@cwru.edu-signing.asc                    readline-8.2
    0xbea7b180b1491921-ahf@torproject.org-signing.asc               tor-0.4.9.13
    0xc155a4eee4e527a2-carlo@alinoe.com-signing.asc                 which-2.21
    0xc155a4eee4e527a2-carlo@alinoe.com-signing.asc                 which-2.23
    0xc7271d0a49b18ba7-herbert@gondor.apana.org.au-                 dash-0.5.13.1
    0xc8464d549af75c0a                                              nginx-1.27.4
    0xcc2af4472167be03-dickey@his.com-signing.asc                   ncurses-6.5
    0xcc2af4472167be03-dickey@his.com-signing.asc                   ncurses-6.6
    0xd19e9c7d71266dce-g.branden.robinson@gmail.com-signing.asc     groff-1.24.1
    0xd3657d24d058434c                                              jansson-2.13.1
    0xd3657d24d058434c                                              jansson-2.14
    0xd36f769bc11804f0-tytso@debian.org-signing.asc                 e2fsprogs-1.45.6
    0xd36f769bc11804f0-tytso@debian.org-signing.asc                 e2fsprogs-1.45.6
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-7.4p1
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-7.6p1
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-7.9p1
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-8.0p1
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-8.2p1
    0xd3e5f56b6d920d30-djm@mindrot.org-signing.asc                  openssh-8.4p1
    0xd5bf9feb0313653a-agruen@kernel.org-signing.asc                acl-2.3.1
    0xd5bf9feb0313653a-agruen@kernel.org-signing.asc                attr-2.5.1
    0xd5bf9feb0313653a-agruen@kernel.org-signing.asc                patch-2.7.6
    0xd5e9e43f7df9ee8c-levitte@openssl.org-signing.asc              openssl-1.1.1q
    0xd5e9e43f7df9ee8c-levitte@openssl.org-signing.asc              openssl-1.1.1t
    0xd5e9e43f7df9ee8c-levitte@openssl.org-signing.asc              openssl-3.0.5
    0xd73cf638c53c06be-simon@josefsson.org-signing.asc              inetutils-2.4
    0xd73cf638c53c06be-simon@josefsson.org-signing.asc              oathtool-2.6.13
    0xd73cf638c53c06be-simon@josefsson.org-signing.asc              oathtool-2.6.14
    0xd73cf638c53c06be-simon@josefsson.org-signing.asc              oathtool-2.6.9
    0xd894e2ce8b3d79f5                                              openssl-1.1.1w
    0xd894e2ce8b3d79f5                                              openssl-3.0.12
    0xd9204cb5bfbf0221-bkorb@gnu.org-signing.asc                    sharutils-4.15.2
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.1t
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.1u
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.2j
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.2m
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.2o
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.2p
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.0.2u
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.0b
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.0c
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.0e
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.0g
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.0h
    0xd9c4d26d0e604491-matt@openssl.org-signing.asc                 openssl-1.1.1k
    0xdaf7350a7ebbd625-frob@debian.org-signing.asc                  glibc-2.6.1
    0xddbc579dab37fba9-gavinsmith0123@gmail.com-signing.asc         texinfo-6.7
    0xddbc579dab37fba9-gavinsmith0123@gmail.com-signing.asc         texinfo-7.0.3
    0xdf597815937ec0d2-arnold@skeeve.com-signing.asc                gawk-4.2.1
    0xdf597815937ec0d2-arnold@skeeve.com-signing.asc                gawk-5.0.1
    0xdf6fd971306037d9-pbrady@redhat.com-signing.asc                coreutils-8.27
    0xdf6fd971306037d9-pbrady@redhat.com-signing.asc                coreutils-8.30
    0xdf6fd971306037d9-pbrady@redhat.com-signing.asc                coreutils-8.31
    0xe4b29c8d64885307                                              flex-2.6.4
    0xe4b71d5eec39c284                                              utillinux-2.34
    0xe4b71d5eec39c284                                              utillinux-2.38.1
    0xe4b71d5eec39c284                                              utillinux-2.40.1
    0xe98e9b2d19c6c8bd                                              gnupg-2.3.6
    0xe98e9b2d19c6c8bd                                              gnupg-2.5.3
    0xe98e9b2d19c6c8bd                                              libassuan-3.0.1
    0xe98e9b2d19c6c8bd                                              libgcrypt-1.8.10
    0xe98e9b2d19c6c8bd                                              libgpgerror-1.51
    0xe98e9b2d19c6c8bd                                              libksba-1.6.7
    0xe98e9b2d19c6c8bd                                              npth-1.8
    0xef8fe99528b52ffd                                              zstd-1.5.2
    0xef8fe99528b52ffd                                              zstd-1.5.5
    0xf132b1cbaf131cae                                              openvpn-2.4.6
    0xf153a7c833235259-markn@greenwoodsoftware.com-signing.asc      less-557
    0xf153a7c833235259-markn@greenwoodsoftware.com-signing.asc      less-661
    0xf3599ff828c67298-nisse@lysator.liu.se-signing.asc             gmp-6.3.0
    0xf5be8b267c6a406d-bruno@clisp.org-signing.asc                  gettext-0.22.5
    0xf7d5c9bf765c61e3-andreas.enge@inria.fr-signing.asc            mpc-1.1.0
    0xf7d5c9bf765c61e3-andreas.enge@inria.fr-signing.asc            mpc-1.2.1
    0xf7d5c9bf765c61e3-andreas.enge@inria.fr-signing.asc            mpc-1.3.1

## Source Package Verification

Many (most?) open source software packages are signed.
To be clear, a specific release of a particular package will be archived
as TAR or ZIP and the resulting archive file cryptographically signed.
This provides a perpetual reference to that release of that package.

As an example, consider BASH, the Bourne Again SHell.
You can obtain a source archive of BASH 5.3 from ...

https://ftp.gnu.org/gnu/bash/bash-5.3.tar.gz

You should also obtain the detached signature file ...

https://ftp.gnu.org/gnu/bash/bash-5.3.tar.gz.sig

The "payload" is the `.tar.gz` file, and that is what is/was signed.

You will also need to download and import (to your GPG keyring)
the signing key (the public half of that key pair),
which for this version of BASH is `0xbb5869f064ea74ab`.
In the collection the file is
[0xbb5869f064ea74ab-chet@cwru.edu-signing.asc](0xbb5869f064ea74ab-chet@cwru.edu-signing.asc)

Download and import that public key. <br/>
Note: when downloading individual public keys from GitHub,
be sure to select the "raw" version, not one of the HTML decorated pages.

    gpg --import 0xbb5869f064ea74ab-chet@cwru.edu-signing.asc

You can then, at any time afterward, verify the archive with ...

    gpg --verify bash-5.3.tar.gz.sig

You not need, in fact *should* not, uncompress the file first.

This provides assurance that ...

* the download was/is intact
* the content is what the publisher intended
* your copy has not been tampered with


