<h1 align = "center"> CRIPTOGRAPHY💵 Concepts Developer shoud Know</h1>

## What is CRIPTOGRAPHY ?
<img align="center"  src = 'Diagrame/intro.png' />


<h3> CRIPTOGRAPHY is terrifying it's based on maths that most of us don't understad,Yet it's the one thing that makes internet secure.Without the mysterious work of Criptography there will be NO-Secrete or NO-Privacy in the digital world,Our E-mails,Browsing history easily hackabel.</h3>

<h3> Our computers are designed to do what we tell to do,but sometimes we don't want  to do certains things like publishing private data</h3> 

<img align="center" src = 'Diagrame/intro 1.png' />

<h3>It collect useful data and upload throught the viered algorythem to mix it up,so computer can't read it without proper values</h3>

<img align="center" src = 'Diagrame/intro 2.png' />

## History of CRYPTOGRAPHY 🐵

<h3>Cryptography has a long and fascinating history that spans thousands of years. Some of the earliest examples of cryptography are found in ancient civilizations, such as Egypt, Greece, Rome, China, and India. They used simple techniques, such as substitution and transposition, to hide messages from their enemies or allies. For example, the Caesar cipher, named after Julius Caesar, is a simple substitution cipher that shifts each letter of the alphabet by a fixed number of positions. The Vigenère cipher, developed in the 16th century, is a more complex substitution cipher that uses a keyword to determine the shift for each letter. The Enigma machine, used by the Nazis during World War II, is a famous example of a mechanical device that implements a complex substitution cipher with multiple rotors and plugboards.</h3>

<img align="center" src = 'Diagrame/spunchbob.jpeg' 
width="400" height="400" />

<h3>As technology and mathematics advanced, cryptography also evolved to become more sophisticated and secure. Modern cryptography is based on concepts such as number theory, algebra, and probability. It uses complex algorithms and protocols to achieve various goals, such as encryption, decryption, authentication, digital signatures, key exchange, and more. Modern cryptography also relies on the concept of computational hardness, which means that some problems are so difficult to solve that even the most powerful computers would take a very long time to crack them. For example, the RSA algorithm, one of the most widely used public-key encryption schemes, is based on the difficulty of factoring large numbers.</h3>

<img align="center" src = 'Diagrame/spunchbobtechnology.jpeg' width="400" height="400" />

## HASH
<img align="center" src = 'Diagrame/spunchbob hash.jpeg' width="400" height="400" />

<h3>A hash function is a mathematical function that takes any input data and produces a fixed-length output, called a hash or a digest. A hash function has two main properties: it is easy to compute the hash from the input, but it is hard to find the input from the hash. A hash function is also designed to be collision-resistant, which means that it is very unlikely that two different inputs will produce the same hash. A hash function can be used for various purposes, such as:</h3>

* <h3>Verifying the integrity of data: A hash function can be used to check if the data has been tampered with or corrupted. For example, when you download a file from the internet, you can compare the hash of the file with the hash provided by the source to make sure that the file is authentic and not modified by a malicious party.

* <h3>Authenticating messages: A hash function can be used to prove that a message was sent by a certain party and not altered by anyone else. For example, a sender can append a hash of the message to the message itself, and the receiver can verify the hash using the same hash function. This is called a message authentication code (MAC).

* <h3>Indexing data: A hash function can be used to map data to a smaller space, such as a table or an array. For example, a hash table is a data structure that uses a hash function to store and retrieve data efficiently.

### Some examples of hash functions are MD5, SHA-1, SHA-2, and SHA-3.

## SALT

<img align="center" src = 'Diagrame/spunchbob-slat.jpeg' width="400" height="400" />

### A salt is a random value that is added to the input of a hash function to make the hash more unpredictable and resistant to attacks. A salt is usually stored along with the hash, so that the hash can be verified later. A salt can be used for various purposes, such as:

* <h3>Preventing rainbow table attacks: A rainbow table is a precomputed table that contains the hashes of common passwords or phrases. An attacker can use a rainbow table to find the input of a hash by looking up the hash in the table. A salt can prevent this attack by making the hash unique for each input, so that the attacker would have to compute a new table for each salt.

* <h3>Preventing dictionary attacks: A dictionary attack is a brute-force attack that tries to guess the input of a hash by using a list of common or likely passwords or phrases. A salt can prevent this attack by making the hash different for each input, so that the attacker would have to try each password or phrase with each salt.

* <h3>Increasing the entropy of passwords: A salt can increase the entropy, or randomness, of passwords by adding more bits to the input of the hash function. This makes the passwords harder to crack by increasing the search space for the attacker.

## HMAC

### HMAC stands for Hash-based Message Authentication Code. It is a type of MAC that uses a hash function and a secret key to authenticate messages. HMAC has the following format:

### HMAC(K, M) = H((K ⊕ opad) || H((K ⊕ ipad) || M))

### where:

 * <h3>H is a hash function, such as SHA-256

* <h3>K is a secret key, shared by the sender and the receiver

* <h3>M is the message to be authenticated

* <h3>⊕ is the bitwise XOR operation

* <h3>|| is the concatenation operation

* <h3>opad and ipad are constant values, defined by the hash function

### HMAC can be used for various purposes, such as:

* <h3> Providing message integrity: HMAC can be used to ensure that the message has not been modified or corrupted by anyone else. The sender can compute the HMAC of the message and append it to the message itself, and the receiver can verify the HMAC using the same hash function and key. If the HMACs match, the message is authentic and intact.

* <h3>Providing message authentication: HMAC can also be used to prove that the message was sent by a certain party and not forged by anyone else. The sender and the receiver must share a secret key, which is used to compute and verify the HMAC. If the HMACs match, the message is authentic and from the expected party.

## Symmetric encryption

<img align="center" src = 'Diagrame/Symmetric encryption.jpeg' width="400" height="400" />

### Symmetric encryption is a type of encryption that uses the same key to encrypt and decrypt data. Symmetric encryption has the following format:

### C = E(K, P) P = D(K, C)

### where:

* <h3>C is the ciphertext, or the encrypted data

* <h3>P is the plaintext, or the original data

* <H3>K is the secret key, shared by the sender and the receiver

* <H3>E is the encryption function

* <h3>D is the decryption function

### Symmetric encryption can be used for various purposes, such as:

* <h3>Providing confidentiality: Symmetric encryption can be used to protect the data from unauthorized access or disclosure. The sender can encrypt the data using the secret key and send the ciphertext to the receiver, and the receiver can decrypt the ciphertext using the same key. Only the parties who know the key can access the data.

* <h3>Providing efficiency: Symmetric encryption is usually faster and simpler than other types of encryption, such as asymmetric encryption. Symmetric encryption can be implemented using various algorithms, such as AES, DES, and RC4.

## Keypairs

### A keypair is a pair of keys that are mathematically related to each other. A keypair consists of a public key and a private key. A public key is a key that can be shared with anyone, and a private key is a key that must be kept secret by the owner. A keypair can be used for various purposes, such as:

* <h3>Providing asymmetric encryption: Asymmetric encryption is a type of encryption that uses different keys to encrypt and decrypt data. Asymmetric encryption has the following format:

### C = E(Pu, P) P = D(Pr, C)

* <h3>C is the ciphertext, or the encrypted data
* <h3>P is the plaintext, or the original data
* <h3>Pu is the public key of the receiver
* <h3>Pr is the private key of the receiver
* <h3>E is the encryption function
* <h3>D is the decryption function

## Asymmetric encryption
<img align="center" src = 'Diagrame/Asymmetric encryption.jpeg' width="400" height="400" />

### Asymmetric encryption can be used to provide confidentiality and key exchange. The sender can encrypt the data using the public key of the receiver and send the ciphertext to the receiver, and the receiver can decrypt the ciphertext using their private key. Only the receiver can access the data, since they are the only one who knows their private key. The sender and the receiver can also use asymmetric encryption to exchange a secret key, which can be used for symmetric encryption or other purposes.

### Providing digital signatures: A digital signature is a way of verifying the authenticity and integrity of a message or a document. A digital signature has the following format:
### S = D(Pr, M) V = E(Pu, S)

### where:

* <h3>S is the signature, or the encrypted message or document
* <h3>M is the message or document to be signed
* <h3>Pr is the private key of the sender
* <h3>Pu is the public key of the sender
* <h3>D is the decryption function
* <h3>E is the encryption function
* <h3>V is the verification result, which is either true or false
### A digital signature can be used to provide authentication and non-repudiation. The sender can sign the message or document using their private key and append the signature to the message or document itself, and the receiver can verify the signature using the public key of the sender. If the verification result is true, the message or document is authentic and from the expected party, and the sender cannot deny sending it. If the verification result is false, the message or document is forged or modified by someone else.

### Some examples of keypair algorithms are RSA, DSA, and ECC.

## END

<img align="center" src = 'Diagrame/the end.jpeg' width="400" height="400" />


<div align = "center">
   
  |[![Ranjika Nethpriya](https://github.com/ranjika123.png?size=150)](https://github.com/ranjika123)|
  | ----------------------------------- 
  | [Ranjika Nethpriya](https://github.com/ranjika123)                                                             
  |[Porfolio](https://ranjikanethpriya.netlify.app/) 


                                                        
 </div>

 **Ranjika Nethpriya**
- GitHub: [Ranjika Nethpriya](https://github.com/Ranjika123)
- Email: ranjikaneth2005@gmail.com
- LinkedIn :[Ranjika Nethpriya](https://www.linkedin.com/in/ranjika-nethpriya-087268246/)
- Facebook :[Ranjika neth](https://web.facebook.com/ranjikaneth/)
- Inster :[Ranjika Neth](https://www.instagram.com/ranjika_neth/)


## License
This project is licensed under the [MIT License](LICENSE).

<h1>Give It a Star ✌</h1>






