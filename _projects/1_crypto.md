---
layout: page
title: Cryptography (Fall 2024)
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
<p style="color:red;"><b> Important: </b>The lecture on 08/11/24 will be exceptionally remote at <a href="https://uniroma1.zoom.us/j/89487521223?pwd=KzrfMElWv3v7c6bOi7BGXR9U9rCw49.1">this link</a>.</p>
<em>Lecture time:</em> Tuesday (8:00am - 11:00am) and Friday (11:00am - 13:00am).
<br>
<em>Location:</em> The lectures on Tuesday take place in Aula Magna - Viale Regina Elena 295. The lectures on Friday take place in Aula 1L - Via del Castro Laurenziano 7a.
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
<li>[7] Michele Laurenti, <em><a href="https://github.com/asmeikal/crypto16/tree/master/notes">Lecture Notes for the Cryptography Course</a></em>, Sapienza University of Rome, A. Y. 2016/2017.
</li>
</ul>

<h2>Exams</h2>
Below are the exam dates for academic year 2024/2025. Please register via Infostud.

<u><em>Exam 1</em></u>. Date: 13/01/25. Aula 3 (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="files/crypto_esame01_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 2</em></u>. Date: 03/02/25. Aula 1 (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="files/crypto_esame02_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 3</em></u>. Reserved to part-time and working students (you must make a formal request to the secretariat; registration in Infostud is still required). Date: TBA. Aula: TBA. Time: TBA. <em>Scores</em> [<a href="files/crypto_esame03_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 4</em></u>. Date: 09/06/25. Aula 1 (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="files/crypto_esame04_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 5</em></u>. Date: 14/07/25. Aula 1 (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="files/crypto_esame05_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 6</em></u>. Date: 08/09/25. Aula 1 (RM018). Time: 10:00-13:00. <em>Scores</em> [<a href="files/crypto_esame06_2425_scores.pdf">pdf</a>].
<br>
<u><em>Exam 7</em></u>. Reserved to part-time and working students (you must make a formal request to the secretariat; registration in Infostud is still required). Date: TBA. Aula: TBA. Time: TBA. <em>Scores</em> [<a href="files/crypto_esame07_2425_scores.pdf">pdf</a>].

<h2>Announcements</h2>
<u>12/09/2024:</u> The course will start on September 24th, 2024. Due to the ongoing construction works in Aula Magna, the lecture on 24/09/2024 will take place in Aula IV Matematica - Edificio Castelnuovo, Città Universitaria.
<br>
<u>30/09/2024:</u> Due to the ongoing construction works in Aula Magna, the lecture on 01/10/2024 will take place in Aula 301 - Palazzina D, Viale Regina Elena 295, 00161 Rome.
<br>
<u>02/10/2024:</u> Due to the ongoing construction works in Aula Magna, the lecture on 08/10/2024 will take place in Aula 301 - Palazzina D, Viale Regina Elena 295, 00161 Rome.
<br>
<u>07/11/2024:</u> Due to the national strike announced for tomorrow, the lecture on November 8th will be exceptionally remote at <a href="https://uniroma1.zoom.us/j/89487521223?pwd=KzrfMElWv3v7c6bOi7BGXR9U9rCw49.1">this link</a>.
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
            <td>Modern cryptography. Overview of the course. Syntax of secret-key encryption (SKE), public-key encryption (PKE), message authentication codes (MACs) and digital signatures. Definition of perfect secrecy.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture01_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 2 27/09/24</td>
            <td>Equivalent notions of perfect secrecy. The one-time pad and Shannon's impossibility result. Definition of statistically-secure (one-time) MACs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture02_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 3 01/10/24</td>
            <td>Constructions of pairwise independent hash functions and one-time statistically secure MACs. Randomness extraction. Impossibility of randomness extraction from a single min-entropy source. Definition of seeded extractors.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture03_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 4 04/10/24</td>
            <td>Leftover hash lemma. Beginning of computational security.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture04_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 5 08/10/24</td>
            <td>Computational security. Definition and examples of one-way functions. Definition of pseudorandom generators (PRGs).</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture05_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 6 11/10/24</td>
            <td>Definition of one-time computationally secure SKE. Construction from any PRG.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture06_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 7 15/10/24</td>
            <td>Constructing PRGs. Proof that one bit of stretch implies unbounded polynomial stretch. PRGs from one-way functions and hard-core bits. Applications to real-world PRGs. Definition of chosen-plaintext attacks (CPA) security for SKE.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture07_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 8 18/10/24</td>
            <td>Definition of pseudorandom functions (PRFs). Application to constructing CPA-secure SKE for fixed input length (FIL) messages. Definition of universal unforgeability under chosen-message attacks (UFCMA) for MACs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture08_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 9 22/10/24</td>
            <td>Proof that PRFs imply CPA-secure SKE for FIL messages. Proof that PRFs imply UFCMA MACs for FIL messages. Modes of operation for SKE.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture09_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 10 25/10/24</td>
            <td>Proof of CPA security for the CTR mode. Domain extension for MACs.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture10_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 11 30/10/24</td>
            <td>Domain extension for MACs. Universal hashing and CBC-MAC. XOR-MAC.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture11_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 12 05/11/24</td>
            <td>Definition of CCA security for SKE. Combining encryption and authentication.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture12_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 13 08/11/24</td>
            <td>Exercises.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture13_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 14 12/11/24</td>
            <td>Authenticated encryption. Blockciphers and Feistel networks.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture14_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 15 15/11/24</td>
            <td>Brush-up on number theory.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture15_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 16 19/11/24</td>
            <td>Brush-up on number theory (continued). The Diffie-Hellmann key exchange.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture16_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 17 22/11/24</td>
            <td>Symmetric cryptography using number theory. Public-key encryption. The ElGamal PKE.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture17_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 18 26/11/24</td>
            <td>The RSA PKE and the PKCS standard. Collision-resistant hash functions.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture18_2425.pdf" target="_blank">PDF</a>]</td>
        </tr>
        <tr>
            <td>Lecture 19 29/11/24</td>
            <td>Merkle trees and the Merklee-Damgaard paradigm. Building compression functions.</td>
            <td>[<a href="https://dventuri83.github.io/assets/pdf/crypto_lecture19_2425.pdf" target="_blank">PDF</a>]</td>
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
