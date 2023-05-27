# BigInt_ModExpo
AWS Site-to-Site VPN based on Diffie-Hellman Key Establishment


n AWS Site-to-Site VPN connection connects your Virtual Private Cloud (VPC) to your data centre as shown in
Figure 4. Amazon supports Internet Protocol Security (IPSec) VPN connections. Data transferred between your
VPC and data centre routes over an encrypted VPN connection maintain the confidentiality and integrity of
data in transit. Internet Key Exchange (IKEv2) is the protocol used to set up a security association (SA) in the
IPSec protocol suite. IKEv2 uses X.509 certificates for authentication ‒ either pre-shared or distributed and a
Diffie–Hellman key exchange to set up a shared session secret from which cryptographic keys are derived.
The Diffie–Hellman key exchange method allows two parties that have no prior knowledge of each other to
jointly establish a shared secret key over an insecure channel. In this question, you are required to implement
the Diffie–Hellman key exchange protocol (Group 2) between your VPC and your data centre.

1. Implemenented 160-bit random number geneation;
2. Used a Crypto Library to implement the modular exploentiation algorithm for larger integers.
