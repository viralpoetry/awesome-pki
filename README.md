# awesome-pki  

A collection of articles, manuals, research papers, blogs, videos and software somehow related to the Public Key Cryptography (PKI).  

## Root Certificate Programs  

The organizations behind the browser and the operating system development maintain the most widely used collections of up-to-date certificate authority certificates.    
Root programs keep the list up-to-date and work together on the process standardization.  

[Chrome Root Program](https://www.chromium.org/Home/chromium-security/root-ca-policy/)  
[Mozilla's CA Certificate Program](https://wiki.mozilla.org/CA)  
[Apple Root Certificate Program](https://www.apple.com/certificateauthority/ca_program.html)  
[Microsoft Trusted Root Certificate Program](https://aka.ms/RootCert)  
[The Common CA Database (CCADB)](https://www.ccadb.org/) - managed by Mozilla, supported by Microsoft & Google  


## Articles & Other sources

[Everything you Never Wanted to Know about PKI but were Forced to Find Out (PDF)](https://www.cs.auckland.ac.nz/~pgut001/pubs/pkitutorial.pdf) - by Peter Gutmann  
[PKI: It’s Not Dead,Just Resting (PDF)](https://people.cs.vt.edu/~kafura/cs6204/Readings/Authentication/PKINotDead.pdf) - Peter Gutmann  
[X.509 Style Guide](https://www.cs.auckland.ac.nz/~pgut001/pubs/x509guide.txt) - by Peter Gutmann  
[SSL/TLS and PKI History](https://www.feistyduck.com/ssl-tls-and-pki-history/) - Feisty Duck  
[How to build your own public key infrastructure](https://blog.cloudflare.com/how-to-build-your-own-public-key-infrastructure/) - The Cloudflare Blog  
[Everything you should know about certificates and PKI but are too afraid to ask](https://smallstep.com/blog/everything-pki/) - Smallstep Labs blog  
[Path Building vs Path Verifying: The Chain of Pain](https://medium.com/@sleevi_/path-building-vs-path-verifying-the-chain-of-pain-9fbab861d7d6)  
[Certificate Transparency: a bird's-eye view](https://emilymstark.com/2020/07/20/certificate-transparency-a-birds-eye-view.html)  
[Key Management Cheat Sheet, OWASP](https://www.owasp.org/index.php/Key_Management_Cheat_Sheet)  
[Certificate Policy and Certification Practice Statement documents for ISRG / Let's Encrypt](https://github.com/letsencrypt/cp-cps)  
[Checklist on building an Offline Root & Intermediate Certificate Authority (CA)](https://security.stackexchange.com/questions/15532/checklist-on-building-an-offline-root-intermediate-certificate-authority-ca) - Stack Overflow  
[Certificate Authority with a YubiKey](https://developers.yubico.com/PIV/Guides/Certificate_authority.html)  
[Get started with the Nitrokey HSM or SmartCard-HSM](https://raymii.org/s/articles/Get_Started_With_The_Nitrokey_HSM.html)  
[PKI maturity model](https://pkic.org/pkimm/model/) - by PKI Consortium  
[PKI Posters](https://www.cem.me/pki) - Posters by Carl Mehner about the entire lifecycle of an SSL certificate

## Hardware Secure Modules (HSM) & Key management  

[Why I don't like smartcards, HSMs, YubiKeys, etc.](https://news.ycombinator.com/item?id=13031155) - Hacker News  
[The Untold Story of PKCS#11 HSM Vulnerabilities](https://cryptosense.com/blog/the-untold-story-of-pkcs11-hsm-vulnerabilities/) - Cryptosense  
[A survey of Hardware Crypto Devices (PDF)](https://cryptotronix.com/wp-content/uploads/2016/10/cryptowarez_nopause.pdf) - cryptotronix  
[Linux smart cards (OpenSC) - How-to](http://cedric.dufour.name/blah/IT/SmartCardsHowto.html) - Cédric Dufour blog  
[Key Management and use cases for HSMs](https://www.cryptomathic.com/news-events/blog/key-management-and-use-cases-for-hsms) - Cryptomathic  
[What is Key Management? a CISO Perspective](https://www.cryptomathic.com/news-events/blog/what-is-key-management-a-ciso-perspective) - Cryptomathic  
[The Definitive Guide to Encryption Key Management Fundamentals](https://info.townsendsecurity.com/definitive-guide-to-encryption-key-management-fundamentals) - Townsend Security  
[Example of an IANA DNSSEC signing ceremony](https://www.iana.org/dnssec/ceremonies/32) - not x509, but describes the procedure of a serious key ceremony  
[Security Concepts, Subsection 28.9: Key Management](https://www.subspacefield.org/security/security_concepts/#toc-Subsection-28.9) - blog of Travis  
[NIST Key Management Guidelines](https://csrc.nist.gov/Projects/Key-Management/Key-Management-Guidelines)  
[NIST Cryptographic Module Validation Program](https://csrc.nist.gov/Projects/Cryptographic-Module-Validation-Program/Modules-In-Process/Modules-In-Process-List)  
[Commercial Cryptographic Key Management in 2018](https://www.malgregator.com/post/key-management/)  


## Books  

[Bulletproof SSL and TLS: Understanding and Deploying SSL/TLS and PKI to Secure Servers and Web Applications](https://www.feistyduck.com/books/bulletproof-tls-and-pki/), Ivan Ristić

[Cryptography Engineering: Design Principles and Practical Applications](https://www.schneier.com/books/cryptography-engineering/), Niels Ferguson, Bruce Schneier, and Tadayoshi Kohno

[Security Engineering, The Second Edition (2008) - Chapter 21: Network Attack and Defence](https://www.cl.cam.ac.uk/~rja14/book.html), Ross Anderson

[Encyclopedia of Cryptography and Security](https://www.researchgate.net/publication/230674947_Springer_Encyclopedia_of_Cryptography_and_Security), Henk C.A. van Tilborg  

[Architecture for Public-Key Infrastructure (APKI)](https://pubs.opengroup.org/onlinepubs/009219899/toc.pdf), The Open Group Guide, 1999  


## Research Papers  

[Is the Web Ready for OCSP Must-Staple? (PDF)](https://balakrishnanc.github.io/papers/chung-imc2018.pdf)  

[The First Ten Years of Public-Key Cryptography - Whitfield Diffie (PDF)](https://www.cs.virginia.edu/~evans/greatworks/diffie.pdf)  

[PKI considered harmful](https://iang.org/ssl/pki_considered_harmful.html)  

## Audio / Video  

Hackable Security Modules: reversing and exploiting a FIPS 140-2 lvl3 HSM firmware - [video](https://www.youtube.com/watch?v=X8xu_I9kn18), [PDF](https://recon.cx/2017/brussels/resources/slides/RECON-BRX-2017-reversinghsms2.pdf)  
PKI Bootcamp by Paul Turner - [Playlist](https://www.youtube.com/playlist?list=PLDp2gaPHHZK-mnKi3Zy_-hRjqLHh5PaAv)  
How to be a Certificate Authority, feat. Ryan Sleevi - [Security. Cryptography. Whatever. podcast](https://securitycryptographywhatever.buzzsprout.com/1822302/9146390-how-to-be-a-certificate-authority-feat-ryan-sleevi)  
Fundamental X.509 PKI in Theory and OpenSSL (Cyrill Gössi) - [Playlist](https://www.youtube.com/playlist?list=PLWjMI9CAmVU4AHEMlq_SUuIAgeCDOdrvO)

## Open-Source Certificate Authority Software  

| Software | pkcs11 support | ACME support | Notes |
|----------|----------------|--------------|-------|
| [Let's Encrypt Boulder](https://github.com/letsencrypt/boulder) | yes | yes | not much documentation, no commercial support |
| [step-ca](https://github.com/smallstep/certificates) | yes | yes | cloud-ready CA with the commercial support |
| [EJBCA](https://www.ejbca.org/) | yes | yes | $$$$ commercial support |
| [Dogtag Certificate System](https://github.com/dogtagpki/pki) | yes | yes | n/a |
| [HashiCorp Vault PKI backend](https://www.vaultproject.io/docs/secrets/pki) | no (only enterprise?) | no | API based CA |
| [CFSSL](https://github.com/cloudflare/cfssl) | no | no | PKI toolkit with an API |
| [easy-rsa](https://github.com/OpenVPN/easy-rsa) | no | no | easy-rsa - Simple shell based CA utility |
| [OpenSSL Certificate Authority](https://jamielinux.com/docs/openssl-certificate-authority/) | yes | no | shell based CA leveraging OpenSSL |
| [XCA](https://www.hohnstaedt.de/xca/) | yes | no | Certificate authority with a comprehensive GUI |

