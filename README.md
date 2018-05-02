
# Personal-Reading-List
I've decided keep track of the resources I found really useful.

Basic writing and formatting syntax: https://help.github.com/articles/basic-writing-and-formatting-syntax/
  - Summary: I included this link so I could always have a solid quick reference for creating this running document.
  
March 2018:

1) The Ultimate Guide to Bitcoin By: Michael Miller
  - Additional Information: Publisher: Que; Date: October 27, 2014

2) The Complexity of Public-Key Cryptography: https://eprint.iacr.org/2017/365.pdf
  - Summary: TBA 
  
3) Truthcoin : http://bitcoinhivemind.com/papers/truthcoin-whitepaper.pdf
  - Summary: TBA
  
4) New Directions in Cryptography : https://ee.stanford.edu/~hellman/publications/24.pdf
  - Summary: In an authentication system, cryptography is used to guarantee the authenticity of the message to the receiver. Not only must a meddler be prevented from injecting totally new, authentic looking messages into a channel, but he must be prevented from creating apparently authentic messages by combining, or merely repeating, old messages which he has copied in the past. A cryptographic system intended to guarantee privacy will not, in general, prevent this latter form of mischief. 
  - The first step in assessing the adequacy of cryptographic systems is to classify the threats to which they are to be subjected. The following threats may occur to cryptographic systems employed for either privacy or authentication.
    - A ciphertext only attack is a cryptanalytic attack in which the cryptanalyst possesses only ciphertext.
    - A known plaintext attack is a cryptanalytic attack in which the cryptanalyst possesses a substantial quantity of corresponding plaintext and ciphertext.
    - A chosen plaintext attack is a cryptanalytic attack in which the cryptanalyst can submit an unlimited number of plaintext messages of his own choosing and examine the resulting cryptograms.

5) Merkle Signature Schemes, Merkle Trees and Their Cryptanalysis: https://www.emsec.rub.de/media/crypto/attachments/files/2011/04/becker_1.pdf
  - Summary:

6) Lectures on Discrete Probabilistic Models: http://www.math.unipd.it/~pavon/Site/Teaching_files/notes.pdf
  - Summary: (This document will take me sometime to read, but I will hopefully have a rough understanding of the material before the summer)
  
 7) Proof-of-work system: https://en.wikipedia.org/wiki/Proof-of-work_system
  - Summary: An economic measure to deter denial of service attacks and other service abuses such as spam on a network by requiring some work from the service requester, usually meaning processing time by a computer. This is just a wikipedia page I found interesting.
    - HashCash: https://en.wikipedia.org/wiki/Hashcash
      - Client Puzzles: A Cryptographic Countermeasure Against Connection Depletion Attacks : http://hashcash.org/papers/client-puzzles.pdf
    - Introduction to Secure Sockets Layer: http://euro.ecom.cmu.edu/resources/elibrary/epay/SSL.pdf
    
  8) https://tools.ietf.org/html/rfc791#section-1.1
    - This document specifies the DoD Standard Internet Protocol.  This document is based on six earlier editions of the ARPA Internet Protocol Specification, and the present text draws heavily from them.  There have been many contributors to this work both in terms of concepts and in terms of text.  This edition revises aspects of addressing, error handling, option codes, and the security, precedence, compartments, and handling restriction features of the internet protocol.
    
  9) https://interledger.org/interledger.pdf
    -  Digital payment systems use ledgers to track accounts and balances and to enable local transfers between their users. Today, there are few connectors facilitating payments between these ledgers and there are high barriers to entry for creating new connections. Connectors are not standardized and they must be trusted not to steal the sender’s money.
      
  10) https://lightning.network/lightning-network-paper.pdf
    - The bitcoin protocol can encompass the global financial transaction volume in all electronic payment systems today, without a single custodial third party holding funds or requiring participants to have anything more than a computer using a broadband connection. A decentralized system is proposed whereby transactions are sent over a network of micropayment channels (a.k.a. payment channels or transaction channels) whose transfer of value occurs off-blockchain. If Bitcoin transactions can be signed with a new sighash type that addresses malleability, these transfers may occur between untrusted parties along the transfer route by contracts which, in the event of uncooperative or hostile participants, are enforceable via broadcast over the bitcoin blockchain in the event of uncooperative or hostile participants, through a series of decrementing timelocks. 
   
  11) https://ripple.com/build/escrow-tutorials/
    - Escrow tutuorial from Ripple
    
  12) https://bitcoin.org/bitcoin.pdf
    - A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution
  
  13) https://docs.google.com/document/d/1Bc-kZXROTeMzG6AvH7rrTrUy24UwHoEcgiL7ALHMO0A/pub
    - Effort has been directed towards architecting a parallel financial system with bitcoin the currency as a base layer. The driving force are flexibility benefits of cryptographic ledgers enabling new use cases like Multi-signature accounts, Decentralized exchange, Machine to machine transactions etc. This paper analyzes applications of cryptographic ledgers in the current financial system and aims to stimulate the discussion.
  
