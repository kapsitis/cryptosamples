AES Intro
==========

AES Algorithm Description
--------------------------

**Summary:** Represent AES into stages; appropriate mental images. 
Start with 128-bit blocks (S-Box, Substitute Rows, Mix Columns, 
Add Round Key). Later this image can be augmented (key schedule, 
padding, modes and other technical details).


AES Modes
----------




Using AES Safely
------------------

Communicating with prospective clients and students
should start from simple observations - how to do basic AES and 
how to use it safely.


* Authenticated encryption; GCM and CCM modes. 
  Exploit, if the same pair of Key+IV (initialization vector)
  are used to encrypt two different messages. See [DG2020]_.
* Confidentiality encryption; ECB, CBC, CFB, OFB, CTR modes.
  Another version of the Initialization Vector exploit in the CTR mode. 
  See [Hammond2021]_. 
* Attacks to the non-authenticating versions of AES (such as CBC). 
  See [Decrypt2020]_.

After this one can proceed with white-box designs and their
attacks.






