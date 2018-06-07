## On Statistical Properties of Arbiter Physical Unclonable Functions - presentation

### Abstract

The growing interest in the Internet of Things (IoT) has led to predictions claiming that by 2020 we can expect to be surrounded by 50 billion Internet connected devices.
With more entry points to a network, adversaries can potentially use IoT devices as a stepping stone for attacking other devices connected to the network or the network itself.
Information security relies on cryptographic primitives that, in turn, depend on secret keys.
Furthermore, the issue of Intellectual property (IP) theft in the field of Integrated circuit (IC) design can be tackled with the help of unique device identifiers. 
Physical unclonable functions (PUFs) provide a tamper-resilient solution for secure key storage and fingerprinting hardware.
PUFs use intrinsic manufacturing differences of ICs to assign unique identities to hardware.
Arbiter PUFs utilise the differences in delays of identically designed paths, giving rise to an unpredictable response unique to a given IC.


This thesis explores the statistical properties of Boolean functions induced by arbiter PUFs. 
In particular, this empirical study looks into the distribution of induced functions.
The data gathered shows that only ~3% of all possible 4-variable functions can be induced by a single 4 stage arbiter PUF. Furthermore, some individual functions are more than 5 times more likely than others.
Hence, the distribution is non-uniform. 
We also evaluate alternate PUF designs, improving the coverage vastly, resulting in one particular implementation inducing all 65,536 4-variable functions. We hypothesise the need for *n* XORed PUFs to induce all 2<sup>2<sup>n</sup></sup> possible *n*-variable Boolean functions.

**Keywords:** PUF, Boolean function, function distribution, arbiter path, digital fingerprint, secure key storage, cryptography, system security, hardware security.

**Phillip Gajland (Stockholm, 2018)**</br>*On Statistical Properties of Arbiter Physical Unclonable Functions*
