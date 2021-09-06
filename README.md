# Final-Year-College-Project
A Novel Two Layer Encryption Algorithm Using One-Time Pad and DNA Cryptography


This project deals with the development of a secure genetic algorithmic system to transfer data that is of extreme importance of the internet in a very secure way. The idea is two implement two levels of encryption that too with a very random making it secure and allowing more and more and people to have a believer in online transaction, Genetic Algorithm is a powerful tool that has makes the process lot more secure, The randomness of the algorithm make it hard to crack it. Therefore, creating a more community where people trust in the sharing the most confidential details online through these secure means.

The need of encryption cannot be underestimated in today’s time. From a travel ticket to a movie ticket, almost everything of need is easily available. This comes with the cost of sharing important information, which if gets into wrong hand, will cause havoc. The aim of this work is to secure the data by fusing the extracts of one-time pad (OTP) and DNA cryptography. In the first level, a symmetric-key algorithm of OTP has been used to make the text secure which is a very random technique. In the next level, conventional DNA cryptographic techniques with few variations have been used. The target of implementation would be the storing and passing of vital information of customers like the debit/credit card details including the CVV code or the virtual passcode. Using DNA cryptography, large amount of storage can be made in the server with an efficient speed and power.


Chapter 1
Introduction
• Terminologies and Definitions:
Cryptography is associated with the process of converting ordinary 
plain text into unintelligible text and vice-versa. It is a method of 
storing and transmitting data in a particular form so that only those 
for whom it is intended can read and process it. Cryptography not 
only protects data from theft or alteration, but can also be used for 
user authentication.

DNA Cryptography can be defined as a hiding data in terms of 
DNA Sequence. Cryptographic technique in which each letter of the 
alphabet is converted into a different combination of the four bases 
that make up the human deoxyribonucleic acid (DNA).
Symmetric key cryptography (or symmetric encryption) is a type 
of encryption scheme in which the same key is used both to encrypt 
and decrypt messages. Such a method of encoding information has 
been largely used in the past decades to facilitate secret 
communication between governments and militaries. Nowadays, 
symmetric key algorithms are widely applied in various types of 
computer systems to enhance data security.
Asymmetric cryptography is a branch of cryptography where a 
secret key can be divided into two parts, a public key and a private 
key. The public key can be given to anyone, trusted or not, while the 
private key must be kept secret (just like the key in symmetric 
cryptography).

• Problem Definition
This problem focuses on developing an algorithm that can provide 
secure means to transfer sensitive data such as payment details using 
DNA Cryptography.

• Objective of the Project
The need of Encryption is almost cannot be underestimated in 
todays time. The Technology has advanced to a great extent and has 
reformed the conventional methods. We have come a long way as a 
civilization and have evolved. The conventional ways have been 
replaced in recent years with the advancement of technology.
Shopping from online website like AMAZON and FLIPKART is 
what people prefer to. Form a travel ticket to a movie ticket almost 
everything of need is easily available. This often comes with the cost 
of sharing important information if such detail gets into wrong hand 
they can easily, they can harm us. Thus, this makes is more clear 
that we ought to have proper mechanism for Encryption. Any 
weakness in encryption will be exploited — by hackers, criminals, 
and foreign governments. Many of the hacks that make the news can 
be attributed to weak or — even worse — non-existent encryption.
Therefore, it can be concluded that the Encryption is the need of 
hour.

This project we make a secure algorithm for Encryption using a two 
level security, in the first level we use symmetric key algorithm.
One Time Pad is used to make the text secure, this is a very random 
technique. In the next level, we use DNA Cryptography. The 
information in DNA is stored as a code made up of four chemical 
bases: adenine (A), guanine (G), cytosine (C), and thymine (T). 
DNA is the basic unit of life and the reasons for the transfer of 
hereditary characteristic from ancestors to the next generation. The 
reason being the DNA can carry a huge amount of information and 
are capable of arranging themselves in different manner. Since we 
know that every person has different DNA therefore the four 
chemical bases are capable of arranging themselves in many 
different ways.

Hence this project is an effort in exploring the complexities of DNA 
Cryptography and Implementing it to provide a secure algorithm 
that can be applied to the sensitive data been transferred over the 
network in a two layered secure manner that can further strengthen 
the security and exploring interesting domains of this interesting
topic of DNA Cryptography.

• Tools and Platforms
• Developer-end requirements
ANY PROGRAMMING LANGUAGE OF CHOICE
JAVA: programming language was originally developed by 
Sun Microsystems which was initiated by James Gosling and 
released in 1995 as core component of Sun Microsystems' 
Java platform (Java 1.0 [J2SE]). The latest release of the Java 
Standard Edition is Java SE 8. With the advancement of Java 
and its widespread popularity, multiple configurations were 
built to suit various types of platforms. For example: J2EE for 
Enterprise Applications, J2ME for Mobile Applications. The 
new J2 versions were renamed as Java SE, Java EE, and Java 
ME respectively. Java is guaranteed to be Write Once, Run 
Anywhere.

Java is − Object Oriented − In Java, everything is an Object. 
Java can be easily extended since it is based on the Object 
model.
• User-end requirements
• System Specification- The user system needs an i5 processor 
with at least 4GB RAM to train the classifier efficiently. The 
classifier training phase complexity is dependent upon the 
size of the text.

• Project Organisation
This project is organised in the following way: Chapter 2 deals with 
the state of the art. Chapter 3 discusses the concepts and the problem 
in details. Chapter 4 contains the sample codes. Chapter 5 deals with 
the experimental results and the comparison with other methods. 
Finally, chapter 6 concludes the project and discusses the future 
scope of development.


Chapter 2
Literature Survey
• Cryptography also allows senders and receivers to authenticate each other 
through the use of key pairs. There are various types of algorithms for 
encryption, some common algorithms include:

• Secret Key Cryptography (SKC): Here only one key is used for both 
encryption and decryption. This type of encryption is also referred to as 
symmetric encryption.

• Public Key Cryptography (PKC): Here two keys are used. This type of 
encryption is also called asymmetric encryption. One key is the public key 
that anyone can access. The other key is the private key, and only the 
owner can access it. The sender encrypts the information using the 
receiver’s public key. The receiver decrypts the message using his/her 
private key. For nonrepudiation, the sender encrypts plain text using a 
private key, while the receiver uses the sender’s public key to decrypt it. 
Thus, the receiver knows who sent it.

• DNA Cryptography Most of the cryptographic algorithms involve a large
memory and computations like, One Time Pad in which there are nonrepeating very large text pads, this technique will be very useful. A gram of 
DNA contains 1021 DNA bases and can store 108 terabytes of memory. 
One trillion bits of binary data can be stored in one cubic decimeter of 
DNA solution .Moreover DNA based computations take very less time 
compared to other algorithms. The task of any cryptography algorithm is 
to secure the data for very large duration of time. In this technique, bases 
of DNA are arranged in random order and plaintext bits can be stored 
successfully using these bases. As this technique employs one time pad 
which is perfectly random cryptographic technique, the data can be 
secured for very long periods of time. In addition to memory, DNA 
molecules show parallel computation, which means DNA based processes 
are capable of intense processing. DNA chains have large scale of 
parallelism and its computing speed could reach up to 1 billion times per 
second computations . DNA based computers also have very less power 
consumption, which is equal to one – billionth of a traditional computer 

.The vast parallelism and extraordinary information density inherent in 
DNA molecules are explored for cryptographic purposes such as 
encryption, authentication, signature, and so on.

• Symmetric key cryptography is any cryptographic algorithm that is 
based on a shared key that is used to encrypt or decrypt text/cyphertext, in
contract to asymmetric key cryptography, where the encryption and 
decryption keys are linked by different. Symmetric encryption is 
generally more efficient than asymmetric encryption and therefore 
preferred when large amounts of data need to be exchanged. Establishing 
the shared key is difficult using only symmetric encryption algorithms, so 
in many cases, an asymmetric encryption is used to establish the shared 
key between two parties. Symmetric Key Cryptography (SKC) 
consists of algorithms for cryptography that use the same key for both the 
encryption and decryption of data. The keys meant for the two functions
can be identical or the key might go through a simple transformation. 
Symmetric key algorithms require the sender and receiver to maintain 
absolute secrecy of the key. Only those two parties are required to share 
the key with the help of a private link. This introduces drawbacks to 
symmetric algorithms, when compared to public-key encryption (also 
known as asymmetric key encryption) .Symmetric key ciphers can be of 
two types:

• Stream ciphers encrypt all the bytes of a plaintext message at a time.

• Block ciphers encrypt a number of bytes of the plaintext message at a
time. Padding (increasing or decreasing the number of redundant 
characters) is done to make the total length of the message a multiple of 
the length of one block of message.


• Asymmetrical Encryption is also known as public key cryptography,
which is a relatively new method, compared to symmetric encryption. 
Asymmetric encryption uses two keys to encrypt a plain text. Secret keys 
are exchanged over the Internet or a large network. It ensures that
malicious persons do not misuse the keys. It is important to note that 
anyone with a secret key can decrypt the message and this is why
asymmetrical encryption uses two related keys to boosting security. A 
public key is made freely available to anyone who might want to send 
you a message. The second private key is kept a secret so that you can 
only know. A message that is encrypted using a public key can only be 
decrypted using a private key, while also, a message encrypted using a 
private key can be decrypted using a public key. Security of the public 
key is not required because it is publicly available and can be passed over 
the internet. Asymmetric key has a far better power in ensuring the
security of information transmitted during communication. Asymmetric 
encryption is mostly used in day-to-day communication channels, 
especially over the Internet. Popular asymmetric key encryption 
algorithm includes EIGamal, RSA, DSA, Elliptic curve technique, 
PKCS. To use asymmetric encryption, there must be a way of 
discovering public keys. One typical technique is using digital certificates
in a client-server model of communication. A certificate is a package of 
information that identifies a user and a server. It contains information
such as an organization’s name, the organization that issued the
certificate, the users’ email address and country, and users public key.


Chapter 3
Concepts and Problem Analysis
• Two Level Encryption Method
• One Time Pad


 BACKGROUND
The term "one-time pad" refers to any method of encryption where 
each byte of the plaintext is encrypted using one byte of the key 
stream and each key byte is used one time then never used again -
and its is the only absolutely secure cipher in use today. The onetime pad system itself was perfected in 1917 during the First World 
War[4,5]. Random keys were written on sheets of paper that were 
glued together to form a pad. Each key was used only once-hence 
the name, one-time pad. The key stream for a one-time pad must be 
a true-random stream, meaning that every key byte can take any of 
the values 0 to 255 with equal likelihood and independently of the 
values of all other key bytes. By contrast, in a pseudo-random key 
stream the value of each byte after the first several is mathematically 
derived from the values of a few preceding bytes.
The practical difficulty of using a one-time pad is that the key bytes 
cannot be reused. This means that even for a two-way exchange of 
messages, each party must have a sufficient supply of key material 
on hand so that they cannot run out before more key stream can be 
furnished. For N-way exchanges, the amount of key required 
increases quadratically. Many papers on cryptography assume that 
the only possible way out is for the key to be generated by some 
mathematical algorithm and then expend a great deal of cleverness 
in finding an algorithm that adequately approximates the properties 
of a true-random key. For more detailed information, one may refer 
to ref.[6] which gives a broad survey of such methods. The 
weakness of such methods is that determining a portion of the key 
stream will allow an opponent to reconstruct the entire key stream 
using the same mathematical algorithm. We will try to present a 
solution intermediate between a pure random key and a pure 
mathematical generator. However, be warned that the ultimate 
crypto-security depends on how cleverness you can keep your key 
secure from your enemy.


Why is One Time Pad Perfectly Secure ?

One-time pad encryption algorithm can be generalized using the 
following equation:
Ci=E (Pi, Ki) for I=1,2,3,…,n
where, E is the encryption operation, Pi is the I-th character of the 
plaintext, Ki is the I-th byte of the key used for this particular 
message, Ci is the I-th character of the resulting ciphertext and n is 
the length of the key stream. Both the key stream K and the 
encryption operation E must be kept secret. The key for each 
individual message is the starting location in the entire random key 
stream used for this encryption as will be seen later in the text. 
Although the term byte has been used and will continue to be used 
for each unit of the key stream, it is not necessary that each unit of 
the key be 8 bits long. In fact, a key with larger units gives better 
protection against a known-plaintext attack, since then there may be 
several values of the key which produce the given ciphertext byte 
from the known plaintext byte. Similarly, the plaintext could be 
encrypted in units other than 8-bit bytes. For present purposes, 
however, encryption based on bytes is sufficiently general.


How Is One Time Pad Implemented?

Step 1: Input a string that is to be encrypted. For example the word 
that has to be encrypted is "CRYPTOGRAPHY".
Step 2: The length of the word to be encrypted is calculated and the 
word is Uppercase.
Step 3: In an array "a" we store the values of the position of 
Alphabet. Since there are 26 character. In the array we store 
0,1,2,3....,25 for A,B,C,....Z.
Step 4: In other array "o" is used to store generated one time pad,
The length of one the pad is same as that of the word to be 
encrypted. Example for the "CRYPTOGRAPHY" we get any 
random word of 12 alphabets, "DEUOKHRWXKOP", and store the 
respective position as above.
Step 5: In the next step, we add the values of the two values and 
store in an array "a" and array "o" and store it in an array "enc1" this 
is the first level of encryption. For example the character "C" whose 
value is 2 and "D" whose value will be 3 on adding 2+3=5,which is 
F so that we encrypt the first level of encryption.
WORD C R Y P T O G R A P H Y
OTP D E U O K H R W X K O P
ENC F V S D D V X N X Z V N

• SECOND LEVEL ENCERPTION

• DNA CRYPTOGRAPHY


BACKGROUND

DNA cryptography is a new born cryptographic field emerged with the research 
of 
DNA computing, in which DNA is used as information carrier and the modern 
biological technology is used as implementation tool. The vast parallelism and 
extraordinary information density inherent in DNA molecules are explored for 
cryptographic purposes such as encryption, authentication, signature, and so on. 
In this paper, we briefly introduce the biological background of DNA 
cryptography and the principle of DNA computing, summarize the progress of 
DNA cryptographic research and several key problems, discuss the trend of DNA 
cryptography, and compare the status, security and application fields of DNA 
cryptography with those of traditional cryptography and quantum cryptography. It 
is pointed out that all the three kinds of cryptography have their own advantages 
and disadvantages and complement each other in future practical application. The 
current main difficulties of DNA cryptography are the absence of effective secure 
theory and simple realizable method. The main goal of the research of DNA 
cryptography is exploring characteristics of DNA molecule and reaction, 
establishing corresponding theories, discovering possible development directions, 
searching for simple methods of realizing DNA cryptography, and laying the 
basis for future development.



WHAT IS DNA?

DNA stands for Deoxyribonucleic acid which store genetic information of the 
entire living organism ranging from human being to small viruses. It is also called 
as an information carrier and consists of long polymer of small units called 
nucleotides. Further nucleotides consist of three components: Nitrogenous base, 
five Carbon sugar and Phosphate group. Nitrogenous base consists of four bases: 
Adenine, Thymine, Cytosine and Guanine (A, T, C, G), all the complex 
information about organism are stored with the combination of these bases. 
Adenine and Guanine are called purines, whereas Thymine and Cytosine are 
called pyrimidines. DNA is a double helix structure as shown in the Figure 
below. Figure 1. Double helical structure of DNA DNA double helical structure 
was discovered by the two Nobel laureate Watson and Crick and therefore it is 
also called a Watson-Crick complementary structure, where A and T form 
hydrogen bond with each other, whereas C and G forms bond with one another. 
In this structure of DNA both the strands are antiparallel to each other, means if 
one strand starts from 3′ to 5′, then another strand is from 5′ to 3′.
ADVANTAGE OF DNA CRYPTOGRAPHY

Speed – Conventional computers can perform approximately 100 MIPS (millions 
of instruction per second). Combining DNA strands as demonstrated by Adleman 
made computations equivalent to 10^9 or better, arguably over 100 times faster 
than the fastest computer.

Minimal Storage Requirements – DNA stores memory at a density of about 1 
bit per cubic nanometer, where conventional storage media requires 10^12 cubic 
nanometers to store 1 bit.

Minimal Power Requirements – There is no power required for DNA 
computing while the computation is taking place. The chemical bonds that are the 
building blocks of DNA happen without any outside power source. There is no 
comparison to the power requirements of conventional computers.
Multiple DNA crypto algorithms have been researched and published, like the 
Symmetric and Asymmetric Key Crypto System using DNA, DNA 
Steganography Systems, Triple Stage DNA Cryptography, Encryption algorithms 
inspired by DNA, and Chaotic computing.

DNA Cryptography can be defined as a technique of hiding data in terms of DNA 
sequence. In the cryptographic technique, each letter of the alphabet is converted 
into a different combination of the four bases which make up the human 
deoxyribonucleic acid (DNA).

DNA cryptography is a rapid emerging technology which works on concepts of 
DNA computing. DNA stores a massive amount of information inside the tiny 
nuclei of living cells. It encodes all the instructions needed to make every living 
creature on earth. The main advantages of DNA computation are miniaturization 
and parallelism of conventional silicon-based machines. For example, a square 
centimeter of silicon can currently support around a million transistors, whereas 
current manipulation techniques can handle to the order of 1020 strands of DNA. 
DNA, with its unique data structure and ability to perform many parallel 
operations, allows one to look at a computational problem from a different point 
of view.

A simple mechanism of transmitting two related messages by hiding the message 
is not enough to prevent an attacker from breaking the code. DNA Cryptography 
can have special advantage for secure data storage, authentication, digital 
signatures, steganography, and so on. DNA can also be used for producing 
identification cards and tickets. “Trying to build security that will last 20 to 30 
years for a defence program is very, very challenging,” says Benjamin Jun, vice 
president and chief technology officer at Cryptography Research. Multiple studies 
have been carried out on a variety of biomolecular methods for encrypting and 
decrypting data that is stored as a DNA. With the right kind of setup, it has the 
potential to solve huge mathematical problems. It’s hardly surprising then, that 
DNA computing represents a serious threat to various powerful encryption 
schemes.

Various groups have suggested using the sequence of nucleotides in DNA (A for 
00, C for 01, G for 10, T for 11) for just this purpose. One idea is to not even 
bother encrypting the information but simply burying it in the DNA so it is well 
hidden, a technique called DNA steganography. DNA Storage of Data has a wide 
range of capacity:

• Medium of Ultra-compact Information storage: Very large amounts of data 
that can be stored in compact volume

• A gram of DNA contains 1021 DNA bases = 108 Terabytes of data.

• A few grams of DNA may hold all data stored in the world.


HOW TO IMPLEMENT DNA CRYPTOGRAPHY
Step 6: One we get a string after the first level of encryption we therefore apply 
another level to the resulted string obtained after applying OTP method.
Step 7: The character of the encrypted string are converted to binary. For 
example The first character "F" whose ASCII value is 70 is convert to 7 digit 
binary value. The value for 70 is "1000110".
Step 8: We use this convention to create a string of DNA codes
Code DNA Represent
00 A
01 G
10 C
11 T
Using the information in this table we replace the binary string, Example 70 
which becomes "1000110" is transformed to "CATC" and for every other 
alphabet we get a this combination of DNA sequences.
This is how we have used the two level of encryption ,in this we need to share the 
One Time Pad between the person trying to exchange data, Since One Time Pad 
is generated in a random manner, every next time we perform the experiment we 
get different OTP. The sender and receiver has to have the exact same One Time 
Pad.
