---
layout: page
title: Data Privacy and Security (Fall 2024)
description: Master's Degree in Data Science
img: assets/img/dps.jpg
importance: 1
category: work
related_publications: true
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dps.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h2>Syllabus</h2>
The course is meant to cover an overview of modern techniques aimed at protecting data privacy and security in digital applications. Below is a tentative list of topics.
<br><br>
<em>Introduction to cryptography:</em>
<ul>
<li> Confidential communication, secret-key and public-key encryption.
</li>
<li> Authentic communication, cryptographic hashing, message authentication codes and digital signatures.
</li>
<li> Key exchange protocols and TLS.
</li>
<li> Post-quantum cryptography. Fully-homomorphic encryption.</li>
</ul>

<em>Differential Privacy:</em>
<ul>
<li> Approximate and pure differential privacy. Properties.
</li>
<li> Examples of differentially-private mechanisms: randomized responses, the Laplace mechanism, the Gaussian mechanism, the exponential mechanism.
</li>
<li> Lower bounds on differentially-private mechanisms.
</li>
</ul>

<em>Blockchain:</em>
<ul>
<li> The Bitcoin protocol.
</li>
<li> Ethereum and smart contracts.
</li>
<li> Altcoins (Algorand, Cardano, ZCash, ...).
</li>
</ul>

<em>Secure Computation:</em>
<ul>
<li> Two-party and multi-party computation.
</li>
<li> Yao's garbled circuits.
</li>
<li> MPC with honest majority.
</li>
</ul>

<h2>Logistics</h2>
<p style="color:red;"><b> Important: </b>The lectures are offered exclusively in-person (with no registration taking place). </p>
<em>Lecture time:</em> Tuesday (15:00 - 17:00) and Thursday (12:00 - 15:00).
<br>
<em>Location:</em> Room A2 - Via Ariosto 25, Rome.
<br>
<em>Twitter:</em> <a href="https://twitter.com/SapienzaCrypto">@SapienzaCrypto</a>.
<br>
<em>Google Group:</em> <a href="https://groups.google.com/u/2/a/uniroma1.it/g/sapienzacrypto">SapienzaCrypto</a>.

<h2>Grading</h2>
Student's presentation (30%), oral exam (70%).

<h2>Course Slides</h2>
<ul>
<li> Course info [<a href="https://danieleventuri.altervista.org/files/00_Course_Info.pdf">pdf</a>].
</li>
<li> Chapter 1: Secret-key cryptography [<a href="https://danieleventuri.altervista.org/files/01_Crypto_101_Sym.pdf">pdf</a>].
</li>
<li> Chapter 2: Public-key cryptography [<a href="https://danieleventuri.altervista.org/files/02_Crypto_101_Asym.pdf">pdf</a>].
</li>
<li> Chapter 3: Applications [<a href="https://danieleventuri.altervista.org/files/03_Crypto_101_Apps.pdf">pdf</a>].
</li>
<li> Chapter 4: Big data and cloud cryptography [<a href="https://danieleventuri.altervista.org/files/04_BigData_Cloud.pdf">pdf</a>].
</li>
<li> Chapter 5: Differential privacy [<a href="https://danieleventuri.altervista.org/files/05_Diff_Priv.pdf">pdf</a>].
</li>
<li> Chapter 6: Bitcoin [<a href="https://danieleventuri.altervista.org/files/06_Bitcoin.pdf">pdf</a>].
</li>
<li> Chapter 7: Alternative currencies [<a href="https://danieleventuri.altervista.org/files/07_Alt_Curr.pdf">pdf</a>].
</li>
<li> Chapter 8: Secure Multiparty Computation [<a href="https://danieleventuri.altervista.org/files/08_MPC.pdf">pdf</a>].
</li>
</ul>

<h2>References</h2>
While we will not follow a single book; the following sources are suggested as reference. However, only the material included in the slides will be part of the oral exam.
<ul>
<li> Daniele Venturi. <em><a href="http://www.springer.com/us/book/9788847024809">Crittografia nel Paese delle Meraviglie</a></em>, Springer, Collana di Informatica, 2012.
</li>
<li> Jonathan Katz, Yehuda Lindell. <em><a href="https://www.crcpress.com/Introduction-to-Modern-Cryptography-Second-Edition/Katz-Lindell/p/book/9781466570269">Introduction to Modern Cryptography</a></em>, CRC Press, Second Edition, 2014.
</li>
<li> [12] Salil Vadhan. <em><a href="https://www.springer.com/gp/book/9783319570471">The Complexity of Differential Privacy</a></em>, Chapter 7 of Tutorials on the Foundations of Cryptography, Yehuda Lindell Ed., Springer, 2017.
</li>
<li> [24] Carmit Hazay and Yehuda Lindell. <em><a href="http://www.springer.com/la/book/9783642143021">Efficient Secure Two-Party Protocols</a></em>, Springer, 2010.
</li>
<!--
<li> [3] Dan Boneh, Matthew Franklin. <em><a href="https://crypto.stanford.edu/~dabo/papers/bfibe.pdf">Identity-Based Encryption from the Weil Pairing</a></em>, SIAM J. of Computing, Vol. 32, No. 3, 2003.
</li>
<li> [4] Jonathan Katz, Ji Sun Shin. <em><a href="https://eprint.iacr.org/2005/461">Parallel and Concurrent Security of the HB and HB+ Protocols</a></em>, EUROCRYPT 2006.
</li>
<li> [5] Hugo Krawczyk. <em><a href="http://webee.technion.ac.il/~hugo/sigma-pdf.pdf">SIGMA: The "SIGn-and-MAc" Approach to Authenticated Diffie-Hellman and its Use in the IKE Protocols</a></em>, CRYPTO 2003.
</li>
<li> [6] Ari Juels, Thomas Ristenpart. <em><a href="https://eprint.iacr.org/2014/155">Honey Encryption: Security Beyond the Brute-Force Bound</a></em>, EUROCRYPT 2014.
</li>
<li> [7] Dan Boneh, Amit Sahai, Brent Waters. <em><a href="https://eprint.iacr.org/2010/543">Functional Encryption: Definitions and Challenges</a></em>, Theory of Cryptography Conference 2011.
</li>
<li> [8] Vipul Goyal, Omkant Pandey, Amit Sahai, Brent Waters. <em><a href="https://eprint.iacr.org/2006/309">Attribute-Based Encryption for Fine-Grained Access Control of Encrypted Data</a></em>, CCS 2006.
</li>
<li> [9] Shai Halevi. <em><a href="https://www.springer.com/gp/book/9783319570471">Homomorphic Encryption</a></em>, Chapter 5 of Tutorials on the Foundations of Cryptography, Yehuda Lindell Ed., Springer, 2017.
</li>
<li> [10] Bryan Parno, Mariana Raykova, Vinod Vaikuntanathan. <em><a href="">How to Delegate and Verify in Public: Verifiable Computation from Attribute-based Encryption</a></em>, Theory of Cryptography Conference 2012.
</li>
<li> [11] Hovav Shacham, Brent Water. <em><a href="https://hovav.net/ucsd/dist/verstore.pdf">Compact Proofs of Retrievability</a></em>,  Journal of Cryptology 26(3): 442-483 (2013).
</li>

<li> [13] Satoshi Nakamoto. <em><a href="https://bitcoin.org/bitcoin.pdf">Bitcoin: A Peer-to-Peer Electronic Cash System</a></em>, Bitcoin white paper.
</li>
<li> [14] Meni Rosenfeld. <em><a href="">Analysis of Bitcoin Pooled Mining Reward Systems</a></em>, CoRR abs/1112.4980, 2011.
</li>
<li> [15] Ittay Eyal, Emin Gun Sirer. <em><a href="https://bitcoin.org/bitcoin.pdf">Majority Is Not Enough: Bitcoin Mining Is Vulnerable</a></em>, Financial Cryptography 2014.
</li>
<li> [16] Dongning Guo and Ling Ren. <em><a href="https://arxiv.org/abs/2203.06357">Bitcoin's Latency--Security Analysis Made Simple.</a></em>, ACM Advances in Financial Cryptography 2022.
</li>
<li> [17] Joseph Poon, Thaddeus Dryja. <em><a href="https://lightning.network/lightning-network-paper.pdf">The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments</a></em>, Lightning Network white paper, 2016.
</li>
<li> [18] Aggelos Kiayias, Alexander Russell, Bernardo David, Roman Oliynykov. <em><a href="https://eprint.iacr.org/2016/889.pdf">Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol</a></em>, CRYPTO 2017.
</li>  
<li> [19] Silvio Micali. <em><a href="https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Distributed%20Computation/BYZANTYNE%20AGREEMENT%20MADE%20TRIVIAL.pdf">Byzantine Agreement Made Simple</a></em>, Innovations in Theoretical Computer Science 2017.
</li>
<li> [20] Jing Chen, Silvio Micali. <em><a href="https://arxiv.org/abs/1607.01341">Algorand</a></em>, technical paper, 2017.
</li>
<li> [21] Stefan Dziembowski, Sebastian Faust, Vladimir Kolmogorov, Krzysztof Pietrzak. <em><a href="https://eprint.iacr.org/2013/796.pdf">Proofs of Space</a></em>, CRYPTO 2015.
</li>  
<li> [22] Sunoo Park, Albert Kwon, Georg Fuchsbauer, Peter Gazi, Joel Alwen, Krzysztof Pietrzak. <em><a href="https://eprint.iacr.org/2015/528.pdf">SpaceMint: A Cryptocurrency Based on Proofs of Space</a></em>, Financial Cryptography 2018.
</li>  
<li> [23] Eli Ben-Sasson, Alessandro Chiesa, Christina Garman, Matthew Green, Ian Miers, Eran Tromer, Madars Virza. <em><a href="http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf">Zerocash: Decentralized Anonymous Payments from Bitcoin</a></em>, IEEE Symposium on Security and Privacy, 2014.
</li>

<li> [25] Marcin Andrychowicz, Stefan Dziembowski, Daniel Malinowski, Lukasz Mazurek. <em><a href="https://eprint.iacr.org/2013/784.pdf">Secure Multiparty Computations on Bitcoin</a></em>, IEEE Symposium on Security and Privacy 2014.
</li>  
<li> [26] Giuseppe Ateniese, Bernardo Magri, Daniele Venturi, Ewerton Andrade. <em><a href="https://eprint.iacr.org/2016/757">Redactable Blockchain -- or -- Rewriting History in Bitcoin and Friends</a></em>, IEEE European Symposium on Security and Privacy, 2017.
</li>
-->
</ul>

<h2>Students' Projects</h2>
As part of the exam, students are required to present a research paper or solve a small project and present the solution during the exam. Reach out to me by email after choosing a topic of preference (among those covered in the course) in order to get an assignment.
<!--
<br>
<h4><font color="black">List of Projects (By Topic)</font></h4>
The following is a good reference for solving some of the projects below using Python:
<br><br>
Al Sweigart, <em><a href="http://inventwithpython.com/hackingciphers.pdf">Hacking Secret Ciphers with Python</a></em>, Creative Commons, 2013.
<br><br>
<ul>
<li><u>Secret-Key Cryptography:</u>
<ul>
<li> <b>Inside Rijndael</b>. The goal of this project is to gain a better understanding of the arithmetic in Rijndael's finite field (underlying the AES blockcipher). Write a program (using your favourite programming language) able to perform the basic operations in <a href="https://en.wikipedia.org/wiki/Finite_field_arithmetic#Rijndael's_finite_field">Rijndael's finite field</a>, using the <a href="https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm#Polynomial_extended_Euclidean_algorithm">extended Euclidean algorithm</a> for computing the multiplicative inverse of a polynomial. Next, use your program to re-generate the AES S-Boxes (for both encryption and decryption).
</li>
<li><s><b>Ancient Ciphers</b>. The goal of this project is to learn how to implement and break some of the blockciphers commonly used in the past. Write a program (using your favourite programming language) implementing encryption/decryption, as well as efficient attacks, on the following blockciphers: The <a href="https://en.wikipedia.org/wiki/Caesar_cipher">Caesar Cipher</a>, the <a href="https://en.wikipedia.org/wiki/Transposition_cipher">Transposition Cipher</a>, the <a href="https://en.wikipedia.org/wiki/Affine_cipher">Affine Cipher</a>, and the <a href="https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher">Vigenere Cipher</a>.</s>
</li>
</ul>
<li><u>Public-Key Cryptography:</u>
<ul>
<li><s><b>Primality Testing</b>. The goal of this project is to better understand the task of primality testing. Write a program (using your favourite programming language) implementing the following primality testing algorithms: The <a href="https://en.wikipedia.org/wiki/Fermat_primality_test">Fermat's Test</a> and the <a href="https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test">Miller-Rabin Test</a>. Compare the performances of the two tests.</s>
</li>
<li><s><b>Inside RSA</b>. The goal of this project is to better understand the number theory behind the RSA cryptosystem. Write programs (using your favourite programming language) for the following tasks: (i) Computing the gcd; (ii) Computing the modular multiplicative inverse (when it exists); (iii) Encryption/Decryption with Textbook RSA; (iv) Signature with Full-Domain Hash.</s>
</li>
</ul>
<li><u>Differential Privacy:</u>
<ul>
<li> <b>Experiments with Differential Privacy.</b> This project can be chosen <u>by an arbitrary number of students</u>, Implement some of the differentially private mechanisms studied in class (using any programming language of your choice), and apply it to solve a toy use case which is relevant for data science.
</li>
</ul>
<li><u>Blockchain:</u>
<ul>
<li> <b>Ethereumlab.</b> Learn how to implement a secure smart contract. This project can be chosen <u>by an arbitrary number of students</u>, with the idea that each student should implement a different smart contract for a toy application of his/her choice. Reference: <em><a href="https://remix.ethereum.org">Remix</a></em>.
</li>
</ul>
<li><u>Secure Computation:</u>
<ul>
<li> <b>SCAPI.</b> Learn how to implement secure multiparty computation protocols (in java). This project can be chosen by an arbitrary number of students, with the idea that each student should implement a protocol for a different application of his/her choice. Reference: <em><a href="https://eprint.iacr.org/2012/629">SCAPI: The Secure Computation Application Programming Interface</a></em>.
</li>
</ul>
</li>
<li><u>Bonus Topics:</u>
<ul>
<li> <b>Steganography.</b> The goal of this project is to get the basics about steganography and steganalysis. Write programs (using your favourite programming language) for the following  tasks: (i) Encrypt/decrypt using the LSB algorithm; (ii) Encrypt/decrypt using JSteg; (iii) Steganalysis of JSteg; (iv) Steganalysis of LSB.
</li>
</ul>
-->

<h2>Exams</h2>
The exam dates for academic year 2024/2025 will be displayed here when available.
<!--
<u><em>Exam 1</em></u>. Date: 11/01/24. Aula 1 (RM018). Time: 09:00-12:00. <em>Scores</em> [<a href="files/crypto_esame01_2324_scores.pdf">pdf</a>].
<br>
<u><em>Exam 2</em></u>. Date: 07/02/24. Aula 1 (RM018). Time: 09:00-12:00. <em>Scores</em> [<a href="files/crypto_esame02_2324_scores.pdf">pdf</a>].
<br>
<u><em>Exam 3</em></u>. Reserved to part-time and working students (you must make a formal request to the secretariat; registration in INFOSTUD is still required). Date: 08/04/24. Aula: 2L (Via del Castro Laurenziano 7a). Time: 09:30-12:30. <em>Scores</em> [<a href="files/crypto_esame03_2324_scores.pdf">pdf</a>].
<br>
<u><em>Exam 4</em></u>. Date: 05/06/24. Aula 3 (RM018). Time: 08:30-11:30. <em>Scores</em> [<a href="files/crypto_esame04_2324_scores.pdf">pdf</a>].
<br>
<u><em>Exam 5</em></u>. Date: 04/07/24. Aula 1 (RM018). Time: 09:30-12:30. <em>Scores</em> [<a href="files/crypto_esame05_2324_scores.pdf">pdf</a>].
<br>
<u><em>Exam 6</em></u>. Date: 10/09/24. Aula 2 (RM018). Time: 09:30-12:30. <em>Scores</em> [<a href="files/crypto_esame06_2324_scores.pdf">pdf</a>].
-->

<h2>Announcements</h2>
<u>18/09/2024:</u> The course will start on September 26th, 2024.
<!--
<br>
<u>25/09/2023:</u> The lecture on 29/09/2023 has been canceled due to personal reasons.  
<br>
<u>19/10/2023:</u> The students are invited to join the next appointment in the series of seminars <a href="https://www.di.uniroma1.it/it/notizie/seminari/distinguished-lectures">Distinguished Lectures</a>, hosted by the Computer Science Department. The talk is on 23/10/23 and starts at 12pm in Viale Regina Elena 295, Building D, Room 101.
<br>
<u>03/11/2022:</u> The lecture on 04/11/2022 will take place remotely via <a href="https://uniroma1.zoom.us/j/93815848058?pwd=Q0swODd3WlY0R095Sk0rWGg0bDZUQT09">Zoom</a>. The lecture will be recorded, and the recording will be made available for 7 days.
<br>
<u>04/11/2022:</u> The recording of the lecture on 04/11/2022 can be found at <a href="https://uniroma1.zoom.us/rec/share/wosM8VnwbhPK7xx38T8dOp_9fbDxRKAzvQcNIxOtz4OIQBT5lS4EUaIX7AFKIVwF.eL0lB1s_xz4NVuft">this link</a>. The passcode is 9n9TeTQ$ (valid for 7 days).
<br>
<u>06/11/2022:</u> The lecture on 08/11/2022 will take place remotely via <a href="https://uniroma1.zoom.us/j/93522071441?pwd=cUdkNVJvWlhDdzVMMzRTQlF0blBiZz09">Zoom</a>. The lecture will be recorded, and the recording will be made available for 7 days.
<br>
<u>08/11/2022:</u> The recording of the lecture on 08/11/2022 can be found at <a href="https://uniroma1.zoom.us/rec/share/SalF2NMbPlkbzY0bhGdkRpyCicPVTVy2fJP7GarfyicZfm-q_TFDQn-xo-QQjtI.3YiznNwWRs8Ib1I-">this link</a>. The passcode is ?L5Ythp% (valid for 7 days).
<br>
<u>10/11/2022:</u> The lecture on 11/11/2022 will take place remotely via <a href="https://uniroma1.zoom.us/j/99385097522?pwd=Q3dETWtEbnd4Rmk5UjBqZmNlKzNFQT09">Zoom</a>. The lecture will be recorded, and the recording will be made available for 7 days.
<br>
<u>11/11/2022:</u> The recording of the lecture on 11/11/2022 can be found at <a href="https://uniroma1.zoom.us/rec/share/xdWusdsoOXq4CyWvAEjwLAQwNuUQCXTlbdIIWrjD1Xxy5OrsC7ZoBMD5ZDAPBnst.MvOWjyLl0OchhRrE">this link</a>. The passcode is B%3fmK@d (valid for 7 days).
<br>
<u>05/12/2022:</u> On 14/12/22, Prof. Vitaly Shmatikov (Cornell Tech) will give the talk "Can we trust machine learning models?". The seminar will take place in Room 201 (Viale Regina Elena 295, Bulding D), from 3pm to 4pm. See <a href="">this link</a> for additional info.  
<br>
<u>07/12/2022:</u> The lecture on 13/12/22 will start regularly at Aula Alfa at 8am. We will move to Aula Seminari during the break (at around 9.15am).
<br>
<u>21/12/2022:</u> The lecture on 23/12/2022 (by Daniele Friolo) will take place remotely via <a href="https://uniroma1.zoom.us/j/99264063517?pwd=UTA0Z0xhUzZLYVp0SmN6WDhpMEppQT09">Zoom</a>.
<br>
<u>08/10/2021:</u> The recording of the lecture on 08/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/k7qiWGYVQw1iO5HPdLadbSm-rmq29WvcpP3y-8eL2W3nDdsQmdWMGbwujXMNSR07.RHvpD52fq21jxtQD">this link</a> The passcode is d3+.gn!# (valid for 7 days).
<br>
<u>13/10/2021:</u> The recording of the lecture on 13/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/nD2BxVd_ukRS6JFCTSWDxdOfReQCJFhgwTUB9KG_oUc0Eyw8WX7JuS7-JHX2rvGr.u2fGQZby3bliGrOW">this link</a> The passcode is X$k3$A7X (valid for 7 days).
<br>
<u>15/10/2021:</u> The recording of the lecture on 015/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/bGTNMOl-UFPd36KQBPoiMIRs_gzxseIoQ0mdCvCckc6ZYmxLS7nOQnnDXAWeEtjR.fHvp1COibp4SS0zJ">this link</a> The passcode is &#38;Gs4gXRn (valid for 7 days).
<br>
<u>20/10/2021:</u> The recording of the lecture on 20/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/wI8UyvGQ1RmYKR4XlVM3LBCymTj4xnVx2mewGKbAd-cMBgf7AZ3aYkgOT2AgekkV.wx-qdPTB3yh1X_oi">this link</a> The passcode is 7+y*JY4i (valid for 7 days).
<br>
<u>25/10/2021:</u> The recording of the lecture on 22/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/LiTj9BntxPVKmOBs_ekccJroIJGxOBhLsy5YTuBN5FdEGCpKoRGpGidMuQfnuXlG.5zX3x9fcqCMaDMkk">this link</a> The passcode is &#38;V6kYiBD (valid for 7 days).
<br>
<u>28/10/2021:</u> The recording of the lecture on 27/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/zbiuFc_W0w3ncStjvePCQESHgx87LRw4dMc9GW9T7CnKCK0PX8fToTP8sWGePs54.SyiUb8IsNtLjKRjs">this link</a> The passcode is X$mc@7C0 (valid for 7 days).
<br>
<u>29/10/2021:</u> The recording of the lecture on 29/10/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/ujCJxJT6v0hq1rqdgk03Y9c-b_3EqcLoLAYn4hksOlOdTdTOtOXIXuPy8v1tRgRb.qbw1eX1YEsy2Ef8y">this link</a> The passcode is 6Qc%lGZU (valid for 7 days).  
<br>
<u>03/11/2021:</u> The recording of the lecture on 03/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/DT_9pLb2i5w7onuq5F6HITmaPEJEBplR1KiLpQCFdpV9bqRCP6YU34TGUOPeLsIc.0cFjfqSYCqEBjypa">this link</a> The passcode is S37+1^R! (valid for 7 days).
<br>
<u>05/11/2021:</u> The recording of the lecture on 05/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/6pAJfT_yMpRTYt6wSjCEJUxzj1yIrr8CbuBNMkJshDHsS9uP8TrTI5WClPyPKfzq.7FIBBCF6RuhF0MGf">this link</a> The passcode is Rw4G$b4W (valid for 7 days).
<br>
<u>10/11/2021:</u> The recording of the lecture on 10/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/KNr-BqYonEbblNTkz_VVZ8UkThqP-DFILi2TTGNRwrMayrmF5XA8_9v2PsCbLYF8.ihW568RqOglRW1ut">this link</a> The passcode is asT%tso0 (valid for 7 days).
<br>
<u>12/11/2021:</u> The recording of the lecture on 12/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/lf6tF9DsEZgI8kC_tyg2TlQn8dRsZp3Ihp2x5JTsTObybA_yA5lEsg-_KnYFZyyZ.x8owIwPnnAtmdLjp">this link</a> The passcode is Fr%7K%R9 (valid for 7 days).
<br>
<u>17/11/2021:</u> The recording of the lecture on 17/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/843L5Fx2ubEWnnPtTrs15D_Hb8KFts_hHu-7_wKasdKFg8-WLwEyEsMg9FsfH2lX.NtVm-JE67snHrtJW">this link</a> The passcode is 6p$CiUd! (valid for 7 days).
<br>
<u>19/11/2021:</u> The recording of the lecture on 19/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/pvhnbgn6LrSLyab_Uhtj9F5oHAgtaZVMxKE_GQupYs_QRfN41fZVXC6bS9hHFwc.52US82UEJkTxLBub">this link</a> The passcode is r$kwH2Vj (valid for 7 days).
<br>
<u>24/11/2021:</u> The recording of the lecture on 24/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/u7yVUXRqVsFbPIngF8UQEkM7cUEy7z-MBfbr9eZqrRukhQkq8lkOj7PLNwACcU3_.5Lxvm9n_D28bNWPv">this link</a> The passcode is F8?5FTxx (valid for 7 days).
<br>
<u>30/11/2021:</u> The recording of the lecture on 26/11/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/mHCmHrmwYt-xOEPNenxSUcx44BPt1stWEyR-HtpDVXuP37Ytq5lQ7xO7Ur3aMyWq.kSse4EOXBkBHMOja">this link</a> The passcode is 2krBa*@r (valid for 7 days).
<br>
<u>01/12/2021:</u> The recording of the lecture on 01/12/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/L5AZL67jeTvQiP4I8otakIBUPc5NlylE1wZoMrO8PHSGGnoE3ZcX-awK6OFqrpzC.ri2eOvIRiUW6bvmE">this link</a> The passcode is VS?*v6F3 (valid for 7 days).
<br>
<u>03/12/2021:</u> The recording of the lecture on 03/12/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/BUK6PSRXXCK8-l926oKW5KutfpBCvHKyZWc6Zlx7Cgo5sLlijGCjxPEAgIADZ2tz.G29JjaWfmC2YGhd7">this link</a> The passcode is 0.HG2@hf (valid for 7 days).
<br>
<u>10/12/2021:</u> The recording of the lecture on 10/12/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/MnXRak8f-RnqxYxGBUbCkDK7oPhOtbmpfZNZehD8cu57nlD2s2wpt7kGo3B16CpX.ExkatcoO2KgVdEPC">this link</a> The passcode is R#6#cpCu (valid for 7 days).
<br>
<u>15/12/2021:</u> The recording of the lecture on 15/12/2021 can be found at <a href="https://uniroma1.zoom.us/rec/share/KwBD3PfgxPKdvTz8k_TPmilBWLqqo_wEgZcgOXfO2Sl8DJyFooQuOP6N1hY1XJR-.fVE821WAw5E3ISqn">this link</a> The passcode is YZnsVG$3 (valid for 7 days).
<br>
<u>02/01/2022:</u> Given the increasing number of covid-19 cases, the exams in January and February will take place remotely.
<br>
<u>24/08/2021:</u> Following Sapienza regulations, the exam in September will take place physically. Remote participation is also possible, in exceptional cases, after emailing the professor.
-->

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
            <td>Lecture 1 24/09/24</td>
            <td>TBA.</td>
            <td>TBA.</td>
        </tr>
        <!-- and so on... -->
    </tbody>
</table>
<!--
The whiteboard notes for each lecture can be downloaded by clicking on the corresponding lecture.
<br>
<br>
        <table class="alt">
        <colgroup>
        	<col span="1" style="width: 5%;">
        	<col span="1" style="width: 70%;">
        	<col span="1" style="width: 25%;">
        </colgroup>
            <tr>
                <th>Class/Date</th>
                <th>Topics Covered</th>
                <th>Readings</th>
            </tr>
            <tr>
                <td><a href="files/01_26092023.pdf">Lecture 1</a>, 26/09/23</td>
                <td>Introduction to the course. Secure communication: message confidentiality and integrity. Symmetric encryption and perfect secrecy. Equivalent notions of perfect secrecy. The one-time pad and Shannon's impossibility result.</td>
                <td>[2]: 2 <br> [1]: 2 <br> [7]: 1.1</td>
            </tr>
            <tr>
                <td><a href="files/02_03102023.pdf">Lecture 2</a>, 03/10/23</td>
                <td>Message Authentication Codes (MACs). Definition of statistically-secure (one-time) MACs. Pair-wise independent hashing: Definition and construction using modular arithmetic. Application to statistically-secure message authentication. Limits of statistically-secure MACs. The problem of randomness extraction, and definition of min-entropy. The von Neumann extractor. Impossibility of seedless extractors for min-entropy sources.</td>
                <td>[1]: 3<br>[2]: 4<br>[4]: 6<br>[7]: 1.2, 1.3</td>
            </tr>
			<tr>            
                <td><a href="files/03_06102023.pdf">Lecture 3</a>, 06/10/23</td>
                <td>Definition of seeded extractors. Leftover-hash lemma: Statement and proof.</td>
                <td>[4]: 6<br>[1]: 3 <br>[7]: 1.3</td>
            </tr>
            <tr>
                <td><a href="files/04_10102023.pdf">Lecture 4</a>, 10/10/23</td>
                <td>Computational security: Asymptotic security, negliglible and polynomial functions, PPT algorithms. One-Way Functions and Impagliazzo's worlds.</td>
                <td>[1]: 1, 3, 3<br>[2]: 3, 7<br>[7]: 2.1</td>
            </tr>
            <tr>
                <td><a href="files/05_13102023.pdf">Lecture 5</a>, 13/10/23</td>
                <td>Computational indistinguishability and hybrid arguments. Definition of Pseudo-Random Generators (PRGs). Definition of one-time computational security for Secret Key Encryption (SKE) and construction from any PRG.</td>
                <td>[1]: 3, 5<br>[2]: 3, 7<br>[7]: 2.2, 2.3</td>
            </tr>
            <tr>
                <td><a href="files/06_17102023.pdf">Lecture 6</a>, 17/10/23</td>
                <td>Definition of hard-core predicates. Goldreich-Levin theorem (statement). Proof that One-Way Permutations (OWPs) imply PRGs with one-bit stretch.</td>
                <td>[1]: 3<br>[2]: 3, 7<br>[7]: 2.4</td>
            </tr>
            <tr>
                <td><a href="files/07_20102023.pdf">Lecture 7</a>, 20/10/23</td>
                <td>Proof that one-bit stretch is sufficient to obtain arbitrary polynomial stretch.</td>
                <td>[1]: 5, 7<br>[2]: 4, 7<br>[7]: 2.3</td>
            </tr>
            <tr>
                <td><a href="files/08_24102023.pdf">Lecture 8</a>, 24/10/23</td>
                <td>Definition of Pseudorandom Functions (PRFs). Definition of chosen-plaintext attack (CPA) secure SKE and construction from any PRF family.</td>
                <td>[1]: 5<br>[2]: 3, 7<br>[7]: 3.1</td>
            </tr>
            <tr>
                <td><a href="files/09_27102023.pdf">Lecture 9</a>, 27/10/23</td>
                <td>Constructing PRFs from PRGs: The GGM construction. Modes of operation: ECB, CBC and CTR. Proof that CTR mode using a PRF yields a CPA secure SKE for variable length messages.</td>
                <td>[1]: 5<br>[2]: 3, 4<br>[7]: 3.1, 3.5</td>
            </tr>
            <tr>
                <td><a href="files/10_31102023.pdf">Lecture 10</a>, 31/10/23</td>
                <td>Message authentication codes in the computational setting: Unforgeability against chosen-message attacks. Proof that every PRF yields a fixed-input length MAC.</td>
                <td>[1]: 5, 7<br>[2]: 4, 7<br>[7]: 3.2</td>
            </tr>
            <tr>
                <td><a href="files/11_03112023.pdf">Lecture 11</a>, 03/11/23</td>
                <td>Domain extension for PRFs via almost-universal hash functions. Constructions of almost universal hash functions. CBC-MAC and Encrypted CBC-MAC.</td>
                <td>[1]: 7<br>[2]: 4<br>[7]: 3.3</td>
            </tr>
            <tr>
                <td><a href="files/12_07112023.pdf">Lecture 12</a>, 07/11/23</td>
                <td>Definition of chosen-ciphertext attack (CCA) secure SKE. Authenticated encryption and its relation to CCA security. Combining confidentiality and message integrity: Encrypt-then-MAC and proof of CCA security.</td>
                <td>[1]: 5<br>[2]: 3, 4<br>[7]: 3.4</td>
            </tr>  
            <tr>
                <td><a href="files/13_10112023.pdf">Lecture 13</a>, 10/11/23</td>
                <td>Pseudorandom permutations (PRPs) and Feistel networks.</td>
                <td>[1]: 5<br>[2]: 7<br>[7]: 3.5</td>
            </tr>   
            <tr>
                <td><a href="files/14_14112023.pdf">Lecture 14</a>, 14/11/23</td>
                <td>Exercises.</td>
                <td>--</td>
            </tr>
            <tr>
                <td><a href="files/15_17112023.pdf">Lecture 15</a>, 17/11/23</td>
                <td>More exercises.</td>
                <td>--</td>
            </tr>   
            <tr>
                <td><a href="files/16_21112023.pdf">Lecture 16</a>, 21/11/23</td>
                <td>Collision-resistant hash functions. The Merkle-Damgaard construction. Constructing secure compression functions: The Davies-Mayer construction and its security in the ideal cipher model.</td>
                <td>[1]: 4, 7<br>[2]: 4, 5<br>[7]: 3.6, 4.5</td>
            </tr>               
            <tr>
                <td><a href="files/17_24112023.pdf">Lecture 17</a>, 24/11/23</td>
                <td>Brush-up on number theory: Modular arithmetic, Euclidean algorithm, prime numbers. Integers factorization. Lagrange's theorem. Cyclic groups.</td>
                <td>[1]: 4, B, C<br>[2]: 5, 6, 8, B<br>[7]: 4.1, 4.2</td>
            </tr>
            <tr>
                <td><a href="files/18_28112023.pdf">Lecture 18</a>, 28/11/23</td>
                <td>The Discrete Logarithm (DL) problem. Diffie-Hellman key exchange. Computational Diffie-Hellman (CDH) and Decisional Diffie-Hellman (DDH) assumptions. Hardness of DDH. Simple number-theoretic constructions: OWPs from DL, PRGs and PRFs from DDH (Naor-Reingold).</td>
                <td>[1]: B, C<br>[2]: 8, B<br>[7]: 4.3, 4.4</td>
            </tr>        
            <tr>
                <td><a href="files/19_01122023.pdf">Lecture 19</a>, 01/12/23</td>
                <td>Public-Key Encryption (PKE): Syntax and CPA security. RSA as a public-key encryption (with mentions to PKCS #1 v1.5 and PKCS #2 v2.0).</td>
                <td>[1]: 6<br>[2]: 8, 11, 13<br>[7]: 5.1</td>
            </tr>
            <tr>
                <td><a href="files/20_05122023.pdf">Lecture 20</a>, 05/12/23</td>
                <td>PKE from Tradpdoor Permutations (TPDs). RSA as a trapdoor permutation and the RSA assumption. Elgamal PKE and its CPA security from the DDH assumption.</td>
                <td>[1]: B, 6<br>[2]: 11, 13<br>[7]: 5.2</td>
            </tr>
            <tr>
                <td><a href="files/21_12122023.pdf">Lecture 21</a>, 12/12/23</td>
                <td>Signature schemes. The random oracle model (ROM). Constructing signatures from TPDs (Full-Domain Hash). Identification (ID) schemes.</td>
                <td>[1]: 4, 8, 13<br>[2]: 5, 12<br>[3]: 6, 7<br>[7]: 6.2</td>
            </tr>
            <tr>
                <td><a href="files/22_15122023.pdf">Lecture 22</a>, 15/12/23</td>
                <td>Passive security and canonical ID schemes. The Fiat-Shamir transform.</td>
                <td>[1] 13<br>[2]: 12<br>[3]: 8<br>[7]: 6.2</td>
            </tr>
            <tr>
                <td><a href="files/23_19122023.pdf">Lecture 23</a>, 19/12/24</td>
                <td>Excercises.</td>
                <td>-</td>
            </tr>
            <tr>
                <td><a href="files/24_22122023.pdf">Lecture 24</a>, 22/12/24</td>
                <td>Definition of Honest Verifier Zero Knowledge (HVZK) and Special Soundness (SS) for canonical ID schemes. Proof that HVZK plus SS imply passive security. Canonical ID schemes from Discrete Log.</td>
                <td>[1] 13<br>[2]: 12<br>[3]: 8<br>[7]: 6.2</td>
            </tr>
            <!--                                                                       
            <tr>
                <td>Lecture 19, 02/12/22</td>
                <td>Cramer-Shoup encryption.</td>
                <td>[1]: 6<br>[5]<br>[7]: 5.3</td>
            </tr>
            <tr>
                <td>Lecture 20, 06/12/22</td>
                <td>Cramer-Shoup encryption (continued).</td>
                <td>[1]: 6<br>[5]<br>[7]: 5.3</td>
            </tr>            
            <tr>
                <td>Lecture 24, 23/12/22</td>
                <td>Guest lecture (Daniele Friolo): Public-key encryption with advanced features.</td>
                <td>-</td>
            </tr>                     
			<tr>
                <td>Lecture 23, 20/12/22</td>
                <td>Signatures are in Minicrypt (without proof). Bilinear maps. Waters signature scheme and its proof of security from the CDH assumption on bilinear groups. Public-Key Infrastructure (PKI).</td>
                <td>[1] 10.1<br>[2]: 10<br>[3]: 5.1, 5.3<br>[7]: 6.1</td>
            </tr>
            <tr>
                <td>Lecture 24, 23/12/22</td>
                <td>Identity-Based Encryption (IBE): Syntax and definition of (selective) IND-ID-CPA security. Decisional Bilinear Diffie-Hellmann (DBDH) assumption. Selectively secure IBE from DBDH.</td>
                <td>[6]: 1, 2.2, 2.3</td>
            </tr>
            <tr>
                <td>Lecture 25, 10/12/21</td>
                <td>Black-box construction of UF-CMA signatures from IND-ID-CPA secure IBE. Black-box construction of CCA secure PKE from selectivly IND-ID-CPA secure IBE.</td>
                <td>[6]: 5, 6</td>
            </tr>
		</table>             
-->
