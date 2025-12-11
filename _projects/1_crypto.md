---
layout: page
title: Cryptography (Fall 2025)
description: Master's Degree in Computer Science, Master's Degree in Cybersecurity, Master's Degree in Mathematics
img: assets/img/crypto.jpg
importance: 1
category: teaching
related_publications: false
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/crypto.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h2>Syllabus</h2>
The course is meant to be an introduction to modern cryptography, with a focus on provable security. Below is a tentative list of topics.
<br><br>
<em>Information-Theoretic Cryptography:</em>
<ul>
<li> Perfect secrecy, one-time pad, Shannon's theorem.
</li>
<li> Perfect authentication, universal hashing, extractors, leftover-hash lemma.
</li>
</ul>

<em>Computational Security:</em>
<ul>
<li> One-Way Functions (OWF) and complexity theory.
</li>
<li> Brush-up on number theory, candidate OWF (Factoring, RSA, DL, LWE).
</li>
<li> Computational indistinguishability, decisional assumptions (DDH, LWE).
</li>
</ul>

<em>Symmetric Cryptography:</em>
<ul>
<li> Pseudorandom Generators (PRG), hard-core bits, PRG constructions.
</li>
<li> Pseudorandom Functions (PRF), PRF constructions, Feistel networks.
</li>
<li> Symmetric encryption: Definitions and constructions, modes of operation.
</li>
<li> Message authentication: Definitions and constructions, authenticated encryption.
</li>
<li> Hash functions: Random oracle model, first/second pre-image resistance, collision resistance, Merkle-Damgaard construction.
</li>
</ul>

<em>Public-Key Cryptography:</em>
<ul>
<li> Public-key encryption: Definitions, RSA and ElGamal cryptosystems. Cramer-Shoup encryption.
</li>
<li> Digital signatures: Definitions, full-domain hash, signatures from OWF, Waters' signatures.
</li>
<li> Identification schemes: Definitions, constructions and applications to signatures.
</li>
<li> Identity-based encryption and applications.
</li>
</ul>

<h2>Logistics</h2>
<p style="color:red;"><b> Important: </b>The lectures are offered exclusively in-person (with no registration taking place).</p>
<!---
<p style="color:red;"><b> Important: </b>The lecture on 08/11/24 will be exceptionally remote at <a href="https://uniroma1.zoom.us/j/89487521223?pwd=KzrfMElWv3v7c6bOi7BGXR9U9rCw49.1">this link</a>.</p>
--->
<em>Lecture time:</em> Tuesday (8:00am - 11:00am) and Friday (11:00am - 13:00am).
<br>
<em>Location:</em> Aula 1L (RM018) - Via del Castro Laurenziano 7a.
<br>
<em>Twitter:</em> <a href="https://twitter.com/SapienzaCrypto">@SapienzaCrypto</a>.
<br>
<em>Google Group:</em> <a href="https://groups.google.com/u/2/a/uniroma1.it/g/sapienzacrypto">SapienzaCrypto</a>.

<h2>Grading</h2>
Written exam. The written exam lasts 3 hours and consists of 3 exercises and 3 open questions. Books, notes and electronic devices are not allowed during the exam.

<h2>References</h2>
We will not follow a single book; the following textbooks are suggested as reference and for deeper study:
<ul>
<li>[1] Daniele Venturi, <em><a href="http://www.springer.com/us/book/9788847024809">Crittografia nel Paese delle Meraviglie</a></em>, Springer, Collana di Informatica, 2012.
</li>
<li>[2] Jonathan Katz and Yehuda Lindell, <em><a href="https://www.crcpress.com/Introduction-to-Modern-Cryptography-Second-Edition/Katz-Lindell/p/book/9781466570269">Introduction to Modern Cryptography</a></em>, CRC Press, Second Edition, 2014.
</li>
<li>[3] Jonathan Katz, <em><a href="http://www.springer.com/us/book/9780387277110">Digital Signatures</a></em>, Springer, 2010.
</li>
<li>[4] Salil P. Vadhan, <em><a href="http://www.nowpublishers.com/article/Details/TCS-010">Pseudorandomness</a></em>, Foundations and Trends in Theoretical Computer Science, Vol. 7, Issue 1-3, 2012. Freely available <a href="http://people.seas.harvard.edu/~salil/pseudorandomness/">here</a>.
</li>
<li>[5] Jonathan Katz, Lecture Notes for a course on <em><a href="http://www.cs.umd.edu/~jkatz/gradcrypto2/">Advanced Topics in Cryptography</a></em>, (Sping 2004). Lecture 9 and Lecture 10 are about the Cramer-Shoup PKE scheme.
</li>
<li>[6] Sanjit Chatterjee and Palash Sarkar, <em><a href="https://www.springer.com/la/book/9781441993823">Identity-Based Encryption</a></em>, Springer, 2011.
</li>
</ul>
You may also find useful the following lecture notes from a past edition of the course (although not reviewed by myself):
<ul>
<li>[7] Simone Bianco, <em><a href="https://github.com/Exyss/university-notes/raw/main/Master/Cryptography/Cryptography.pdf">Lecture Notes for the Cryptography Course</a></em>, Sapienza University of Rome, A. Y. 2025/2026 (work in progress).
</li>
</ul>

<h2>Exams</h2>
The exam dates for academic year 2025/2026 are indicated below. Please always register via Infostud.
<br>
<u><em>Exam 1</em></u>. Date: 13/01/26. Aula: 3L (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame01_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 2</em></u>. Date: 10/02/26. Aula: 3L (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame02_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 3</em></u>. Reserved to part-time and working students (you must make a formal request to the secretariat; registration in Infostud is still required). Date: TBA. Aula: TBA. Time: TBA. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame03_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 4</em></u>. Date: 09/06/26. Aula: 3L (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame04_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 5</em></u>. Date: 14/07/26. Aula: 3L (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame05_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 6</em></u>. Date: 08/09/26. Aula: 3L (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame06_2526_scores.pdf">pdf</a>].
<br>
<u><em>Exam 7</em></u>. Reserved to part-time and working students (you must make a formal request to the secretariat; registration in Infostud is still required). Date: TBA. Aula: TBA. Time: TBA. <em>Scores</em> [<a href="https://dventuri83.github.io/assets/pdf/crypto_esame07_2526_scores.pdf">pdf</a>].

<h2>Announcements</h2>
<u>20/09/2025:</u> The course will start on September 23, 2025.
<br>
<u>02/10/2025:</u> Due to the national strike announced for tomorrow, the lecture on October 3 will be exceptionally remote at <a href="https://uniroma1.zoom.us/j/84580904785?pwd=XuEpGhYpm650li6wVU0jmqny7rIxPq.1">this link</a>.
<br>
<u>30/10/2025:</u> The lecture on 04/11/2025 will not take place.
<br>
<u>13/11/2025:</u> Due to the transportations strike announced for tomorrow, the lecture on November 14 will take place in person but also exceptionally be streamed at <a href="https://uniroma1.zoom.us/j/81263907289?pwd=2UOa8FQtiBNCWtv01D7BFPrrRV4Is4.1">this link</a>.
<br>
<u>27/11/2025:</u> Due to the transportations strike announced for tomorrow, the lecture on November 28 will be exclusively remote at <a href="https://uniroma1.zoom.us/j/85474176836?pwd=ODU8pjAHFJSyZOKKylO71AlwIDoZEh.1">this link</a>.
<br>
<u>03/12/2025:</u> The students are invited to express their preference about the last topic to be covered in the final lectures of the course. Please vote only once using <a href="https://forms.gle/yo4HpH77DvUZTLHg9">this link</a>.
<br>
<u>11/12/2025:</u> Due to the national strike announced for tomorrow, the lecture on December 12 will take place in person but also exceptionally be streamed at at <a href="https://uniroma1.zoom.us/j/82414082275?pwd=2jT1zMRzmdcDBdQQCjzGFirU62H2dH.1">this link</a>.

<h2>Lectures</h2>
<table>
    <thead>
        <tr>
            <th>Date</th>
            <th>Topics</th>
            <th>References</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Lecture 1 23/09/25</td>
            <td>Overview of the course. Definition of secret-key encryption (SKE). Definition of perfect secrecy. The one-time pad and Shannon's impossibility result.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture01_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 2 26/09/25</td>
            <td>Equivalent notions of perfect secrecy. Definition of statistically-secure (one-time) MACs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture02_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 3 30/09/25</td>
            <td>Constructions of pairwise independent hash functions and one-time statistically secure MACs. Randomness extraction. Impossibility of randomness extraction from a single min-entropy source. Definition of seeded extractors.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture03_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 4 03/10/25</td>
            <td>Leftover hash lemma. Beginning of computational security.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture04_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 5 07/10/25</td>
            <td>Definition and examples of one-way functions. Definition of pseudorandom generators (PRGs). Proof that one bit of stretch implies unbounded polynomial stretch. Constructions of real-world PRGs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture05_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 6 10/10/25</td>
            <td>Hard-core predicates and the Goldreich-Levin theorem.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture06_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 7 14/10/25</td>
            <td>Definition of one-time computationally secure and chosen-plaintext attacks (CPA) secure SKE. Construction of one-time computationally secure SKE from any PRG. Definition of pseudorandom functions (PRFs).</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture07_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 8 17/10/25</td>
            <td>Constructing PRFs from OWFs: The GGM construction and its proof of security.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture08_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 9 21/10/25</td>
            <td> Modes of operation for SKE. CPA security of the CTR mode. Definition of universal unforgeability under chosen-message attacks (UFCMA) for MACs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture09_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 10 24/10/25</td>
            <td>Proof that PRFs imply UFCMA MACs for FIL messages. Domain extension for MACs. Universal hashing and CBC-MAC.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture10_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 11 28/10/25</td>
            <td>Definition of CCA security for SKE. Combining encryption and authentication.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture11_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 12 31/10/25</td>
            <td>Exercises.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture12_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 13 07/11/25</td>
            <td>Blockciphers: DES and AES. Feistel networks and substitution-permutation networks.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture13_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 14 11/11/25</td>
            <td>Collision-resistant hash functions. The Merklee-Damgaard paradigm. Building compression functions.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture14_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 15 14/11/25</td>
            <td>Brush-up on number theory.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture15_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>                                                             
        <tr>
            <td>Lecture 16 18/11/25</td>
            <td>The Diffie-Hellmann key exchange. Symmetric cryptography using number theory.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture16_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>     
        <tr>
            <td>Lecture 17 21/11/25</td>
            <td>Public-key encryption. The ElGamal PKE.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture17_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 18 25/11/25</td>
            <td>RSA PKE. Digital signatures and universal unforgeability under chosen-message attacks. Public key infrastructures. Full-domain hash signatures and the random oracle model.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture18_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 19 28/11/25</td>
            <td>Identification schemes and passive security. The Schnorr protocol. Definitions of honest-verifier zero knowledge and special soundness.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture19_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 20 02/12/25</td>
            <td>Proof that honest-verifier zero knowledge and special soundness imply passive security. Fiat-Shamir signatures.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture20_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 21 05/12/25</td>
            <td>Lattices. The short integer solution (SIS) problem and the learning with errors (LWE) problem.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture21_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 22 09/12/25</td>
            <td>Regev's PKE. Lattice trapdoors. Signatures from lattices.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture22_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 23 12/12/25</td>
            <td>Identity-based encryption: definitions and constructions.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture23_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <!---                                                           
        <tr>
            <td>Lecture 24 16/12/25</td>
            <td>Identity-based encryption: applications.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture24_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 25 19/12/25</td>
            <td>Exercises.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture25_2526.pdf" target="_blank">PDF</a>]</td>
        </tr>
        --->
    </tbody>
</table>
