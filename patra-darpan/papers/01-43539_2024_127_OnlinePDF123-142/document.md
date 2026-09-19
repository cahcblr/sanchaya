# Turagagati method for 4 × 4 pandiagonal magic squares by Nārāyana Pandita

- Author Display: M V Reddy et al.
- Year: 2024
- Journal Label: IJHS-59-2024-Issue-2
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/01-43539_2024_127_OnlinePDF123-142.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science (2024) 59:123–142
https://doi.org/10.1007/s43539-024-00127-2
ARTICLE

# Turagagati method for $4 \times 4$ pandiagonal magic squares by Nārāyaṇa Paṇḍita

Mandadi Varuneshwar Reddy¹ · Sooryanarayan D. G.¹ · Ramasubramanian K.¹
Received: 25 April 2024 / Accepted: 16 May 2024 / Published online: 24 July 2024
© Indian National Science Academy 2024
**Abstract**
The pandiagonal magic squares have been known in India from the time of Nāgārjuna (c.100 CE) and Varāhamihira (c.550 CE). In his comprehensive mathematical study of magic squares presented in the *Bhadragaṇita* chapter of *Gaṇitakaumudī* (c. 1356 CE), Nārāyaṇa Paṇḍita has briefly outlined a method for constructing $4 \times 4$ pandiagonal magic squares based on *turagagati* or horse movements in a chess board. In this paper, we present a study of the verses of Nārāyaṇa Paṇḍita which leads to a method of construction of $4 \times 4$ pandiagonal squares by horse moves only. We also show that this algorithm generates all (and only) the 384 pandiagonal squares of order 4. Besides presenting this algorithm, this paper discusses various properties exhibited by these squares along with their proofs.
**Keywords** Magic squares · Pandiagonal · Horse moves · Bhadragaṇita · Gaṇitakaumudī · Turagagati · Nārāyaṇa Paṇḍita

## 1 Introduction

Toying with magic squares is an enjoyable experience and is known to have fascinated even the greatest of mathematicians. The first chapter of Srinivasa Ramanujan’s notebooks is on magic squares. It is said to have been written “much earlier than the remainder of the notebooks”.[^1]
A magic square of order $n$ is an arrangement of $n^2$ different numbers in a $n \times n$ square array. They can be of three types: (i) semi-magic squares, (ii) normal magic squares and (iii) pandiagonal magic squares. In a semi-magic square, the sum of numbers in all the rows and columns are the same. In a normal magic square, besides the sum of the numbers along every row and column, the leading diagonals (primary and secondary) also sum up to the same number. In addition, if the broken diagonals (*alpaśruti*) across the torus of the magic square also add up to the magic sum, then the square is called a pandiagonal magic square. Broken diagonal are those that wrap around the square from the opposite side, when the diagonal line is extended beyond the edge of the square.
If $M$ is a pandiagonal magic square with the magic sum ($S$) and elements $m_{ij} (i, j = 1, 2, \dots n)$, then the various relevant sums may be represented as:
(a) Sum along the rows

$$S = \sum_{j=1}^{n} m_{ij} \forall i = \{1, 2, \dots, n\} \tag{1a}$$

(b) Sum along the columns

$$S = \sum_{i=1}^{n} m_{ij} \forall j = \{1, 2, \dots, n\} \tag{1b}$$

(c) Sum along the leading diagonals (*śruti*)

$$S = \sum_{i,j=1}^{n} m_{ij} [[i = j]] = \sum_{i,j=1}^{n} m_{ij} [[j = n - i + 1]] \tag{1c}$$

(d) Sum along the broken diagonals (*alpaśruti*)

<!-- figure-resolved-page-render-hidden: image=media/p02_page.png caption="Fig. 1. Depiction of semi, normal and pandiagonal magic squares" -->

<!-- figure-meta: page=2, position=top, type=diagram -->

If only the conditions (1a) and (1b) are satisfied, it is a semi-magic square. With (1c) also satisfied, it becomes a normal magic square. If (1d) is also satisfied then it becomes a pandiagonal magic square. An illustration of a semi-magic square, a normal magic square and a pandiagonal magic square can be found in Fig. 1.

$$S = \sum_{i,j=1}^{n} m_{ij} [[i + j = d_1 \pmod n]] \forall d_1 = \{2, 3, \dots, n\} \tag{1d}$$

$$S = \sum_{i,j=1}^{n} m_{ij} [[i - j = d_2 \pmod n]] \forall d_2 = \{1, 2, \dots, n - 1\}$$

### 1.1 Historic outline of magic squares in India

A survey of mathematical development over many eras across various civilizations reveals that in India, magic squares have been known for more than two millennia. However, a thorough mathematical analysis of the topic and systematic rules for their construction are to be found in the last millennia alone based on the extant texts.
One of the earliest occurrence of magic squares is found in the works of Nāgārjuna[^2] who flourished around the 1st century CE. One of the squares in this work is called *Nāgārjunīya* after him. The squares given by Nāgārjuna are all $4 \times 4$ squares, and some of these seem to have been known before him. The even sum squares constructed based on this template are pandiagonal. So is the $4 \times 4$ square with magic sum 100 known as “Nāgārjunīya” (Kolachana et al. 2019, p.382) (Fig. 2).

<!-- figure-resolved-page-render-hidden: image=media/p02_page.png caption="Fig. 2. Nāgārjuniya Magic Square (magic sum = 100)" -->

<!-- figure-meta: page=2, position=middle, type=diagram -->

Another interesting pandiagonal magic square found in a work of Varāhamihira is also of the order 4, and gives the magic sum 18. Varāhamihira’s *Bṛhatsaṃhitā* (c. 6th century CE) is a historically important encyclopedic work. In Chapter 76, verses 23–26, he gives the method of preparing perfumes employing the *sarvatobhadra*[^3] (Fig. 3). The commentator Bhaṭṭotpala (c.950 CE) has detailed that the method clearly involved the use of the following 16 celled square which Varāhamihira calls *ṣoḍaśa-kacchapuṭa*[^4]. This magic square has been employed in apportioning sixteen ingredients in the context of perfume preparation. By choosing four elements along the row, column, leading or broken

![Fig. 3. Pandiagonal sarvatobhadra of Varāhamihira](media/p02_page.png)

*Fig. 3. Pandiagonal sarvatobhadra of Varāhamihira*

<!-- figure-resolved-page-render: page=2 image=media/p02_page.png -->

<!-- figure-meta: page=2, position=middle, type=diagram -->

diagonal would add up to 18 parts, thereby leading to a new perfume concoction.
In the ancient town of Khajuraho, there are Jaina inscriptions and amidst them a magic square of $4 \times 4$ cells with the sum as 34 has been found and dated to be from the 11th century (Shukla et al., 1992). Recently, one of the authors of the paper had an occasion to visit this temple. The photograph of the magic square, which is engraved on the right hand side of the column to the entry of the shrine at is shown in Fig. 4. K.S. Shukla also notes that in the *Tijapapahutta Stotra* of the Jainas, we find another $4 \times 4$ magic square having a total of 170.

![Fig. 4. Magic square at the Pārśvanātha temple, Khajuraho. (a) Transcription of the Magic square. (b) Engraved on the right hand side of the column at the entry.](media/p03_fig01.jpg)

*Fig. 4. Magic square at the Pārśvanātha temple, Khajuraho. (a) Transcription of the Magic square. (b) Engraved on the right hand side of the column at the entry.*

<!-- figure-resolved-extracted: page=3 image=media/p03_fig01.jpg -->

<!-- figure-meta: page=3, position=top, type=photograph -->

The earliest extant mathematical text in India that presents a fairly detailed treatment on the topic of magic squares is found in the Prākṛta work, *Gaṇitasārakaumudī*, of the Jaina mathematician Thakkura Pherū (c. 1300 CE). Nonetheless, it does not deal with pandiagonal squares. A comprehensive discussion of the mathematics of magic squares is to be found only in the *Gaṇitakaumudī* of Nārāyaṇa Paṇḍita. This work comprises a significant leap in elucidating the underlying principles and techniques of constructing various magic squares. The algorithm presented in this paper is a testimonial to the systematic presentation of Nārāyaṇa Paṇḍita. We shall give an outline of its contents in Sect. 2 of the paper.
Amongst the later works, the *Smṛtitattva* of Raghunandana (c.1500) also gives a method for the construction of $4 \times 4$ pandiagonal squares with a given even magic sum. A similar construction is also given in a *stotra* of Sundara Sūri (16th century). *Caturaciṇtāmaṇi* of Giridhara Bhaṭṭa (c. 16th century) is another mathematical work which discusses magic squares, but very briefly, in six verses (Ramasubramanian, 2019).

### 1.2 Magic squares in a global context

Chinese, Hebrew,[^5] Persian and Arabic scholars of different periods have authored texts that contain magic squares. One among the most recent works that aims to provide a historical perspective of magic squares by Sesiano (2019, pp. 6–13) almost completely overlooks the Indian tradition, with an opinion that development of this field of study in India almost entirely is centered around the Arabic traditions, with a likely origin from concealed Greek traditions: concealed because there are no extant Greek texts that deal with magic squares. This assumption seems to be somewhat far-fetched.
In any case, from Sesiano (2019) it is evident that Arabic texts of the period 10–13th centuries contain various examples of $4 \times 4$ magic squares and a few methods for their constructions as well. Though we come across examples of pandiagonal squares of order four in some of these texts, the pandiagonality property itself was not recognised in the Islamic mathematical tradition, nor any specific methods were given for their construction. The only special feature of pandiagonal squares that was noted was that they continued to be magic squares when the elements were moved around.
Sesiano notes that “The first trace of magic squares in the West is the treatise of the Byzantine Manuel Moschopoulos, written at the very beginning of the 14th century... It would seem that he attempted to reconstruct the methods from examples of squares he saw in some manuscripts, either Persian or Arabic.” Peter G Brown (1997, p. 2), in his article commenting on the work of Manuel Moschopoulos, notices that “It is very unlikely that he worked out any of the methods of finding Magic Squares himself", and adds that “In his writing he gives a number of techniques for constructing magic square of various types." However, it may be mentioned that he does not explain how the $4 \times 4$ magic square was constructed, nor does he discuss the pandiagonal property of the square.
Sesiano in his book also states that, “The magic square of order 3 appears in China at the beginning of our era; to our knowledge, higher-order squares do not occur there before the 13th century, and are clearly of Arabic or Persian origin. The same holds for Indian magic squares.”
It seems to us that some of the claims and assertions made by Sesiano are ill informed. Based on the account given by him, the first known Arabic work that attempts to delve into a horse move based approach to building squares of order 4n is found in the treatise *Rising of the illumination for arranging magic squares*, written around 1600 CE by the Egyptian Muḥammad Shabrāmallisı (Sesanio 2019, p. 16). Sesanio himself observes that “This does not make, though, the author highly competent: sometimes he describes at length something very simple, sometimes he wrongly attempts to generalize a particular method.”
Whereas in the Indian tradition, as indicated in the previous subsection, the *Turagagati* method was enunciated by Nārāyaṇa Paṇḍita in c. 1356 CE along with the construction of a rich variety of geometrical shapes with magic sums.

### 1.3 Motivation for this study

The motivation to take up an in depth study of the algorithm provided by Nārāyaṇa Paṇḍita to construct $4 \times 4$ pandiagonal magic squares includes:
(a) Experiencing the joy of comprehending an algorithm that has not been fully understood and ‘clearly’ enunciated in modern parlance till date.
(b) Facilitating the integration of this topic into school curriculum in India and elsewhere as a part of recreational mathematics that would stimulate young minds.
(c) Helping historians provide the rightful place for contributions made by Indians in the study of magic squares as part of the history of mathematics.
In this study, Sect. 2 presents further details about Nārāyaṇa Paṇḍita and his work *Gaṇitakaumudī*. Following that, in Sect. 3, earlier studies on *Gaṇitakaumudī* and pandiagonal magic square have been discussed. Later, in Sect. 4, the algorithm for constructing $4 \times 4$ pandiagonal magic squares by employing only HMs is discussed and analysed. In Sect. 5, we list out various properties exhibited by $4 \times 4$ pandiagonal squares along with their proofs.

## 2 About *Gaṇitakaumudī* and its author

A detailed mathematical treatment, by way of exclusively devoting a chapter (Chapter 14, consisting of 77 verses), is provided by Nārāyaṇa Paṇḍita in his *Gaṇitakaumudī* (c. 1356). In this chapter Nārāyaṇa Paṇḍita systematically introduces the principles governing the construction of magic squares and also details general methods for the construction of different forms of magic squares by broadly classifying them into three types as mentioned in the introduction. The presentation of Nārāyaṇa Paṇḍita is noted to be clearly connected to the topic of progressions. While discussing the mathematical foundations pertaining to the computation of magic squares, Nārāyaṇa Paṇḍita notes that any series in arithmetic progression can be used to construct magic squares with the methods enunciated by him.
> सर्वेषां भद्राणां श्रेढीरीत्या भवेद्गणितम् ।
> $sarveṣāṃ\ bhadrāṇāṃ\ śreḍhīrītyā\ bhavedgaṇitam\ ।$
The construction of all magic squares is through arithmetic progression (*śreḍhī*).
From the summarised list of contents presented by K.S. Shukla (Shukla et al, 1992), we come to understand that this chapter encompasses:
1. Explicit rules for the construction of a $4 \times 4$ square by the *Turagagati* or horse moves (HMs).
2. The method of superposition for the construction of higher order squares of the type 4n × 4n.
3. The method of equi-spacing for the construction of (4n + 2) × (4n + 2) squares.
4. The method of superposition for odd squares.
5. A very simple and straight forward (*alpaśruti*) method whose origins are unknown for odd squares of all orders.
6. The construction of a magic rectangle (*vitāna* or canopy).
7. The construction of magic circles, triangles, hexagons and various other figures, such as the altar, the diamond, etc.
The total number of verses in this text *Gaṇitakaumudī* is close to 925 which is more than three times the number of verses in the famous work *Līlāvatī* of Bhāskarācārya. The contents and the range of topics covered are also much richer than *Līlāvatī*. However, unfortunately the number of available manuscripts of this work is very small and the entire text came into light only in recent times. Thus this text presents an excellent opportunity to study and bring forth the salient mathematical aspects and the developments of the time.

### 2.1 Availability of manuscripts

Among the European scholars, Henry Thomas Colebrooke, the 18th century English mathematician and translator of Bhāskara’s *Līlāvatī*, has identified the presence of this text. The manuscript has been described as partial with only the last two chapters present in it. The last two chapters - the thirteenth and the fourteenth chapters deal with the topics of *Aṅkapāśa* (combinatorics) and *Bhadragaṇita* (Magic Squares) respectively. It has been stated that the Library of the India Office at both London and Cambridge hold a copy of the partial manuscript.
The content of this text in its entirety has come to light only in the early 20th century with the efforts of Pandit Padmakara Dvivedi, the son of the famous scholar Pandit Sudhakara Dvivedi. It has been stated by Dvivedi that he had accidentally discovered a complete manuscript of *Gaṇitakaumudī* in his father’s collection and looking into its contents, he decided to bring out an edited version of the work. This was subsequently brought out as a two part publication in the years 1936 and 1942. Dvivedi also mentions in the preface that he has compared the complete manuscript in his possession with the copies in the India Office Library and has presented the differences in the readings with suggestions which he felt were more appropriate. Unfortunately the edition that has been brought out by Padmakara Dvivedi—which is the only edition that is available to us—is not that great as it still has several typographical errors.
Considering the depth and width of the topics covered here, Dvivedi conjectures that this work must have intended to be an alternative to the widely renowned *Līlāvatī* of Bhāskarācārya. This incidentally testifies the alluring title given to the text *Gaṇitakaumudī* which literally means “Mathematics in the form of moonlight" as well as the gamut of foundational topics in mathematics that is covered here.

### 2.2 The lineage of Nārāyaṇa Paṇḍita

The earliest known allusion to Nārāyaṇa Paṇḍita is in *Buddhivilāsinī*, which is a well-known commentary to the famous text *Līlāvatī*. *Buddhivilāsinī* was composed by Gaṇeśa Daivajña in 1546 CE. In this text, Gaṇeśa Daivajña attributes mathematicians Śrīdhara and Nārāyaṇa Paṇḍita to be the propounders of the mathematics that deal with barter, trade and mixed proportions which is titled *Trairāśika* in arithmetics. The following is the aforementioned quote from *Buddhivilāsinī*.
> श्रीधरनारायणादिभिरपि भाण्डजात्यादिकमन्यदप्युक्तम् ।
> *śrīdhara-nārāyaṇādibhirapi bhāṇḍajātyādikam anyat apyuktam ।*
Other [topics] such as barter, fractional procedures, and so on are stated [to be *pāṭīgaṇita*] by Śrīdhara, Nārāyaṇa, and others.
Unfortunately, not much is known about the Nārāyaṇa Paṇḍita’s date of birth, whereabouts and other biographical details. Only very little information has been provided by him in the verses towards the end of the text. One verse in *sragdharā* meter that has been dedicated to capture the glory of his father is as follows:
> आसीत् सौजन्यदुग्धान्बुधिरवनिसुरश्रेणिमुख्यो जगत्यां
> प्रख्यः श्रीकण्ठपादद्वयनिहितमनाः शारदाया निवासः ।
> श्रौतस्मार्तार्थवेत्ता सकलगुणनिधिः शिल्पविद्याप्रगल्भः
> शास्त्रे शस्त्रे च तर्के प्रचुरतरगतिः श्रीनृसिंहो नृसिंहः ॥
> *āsīt saujanyadugdhāmbudhiravanisuraśreṇimukhyo jagatyāṃ*
> *prakhyaḥ śrīkaṃṭhapādadvayanihitamanāḥ śāradāyā nivāsaḥ ।*
> *srautasmārtārthavettā sakalaguṇanidhiḥ śilpavidyāप्रगल्भः*
> *śāstre śastre ca tarke pracurataragati: śrīnṛsiṃho nṛsiṃhaḥ ॥*
He was the milky ocean of nobility (*saujanya*), the foremost in the assembly of *brāhmaṇas* (*avanisura*) whose fame has spread over the world; [He was] one whose mind was steadfast (*nihita*) at the feet of Lord Śiva; one who was the dwelling place of Devī Sarasvatī; one who had mastered the [performances of] *śrauta* and *smārta* [*karmas*]; one who was a reservoir of all virtues; one who was outstanding in the field of architecture/geometry; one who had great felicity (*pracurataragati*) in *śāstrās*, rituals and logic; [my father] by name Śrī Nṛsiṃha was indeed a nṛsiṃha[^6] (lion among men).
From the above verse we understand that Nārāyaṇa Paṇḍita’s father was named Nṛsiṃha and that he was an outstanding scholar in several branches of knowledge. Besides this, no other personal details of Nārāyaṇa Paṇḍita are known. However, the contents of *Gaṇitakaumudī* undoubtedly stand testimony to the genius of this 14th century mathematician of India. *Bījagaṇitāvataṃśa* is known to be another work of Nārāyaṇa Paṇḍita with only one incomplete manuscript available in Benares.

[^1]: Ramanujan et al. 1985, Chapter 1 (pp. 16–24) of Ramanujan’s Notebooks, Part I.

[^2]: There are divergent views on whether the author Nāgārjuna of *Kakṣapuṭa* is the Buddhist philosopher of 2nd century CE or a Chemist (expert of *Rasaśāstra*) who lived around 8–10th centuries. See (Kolachana et al., 2019) and (Ramasubramanian, 2019).

[^3]: This word *sarvatobhadra* is a compound word, where *sarvataḥ* means from all sides. *Bhadra* in this context referes to a magic square, thus *sarvatobhadra* refers to a pandiagonal magic square.

[^4]: The word *kaccha* in Sanskrit means a tortoise and *puṭa*, though has several meanings, in this context refers to the carapace. Thus the compound *kacchapuṭa* is used to refer to a magic square having various cells that are akin to the cells that appear on the carapace of a tortoise.

[^5]: Cited by K.S. Shukla et al. (1992) referring to a work of Rabbi ben Ezra (c. 1140); cf. D. E. Smith, History of Mathematics, II, New York, 1923, p. 596.

[^6]: In this instance, the use of the word nṛsiṃha must be taken as a tatpuruṣa compound: नृषुसिंहः = नरसिंहः ।

128 Indian Journal of History of Science (2024) 59:123–142

## 2.3 Date of composition of *Gaṇitakaumudī*

The date of composition of *Gaṇitakaumudī* has been given by Nārāyaṇa Paṇḍita himself in the following verse that appears at the end of the text.
> गजनगरविमितशाके दुर्मुखवर्षे च बाहुले मासि ।
> धातृतिथौ कृष्णदले गुरौ समाप्तिं गतं गणितम् ॥
> 
> *gajanagaravimitaśāke*
> *durmukhavarṣe ca bāhule māsi |*
> *dhātṛtithau kṛṣṇadale*
> *gurau samāptiṃ gataṃ gaṇitam ||*
The *Gaṇita* (*Gaṇitakaumudī*) came to completion on Thursday, in the second *tithi* of the *Kṛṣṇa Pakṣa* (waning cycle of Moon), of the month *Kārtika* in *Durmukha Saṃvatsara*, in 1278 (*gaja* - 8; *naga* - 7; *ravi* - 12) *Śaka*.
Thus we unambiguously know that the work *Gaṇitakaumudī* was completed in the year 1356 CE (1278 *Śaka* year). It is interesting to note that Nārāyaṇa Paṇḍita has specified the *tithi* count in terms of the *devatā* of the *tithi*. Based on the list available from other works, we know that *dhātṛtithi* corresponds to *dvitīyā*.

## 2.4 Contents, structure and significance of *Gaṇitakaumudī*

The text *Gaṇitakaumudī* contains fourteen chapters called *vyavahāras*. Of the 900+ verses about 60% of them are *sūtra* verses (giving rules) and 40% of them are *udāharaṇa* verses (that present examples to be worked out). Most of the *sūtra* verses are composed in the *Āryā* meter.
Towards the end of the work, Nārāyaṇa Paṇḍita fondly expresses his wish that this text shall gain widespread acceptance and popularity. This wish has been brilliantly put forth with poetic flourishes in the following verse composed in *śārdūlavikrīḍita* meter:
> यावत् सप्तकुलाचलाः क्षितितले यावच्च सप्तार्णवाः
> यावत् सूर्यमुखा ग्रहाश्च गगने यावद्ध्रुवास्तारकाः ।
> स्थेयात्तावदियं सदोदितवती श्रीकौमुदी कौमुदी-
> पूरस्वच्छयशःप्रवाहसुभगा नारायणेन्दोः सृता ॥
> 
> *yāvat saptakulācalāḥ kṣititale yāvacca saptārṇavāḥ*
> *yāvat sūryamukhā grahāśca gagane yāvaddhruvāstārakāḥ |*
> *stheyāttāvadiyaṃ sadoditavatī śrīkaumudī kaumudī-*
> *pūrasvacchayaśa:pravāhasubhagā nārāyaṇendoḥ srutā ||*
For as long as there are the seven mountains and the seven oceans on the earth, as long as the planets commencing from sun remain in the space and so too the stars remain studded, so long may the text *Śrīkaumudī*, which has emanated from the face of Nārāyaṇa in the form of moon [be cherished by scholars], like the abundantly pure moonlight emerging from the moon is cherished.
The nature of the foundational mathematics taught in this text, and the systematic way in which it is presented, including the special chapter on magic squares, indeed makes this text occupy a special status among the repository of Indian mathematical heritage. Nārāyaṇa Paṇḍita has also written his own short commentary called *Vāsanā*, which succinctly presents the explanation to the *sūtras* or rules and solutions to the examples. Table 1 presents a brief summary of the contents of *Gaṇitakaumudī*.

# 3 Earlier studies on *Gaṇitakaumudī* and pandiagonal magic squares

The primary aim of this work is to clearly analyse and present the algorithm for constructing pandiagonal magic squares of order 4 as proposed by Nārāyaṇa Paṇḍita in the fourteenth chapter of *Gaṇitakaumudī*. The article of Datta and Singh revised by Shukla et al. (1992), as well as the writings of R.C. Gupta (2005) have presented this method briefly. Nonetheless these works do not crisply bring out the algorithm prescribed by Nārāyaṇa Paṇḍita.
It was mentioned earlier that, the very first edition of the full text of *Gaṇitakaumudī* was by Pandit Padmakara Dvivedi only in 1942. Kusuba (1993) has also brought out
Table 1 Contents of *Gaṇitakaumudī*

| Number | Chapter Title | Mathematical topics covered |
| :--- | :--- | :--- |
| 1 | *Prakīrṇaka-vyavahāra* | Logistics, weights and measures |
| 2 | *Miśraka-vyavahāra* | Partnership, sales, interest, etc |
| 3 | *Śreḍhī-vyavahāra* | Sequences and series |
| 4 | *Kṣetra-vyavahāra* | Geometry of planar figures |
| 5 | *Khāta-vyavahāra* | Excavations |
| 6 | *Citi-vyavahāra* | Stacks |
| 7 | *Rāśi-vyavahāra* | Mounds of grain |
| 8 | *Chāyā-vyavahāra* | Shadow problems |
| 9 | *Kuṭṭaka* | Linear indeterminate equations |
| 10 | *Vargaprakṛti* | Quadratic indeterminate equations |
| 11 | *Bhāgādāna* | Factorisation |
| 12 | *Rūpādyamśāvatāra* | Partitioning unity into unit-fractions |
| 13 | *Aṅkapāśa* | Combinatorics |
| 14 | *Bhadragaṇita* | Magic squares |

---
129 Indian Journal of History of Science (2024) 59:123–142
the edited and transliterated version of the last two chapters of this text as part of his doctoral thesis and has made preliminary studies into the contents of these chapters. Kusuba has also correctly constructed the 24 possible configurations of magic squares that Nārāyaṇa Paṇḍita himself has alluded in his *vāsanā*, which seems to have errors in the manuscript of Dvivedi.
Paramanand Singh (1978, 1998-2002) has brought out the translation of the *Gaṇitakaumudī* along with mathematical notes as a series of publications over a period of four years since 1998. This includes the fourteenth chapter covering magic squares. However, the study by Singh is not really satisfactory as it fails to get into the heart of the matter on various occasions. To our knowledge to date, the exact algorithm of constructing magic squares with *Turagagati* has not been satisfactorily described and analysed in detail.
Vijayaraghavan (1941) in his paper on Jaina Magic Squares deals with similar $4 \times 4$ pandiagonal magic squares, along with a brief mathematical analysis, bringing out various properties. Bhowmik (2018) has worked on the proofs demonstrating certain properties of magic squares and also tries to show how the HMs shall lead to numbers of the progression being placed to get the magic sum. In this study, these properties are also discussed in Sect. 5 after presenting the algorithm clearly, along with proofs.
Lehmer (1933) had surveyed $4 \times 4$ squares and concluded that there are 539,136 squares possible with only rows and columns having the magic sum, and 7,040 normal magic squares and only 48 diabolic/pandiagonal magic squares. Later, Rosser and Walker (1938) have corrected this result and have mathematically arrived at the conclusion that there are 384 diabolic squares, which Nārāyaṇa Paṇḍita has clearly stated in his work. This study will also show that there are only 384 different configurations of a pandiagonal magic square of order 4 that is constructed from any sixteen numbers in an arithmetic sequence.

## 3.1 *Bhadragaṇita* in *Gaṇitakaumudī*

In the *Gaṇitakaumudī* Nārāyaṇa Paṇḍita employs the term *Bhadragaṇita* to refer to magic squares. The word ‘*bhadra*’ has several connotations in Sanskrit which include:
> साधु, मङ्गलं, श्रेष्ठं
> *sādhu, maṅgalaṃ, śreṣṭhaṃ*
> good, auspicious, foremost
Keeping these meanings in mind, we may desire the compound as:
1. भद्रं च तत् गणितञ्च (कर्मधारय compound)
2. भद्रदायकं गणितम् (मध्यमपदलोपी compound)
3. भद्राय गणितम् (चतुर्थीतत्पुरुष compound)
The three different meanings given above are consistent with the three purpose that have been outlined by Nārāyaṇa Paṇḍita in the opening verse of this chapter:
> सद्गणितचमत्कृतये यन्त्रविदां प्रीतये कुगणकानाम् ।
> गर्वक्षिप्त्यै वक्ष्ये तत्सारं भद्रगणिताख्यम् ॥
> 
> *sadgaṇitacamatkṛtaye*
> *yantravidāṃ prītaye kugaṇakānām |*
> *garvakṣiptyai vakṣye*
> *tatsāraṃ bhadragaṇitākhyam ||*
For the delight of the good mathematician, for pleasing those who know the techniques of *yantras*, and for stultifying the arrogance of inferior mathematicians I shall state the essence of what is called *Bhadragaṇita*.
The chapter on *Bhadragaṇita* has 60 verses dedicated to presenting the rules and 17 verses for illustrating those rules through examples.

## 3.2 Origin of *Bhadragaṇita*

At the beginning of this chapter, before stating the purpose of studying the magic squares, Nārāyaṇa Paṇḍita provides a very brief narrative of the origin of this field of study. In the Indian tradition, it is held that the subject of progression, of which magic squares form a part, was taught by Lord Śiva to Maṇibhadra. Nārāyaṇa Paṇḍita begins Chapter 14 of his *Gaṇitakaumudī* (c. 1356 CE) by stating the following verse:
> अथ भुवनत्रयगुरूपदिष्टं ईशेन माणिभद्राय ।
> कौतुकिने भूताय श्रेढीसम्बन्धि सद्गणितम् ॥
> 
> *atha bhuvanatrayaguruṇopadiṣṭam*
> *īśena māṇibhadrāya |*
> *kautukine bhūtāya*
> *śreḍhīsambandhi sadgaṇitam ||*
Now, the beautiful mathematics called *Bhadragaṇita*, which was taught by *Īśa* (Lord Śiva), the guru of all three worlds, to the enthusiastic *bhūta* Maṇibhadra [is going to be stated].
Here, Nārāyaṇa Paṇḍita presents the tradition that Lord Śiva was the preceptor who had first taught this field of study to his enthusiastic pupil and *bhūtagaṇa* Maṇibhadra. Dvivedi states that this field of study is named *Bhadragaṇita* since this knowledge was first endowed upon Maṇibhadra. The nomenclature could also stem from the fact that it was considered to fetch *bhadra* (all round prosperity/well-being) by creating *yantras* with various numbers inscribed in them in a manner akin to other kinds of *yantras* containing various *bījākśaras*. R.C. Gupta notes that “magic squares (*aṅka-yantras*) are particular type of the more general figures or
---
130 Indian Journal of History of Science (2024) 59:123–142
diagrams called *yantras* (mystic diagrams). According to Mahīdhara, the *yantras* were enunciated by Lord Śiva” (Gupta, 2005, p. 25)).

## 3.3 Systematic approach

One of the notable features of Nārāyaṇa Paṇḍita is that he methodically introduces all topics that he discusses. For instance, after setting out the historical background and context, he commences this chapter by broadly classifying magic squares into three types.
> समगर्भविषमगर्भे विषमञ्चेति त्रिधा भवेद भद्रम् ।
> 
> *samagarbhaviṣamagarbhe viṣamañceti*
> *tridhā bhaved bhadram |*
*Samagarbha*, *viṣamagarbha* and *viṣama* are the three forms of magic square.
Understanding this classification is essential since the rules for construction of magic squares of these three types are quite different. The method that is suitable for one would not hold for the other. He also provides a brief explanation on what qualifies as these different types in the following verse:
> भद्राङ्के चतुराप्ते निरग्रके तद्भवेच्च समगर्भम् ।
> द्व्यग्रे तु विषमगर्भं त्र्येकाग्रे केवलं विषमम् ॥
> 
> *bhadrāṅke caturāpte*
> *niragrake tadbhavecca samagarbham |*
> *dvyagre tu viṣamagarbhaṃ*
> *tryekāgre kevalaṃ viṣamam ||*
When the order of the magic square is divided by four, if the remainder is zero, then it is *samagarbha*; if remainder is two, then it is *viṣamagarbha*; and if remainder is three or one, then it is *viṣama*.
In this study we focus on a particular method propounded by Nārāyaṇa Paṇḍita to build a *samagarbha* of order 4 that is a pandiagonal magic square by placing the numbers through HMs. The following section presents the set of verses that is being studied here.

# 4 Construction of $4 \times 4$ pandiagonal magic squares by Horse Moves

## 4.1 Verses describing construction by *turagagati*

Nārāyaṇa Paṇḍita presents the algorithm for constructing $4 \times 4$ pandiagonal magic squares in just two verses (10–11). Verse 12 describes what is pandiagonality.
> चतुरङ्गतुरगगत्या द्वौ द्वौ श्रेढीसमुद्भवावङ्कौ ।
> न्यस्य क्रमोत्क्रमेण च कोष्ठैक्यैकान्तरेण च तौ ॥ १० ॥
> सव्यासव्यतुरङ्गगत्या कोष्ठान् प्रपूरयेदङ्कैः ।
> समगर्भे षोडशगृहभद्रे प्रोक्तो विधिश्चायम् ॥ ११ ॥
> तिर्यक्कोष्ठगतानां ऊर्ध्वस्थानां च कर्णगानां च ।
> अङ्कानां संयोगः पृथङ्‌मितो जायते तुल्यः ॥ १२ ॥
> 
> *caturaṅgaturagagatyādvau*
> *dvau śreḍhīsamudbhavāvaṅkau |*
> *nyasya kramotkrameṇa ca*
> *koṣṭhaikyaikāntareṇa ca tau || 10 ||*
> *savyāsavyaturaṅgagatī*
> *koṣṭhān prapūrayedaṅkaiḥ |*
> *samagarbhe ṣoḍaśagṛhabhadre*
> *prokto vidhiścāyam || 11 ||*
> *tiryakkoṣṭhagatānāṃ*
> *ūrdhvasthānāñca karṇagānāñca |*
> *aṅkānāṃ saṃyogaḥ*
> *pṛthaṅmito jāyate tulyaḥ || 12 ||*
Having placed (*nyasya*) the pairs of numbers generated in an arithmetic sequence (*śreḍhi*) in sequence (*krama*) and out of sequence (*utkrama*), by HMs, and placing those pairs [such that the relative positions of the numbers placed by HMs from any given cell] in adjacent cells (*koṣṭhaikya*) [along diagonals], or at an interval of one cell (*ekāntareṇa*) [either along a row, or column], and by making use of the motion of horse to the left and right in a magic square with 16 cells, and of the type 4n (*samagarbha*), may you fill [all] the cells with the numbers [of the chosen arithmetic sequence]. This is the method (*vidhi*) that has been stated [by earlier mathematicians/himself?]. The sum of the numbers along the rows (*tiryakkoṣṭha*) and of those along the column (*ūrdhvastha*)[^7] and of those along the diagonals (*karṇaga*) [including broken diagonals] when counted separately will be equal.
After presenting the algorithm in the verses above, Nārāyaṇa Paṇḍita also seems to have tabulated 24 different configurations of the pandiagonal magic squares for a fixed position of 1 in the top-left corner. This is our surmise based on what is printed in the [only] edited version of the text that is available to us.
These magic squares are half-filled with the first eight numbers of the series. The table is accompanied with the following brief explanation in prose.

[^7]: The word *ūrdhvastha* means ‘that which is above’. In this context it refers to the numbers aligned in the columns of a magic square, and in fact, it is qualifier to the noun *aṅka*. Incidentally, this phrase employed by Nārāyaṇa Paṇḍita indicate that the procedure of counting began from the bottom row, and moved upwards. This perhaps was the common practice that had been adopted to find the sum of a sequence of numbers in those times.

---
131 Indian Journal of History of Science (2024) 59:123–142
> प्रथमयमालङ्कयुगलम् १।२।३।४ द्वितीयम् ५।६।७।८ तृतीयम् ९।१०।११।१२ चतुर्थम् १३।१४।१५।१६ ।
> प्रथमकोणलग्नैः प्रथमयमलयुगाङ्कैः जाताश्चतुर्विंशतिभेदाः । तेषां दर्शनम् । एवमन्यैः यमलयुगाङ्कैः पृथक् पृथक् चतुर्विंशतिभेदा भवन्ति ।
> 
> *prathamayamalāṅkayugalam 1,2,3,4 dvitīyam*
> *5,6,7,8 tṛtīyam 9,10,11,12 caturtham 13,14,15,16 |*
> *prathamakoṇalagnaiḥ prathamayamalayugāṅkaiḥ*
> *jātāścaturviṃśatibhedāḥ | teṣāṃ darśanam | evaman-*
> *yai: yamalayugāṅkaiḥ pṛthak pṛthak caturviṃśatibhedā*
> *bhavanti |*
The first pair of pairs (*yamalāṅkayugalam*) is 1,2,3,4, second pair of pairs is 5,6,7,8, the third is 9,10,11,12 and the fourth is 13,14,15,16. Placing the first number of the first pair of pairs in the top-left corner, there are 24 possible variants [of pandiagonal magic squares]. They can be seen here. Similarly, with pair of pairs [generated] with every other (*anyaiḥ*) [number], there are 24 possible variants.
In what follows, we present the algorithm to place all pairs of numbers through HMs that has been subtly and succinctly outlined by Nārāyaṇa Paṇḍita in just about one-and-half verses (10 and 11a, Chapter 14 of *Gaṇitakaumudī*). We also present an illustration following the algorithm.
Though the algorithm presented by Nārāyaṇa is valid for any arithmetic sequence having sixteen elements, we choose the simplest sequence of numbers 1, 2, 3, ...15, 16, as it has been opted by Nārāyaṇa Paṇḍita himself for the purpose of demonstration.

## 4.2 Algorithm for construction of $4 \times 4$ magic squares only with horse moves

The algorithm given in verses 9–12 of the fourteenth chapter by Nārāyaṇa Paṇḍita needs to be carefully interpreted, not only keeping in mind the meaning of the words and phrases employed there but also being mindful of the requirement that they should generate all (and only) the 24 templates and $384 = 16 \times 24$ variations, mentioned in example 4.
> एवं चतुर्भद्रस्य चतुर्भिः यमलैः चतुराशीत्यधिक-शतत्रयभेदा भवन्ति ।
> 
> *evaṃ caturbhadrasya caturbhiḥ yamalaiḥ caturaśī-*
> *tyadhika-śatatrayabhedā bhavanti |*
Thus with just four pairs of numbers (*caturbhiḥ yamalaiḥ*), there are 384 variants of a $4 \times 4$ [pandiagonal] magic square.
For explaining the algorithm outlined in the above verses, we introduce a few notations and explain the algorithm using modern mathematical parlance. Though we employ modern notations, it can be easily seen that these rules essentially describe the procedure outlined in his verses.
We consider the following, in order to describe the algorithm.
* Let $M$ be a pandiagonal magic square with 16 cells (*koṣṭhas*) where the cells are denoted by:

$$M_{i,j} \quad (i, j = 1, 2, 3, 4)$$

* Let $S$ be the arithmetic sequence (*śreḍhi*) with which the cells of $M$ are to be filled. The sequence $S$ we choose for demonstration is:

$$\{1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16\}$$

It is clearly stated at the begining of verse 10 “*caturaṅgaturagagatyādvau dvau śreḍhī samudbhavāvaṅkau nyasya*” that we have to take pairs (*dvau dvau*) from this arithmetic sequence and place them in the magic square by way of positioning through a HM (*turagagatyā*), as done in a chessboard (*caturaṅga*). The subsets that have to be conceived from this set of numbers in the sequence are described by Nārāyaṇa Paṇḍita himself in his commentary as *yamalāṅkayugalam*, meaning pair of pairs. They are:
$S_1 = \{1, 2, 3, 4\}$, $S_2 = \{5, 6, 7, 8\}$,
$S_3 = \{9, 10, 11, 12\}$, $S_4 = \{13, 14, 15, 16\}$
These four subsets $S_i$ ($i = 1, 2, 3, 4$) are called *prathama, dvitīya, tritīya* and *caturta yamalāṅkayugalas* respectively. The HMs that will be considered for obtaining the magic squares from the above sets (*yamalāṅkayugalas*) may be represented by the following pairs:
$H_1 = \{(1, 2), (1, 3), (3, 4)\}$,
$H_2 = \{(5, 6), (5, 7), (7, 8)\}$,
$H_3 = \{(9, 10), (9, 11), (11, 12)\}$,
$H_4 = \{(13, 14), (13, 15), (15, 16)\}$

## 4.3 The nature and description of horse moves

In a $4 \times 4$ magic square, from any given cell, there are only four types of HMs that are possible. Assume that an element $p$ is positioned in the cell $M_{2,2}$. In order to place an element $q$ in HM with respect to $p$, the only moves possible are represented by $U, D, L$ and $R$ and illustrated in Fig. 5.
Though the HM $(p, q)$ has been demonstrated by placing $p$ in $M_{2,2}$, this description is valid for any of the cells. In Fig. 6, same moves are illustrated by placing $p$ in $M_{1,1}$. Though there are eight HMs possible from any given position on a chessboard, on a $4 \times 4$ magic square there are only four moves possible, by virtue of being cyclically mapped over a torus.
---
132 Indian Journal of History of Science (2024) 59:123–142

![Fig. 5. Four types of HMs - U, D, L and R when $p$ is in $M_{2,2}$](media/p10_fig01.jpg)

*Fig. 5. Four types of HMs - U, D, L and R when $p$ is in $M_{2,2}$*

<!-- figure-resolved-extracted: page=10 image=media/p10_fig01.jpg -->

<!-- figure-meta: page=10, position=top, type=diagram -->

![Fig. 6. Four types of HMs - U, D, L and R when $p$ is in $M_{1,1}$](media/p10_fig01.jpg)

*Fig. 6. Four types of HMs - U, D, L and R when $p$ is in $M_{1,1}$*

<!-- figure-resolved-extracted: page=10 image=media/p10_fig01.jpg -->

<!-- figure-meta: page=10, position=middle, type=diagram -->

Table 2 Derivation and meaning of words *Koṣṭhaikya* and *Koṣṭhaikāntara*

| Word | Derivation | Meaning |
| :--- | :--- | :--- |
| कोष्ठैक्येन | कोष्ठयोः ऐक्यं कोष्ठैक्यं, तेन | in such a way that cells are adjacent |
| कोष्ठैकान्तरेण | कोष्ठयोः मध्ये एकं अन्तरं कोष्ठैकान्तरं, तेन | in such a way that there is a gap of one cell in between |

## 4.4 Significance of the phrases *koṣṭhaikya* and *koṣṭhaikāntara*

The term *koṣṭhā* in the context of magic squares denotes a cell. The words ‘*aikya*’ and ‘*antara*’ literally mean union and difference respectively. However in this specific context when the words are compounded with *koṣṭha* refering to the cells in a magic square, these two words refer to ‘adjacent’ [cells] and the ‘one with a gap’. The derivation of these two terms and their meanings in the present context are given in Table 2.
The significance of these terms is to capture the relative position of all the numbers, that are positioned by the four possible HMs from a given cell. As shown earlier, from a given cell there are only four possible HMs for a magic square of order four. And the numbers positioned by HMs from a given cell get placed in such a way that they will be either in *koṣṭhaikya* or *koṣṭhaikāntara* mode. This would become very clear when we illustrate with examples in the later sections.

## 4.5 Significance of the phrase *kramotkrama*

Besides describing these moves, Nārāyaṇa Paṇḍita also uses the phrase *kramotkrama* as a qualifier to the above moves. It can either be attributed to the HMs (*turagagati*) or to the choice of the numbers paired for making the HM. In the algorithm that we describe below we *kramotkrama* is a qualifier to the way the pairs are chosen. Literally, the phrase *kramotkrama* means ‘in order’ (*krama*) and ‘out of order’ (*utkrama*).

![Fig. 7. The nature of HMs within the set $S_1$](media/p10_fig01.jpg)

*Fig. 7. The nature of HMs within the set $S_1$*

<!-- figure-resolved-extracted: page=10 image=media/p10_fig01.jpg -->

<!-- figure-meta: page=10, position=bottom, type=diagram -->

($utkrama$). As presented earlier (see 4.2), the arithmetic series is structured as pair of pairs termed *yamalāṅkayugala* by Nārāyaṇa Paṇḍita. The pairs of numbers chosen within these sets are in order and out of order. For instance, considering the set $S_1$, of the three HMs in $H_1$, (1,2) is in *krama* and (1,3) is in *utkrama*. Figure 7 captures the nature of HMs within a *yamalāṅkayugalam*.

### 4.6 Rules for placing numbers in magic squares only through horse moves

The following rule-based algorithm captures Nārāyaṇa Paṇḍita’s approach to build all possible combinations of a $4 \times 4$ pandiagonal magic squares for a given arithmetic sequence.
**Rules for placing pairs in $S_1$**
**Rule 1** The first element 1 of *prathama-yamalāṅkayugalam* $S_1$, is to be placed in any of the sixteen cells.
**Rule 2** For a fixed position of 1, 2 can be placed by any one of the four valid HMs - D / U / L / R, described in the previous section.
**Rule 3** Having placed 1 and 2, 3 is also to be placed in a HM with respect to 1 through any one of the remaining three possible HMs.
**Rule 4** Having placed 1, 2 and 3, 4 is placed such that it is in a HM from both 2 and 3. There is only one such position for any given placement of 1, 2 and 3.
(At this stage you may like to go through the first three steps of the illustration provided in the next Sect. 4.7).
**Rules for placing pairs in $S_2$, $S_3$ and $S_4$**
**Rule 5** Having placed all elements in $S_1$, 5 is placed such that it is always in a HM from 1. There are only two possible ways to place 5, since 2 and 3 are already positioned through HMs from 1.
**Rule 6** All the numbers within each of the *yamalāṅkayugalams* in $S_2$, $S_3$ and $S_4$ get placed by choosing the same set of HMs chosen for the pairs in *prathama-yamalāṅkayugalam* $S_1$, with the only condition that if a cell is already filled then the HMs get reversed. The pairs of equivalent HMs are presented in Fig. 8 where the same type of HMs will be retained. In the case of reversing a HM, U will become D and vice versa, and L will become R and vice versa.
**Rule 7** Having placed elements in $S_1$ and $S_2$, 9 is placed in the only HM position that is available from 1.
**Rule 8** Having placed elements in $S_1$, $S_2$ and $S_3$, 13 is placed in the only HM position that is available from 9.
It is important to note that once five numbers are positioned say (1,2...5), the configuration of the magic square is completely fixed.

### 4.7 Illustration of constructing $4 \times 4$ magic squares by *turagagati*

The steps in the above algorithm are illustrated through the following simulation for a fixed position of 1 in the top-left corner cell.

![Fig. 11. Equivalent pairs (along the column) which retain the same type of HMs](figure-11-placeholder)

*Fig. 11. Equivalent pairs (along the column) which retain the same type of HMs*

<!-- figure-unresolved: figure=11 page_meta=133 chunk_pages=11-15 -->

<!-- figure-meta: page=133, position=top, type=diagram -->

| Equivalent pairs HMs | | | |
| :--- | :--- | :--- | :--- |
| $H_1$ | $H_2$ | $H_3$ | $H_4$ |
| **(1,2)** | (5,6) | (9,10) | (13,14) |
| **(1,3)** | (5,7) | (9,11) | (13,15) |
| **(3,4)** | (7,8) | (11,12) | (15,16) |

**Fig. 8** Equivalent pairs (along the column) which retain the same type of HMs

![The move (1,2) is chosen here as D from one of the four possibilities (U/D/L/R) as per Rule 2.](figure-11-step1-placeholder)

*The move (1,2) is chosen here as D from one of the four possibilities (U/D/L/R) as per Rule 2.*

<!-- figure-unresolved: figure=11-step1 page_meta=133 chunk_pages=11-15 -->

<!-- figure-meta: page=133, position=middle, type=diagram -->

![The move (1,3) is chosen here as R from one of the three possibilities (U/L/R) as per Rule 3.](figure-11-step2-placeholder)

*The move (1,3) is chosen here as R from one of the three possibilities (U/L/R) as per Rule 3.*

<!-- figure-unresolved: figure=11-step2 page_meta=133 chunk_pages=11-15 -->

<!-- figure-meta: page=133, position=middle, type=diagram -->

![The move (3,4) is a HM such that 4 is also in a HM from 2, as per Rule 4. Alternatively, since 2 and 3 are in *koṣṭhaikya*, (3,4) must be D, the same type as the (1,2) HM.](figure-11-step3-placeholder)

*The move (3,4) is a HM such that 4 is also in a HM from 2, as per Rule 4. Alternatively, since 2 and 3 are in *koṣṭhaikya*, (3,4) must be D, the same type as the (1,2) HM.*

<!-- figure-unresolved: figure=11-step3 page_meta=133 chunk_pages=11-15 -->

<!-- figure-meta: page=133, position=bottom, type=diagram -->

---

![The move (1,5) as per Rule 5 is chosen here as L from one of the two HM possibilities from 1 (L/U).](figure-12-step4-placeholder)

*The move (1,5) as per Rule 5 is chosen here as L from one of the two HM possibilities from 1 (L/U).*

<!-- figure-unresolved: figure=12-step4 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=top, type=diagram -->

![The move (5,6) is D as it is equivalent to (1,2) as per Rule 6.](figure-12-step5-placeholder)

*The move (5,6) is D as it is equivalent to (1,2) as per Rule 6.*

<!-- figure-unresolved: figure=12-step5 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (5,7) is equivalent to (1,3) which was R. But R move from 5 leads to a cell that is already filled (with 1). Hence the opposite move L is chosen, as per Rule 6.](figure-12-step6-placeholder)

*The move (5,7) is equivalent to (1,3) which was R. But R move from 5 leads to a cell that is already filled (with 1). Hence the opposite move L is chosen, as per Rule 6.*

<!-- figure-unresolved: figure=12-step6 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![Likewise, as per Rule 6, the move (7,8) is D as it is equivalent to the move (3,4).](figure-12-step7-placeholder)

*Likewise, as per Rule 6, the move (7,8) is D as it is equivalent to the move (3,4).*

<!-- figure-unresolved: figure=12-step7 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (1,9) is the HM U, as per Rule 7, since it is the only HM possibility from 1.](figure-12-step8-placeholder)

*The move (1,9) is the HM U, as per Rule 7, since it is the only HM possibility from 1.*

<!-- figure-unresolved: figure=12-step8 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (9,10) is equivalent to (1,2) which was D. But D move from 9 leads to a cell that is already filled (with 1). Hence as per Rule 6 the opposite move U is chosen.](figure-12-step9-placeholder)

*The move (9,10) is equivalent to (1,2) which was D. But D move from 9 leads to a cell that is already filled (with 1). Hence as per Rule 6 the opposite move U is chosen.*

<!-- figure-unresolved: figure=12-step9 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (9,11) is R as it is equivalent to the move (1,3), by Rule 6.](figure-12-step10-placeholder)

*The move (9,11) is R as it is equivalent to the move (1,3), by Rule 6.*

<!-- figure-unresolved: figure=12-step10 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=bottom, type=diagram -->

![The move (11,12) is equivalent to (3,4) which was D. But D move from 11 leads to a cell that is already filled (with 3). Hence by Rule 6 the opposite move U is chosen.](figure-12-step11-placeholder)

*The move (11,12) is equivalent to (3,4) which was D. But D move from 11 leads to a cell that is already filled (with 3). Hence by Rule 6 the opposite move U is chosen.*

<!-- figure-unresolved: figure=12-step11 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=top, type=diagram -->

![The move (9,13) is L as it is the only HM left as per Rule 8.](figure-12-step12-placeholder)

*The move (9,13) is L as it is the only HM left as per Rule 8.*

<!-- figure-unresolved: figure=12-step12 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=top, type=diagram -->

![The move (13,14) is equivalent to (1,2) which was D. But D move from 13 leads to a cell that is already filled (with 5). Hence as per Rule 6 the opposite move U is chosen.](figure-12-step13-placeholder)

*The move (13,14) is equivalent to (1,2) which was D. But D move from 13 leads to a cell that is already filled (with 5). Hence as per Rule 6 the opposite move U is chosen.*

<!-- figure-unresolved: figure=12-step13 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (13,15) is equivalent to (1,3) which was R. But R move from 13 leads to a cell that is already filled (with 9). Hence as per Rule 6 the opposite move L is chosen.](figure-12-step14-placeholder)

*The move (13,15) is equivalent to (1,3) which was R. But R move from 13 leads to a cell that is already filled (with 9). Hence as per Rule 6 the opposite move L is chosen.*

<!-- figure-unresolved: figure=12-step14 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

![The move (15,16) is equivalent to (3,4) which was D. But D move from 15 leads to a cell that is already filled (with 7). Hence as per Rule 6 the opposite move U is chosen.](figure-12-step15-placeholder)

*The move (15,16) is equivalent to (3,4) which was D. But D move from 15 leads to a cell that is already filled (with 7). Hence as per Rule 6 the opposite move U is chosen.*

<!-- figure-unresolved: figure=12-step15 page_meta=134 chunk_pages=11-15 -->

<!-- figure-meta: page=134, position=middle, type=diagram -->

### 4.8 Precisely arriving at all and only possible 384 variations

Based on the aforesaid rules, it can be observed that:
*   Having fixed a position for 1, there are four possible moves for placing 2. Thus the pair (1,2) can have four different configurations.
*   For a fixed position of 1, there are three possible moves for placing 3. However, there is only one position for placing 4 in accordance to the rules Rule 4.
Thus at this stage we see that there are totally $4 \times 3 = 12$ possible configurations.
*   Now if for a given arrangement of 1,2,3 and 4, only two possible positions are available for 5 satisfying the aforesaid
---
rule Rule 5. Thus considering the earlier result (12), we see that there are totally $12 \times 2 = 24$ possible configurations.
*   Once the numbers 1, 2, 3, 4, and 5 are fixed, the rest of the square has only a unique solution for being a pan diagonal magic square. In other words, positions of all other numbers (6, 7, ...16) get fixed once the first five are fixed.
The twenty-four possible combinations for placing the numbers 1, 2, 3, 4, and 5 by placing 1 at $M_{1,1}$ are shown in Fig. 9.
As the number 1 itself can occupy any of the sixteen cells of $M$, the total number of pandiagonal magic squares is $16 \times 24 = 384$, as stated by Nārāyaṇa Paṇḍita. However, there are 7,040 different configurations of normal magic squares of order 4 that are possible (Lehmer, 1933).

## 5 Properties of Nārāyaṇa Paṇḍita’s $4 \times 4$ pandiagonal magic squares

A close and careful study of the pandiagonal magic squares of order four, reveals that there are a several interesting properties. In what follows we first lay down these properties and subsequently also provide proofs of them.
P1: The sum of elements in any $2 \times 2$ square across the torus of a pandiagonal magic square ($M$) of order four yields the magic sum ($S$).
P2: The sum of elements in any two cells that are separated by one cell in between them (*koṣṭhaikāntara*) along the diagonal on a pandiagonal magic square of order four yields half the magic sum ($S/2$).
P3: In a $4 \times 4$ pandiagonal magic square, ONLY four cells are in HM, with any given cell (see Fig. 10). Considering any two of these four cells, the sum of the elements in them will be the same as the sum of the elements in the two cells that are at once in HM with them.

![Fig. 13. All possible ways of placing 1 to 5 with 1 fixed at the top left corner cell (1,1)](figure-13-placeholder)

*Fig. 13. All possible ways of placing 1 to 5 with 1 fixed at the top left corner cell (1,1)*

<!-- figure-unresolved: figure=13 page_meta=135 chunk_pages=11-15 -->

<!-- figure-meta: page=135, position=middle, type=diagram -->

**Fig. 9** All possible ways of placing 1 to 5 with 1 fixed at the top left corner cell (1,1)

![Fig. 13. Possible four HMs from the top left cell](figure-13-hm-placeholder)

*Fig. 13. Possible four HMs from the top left cell*

<!-- figure-unresolved: figure=13-hm page_meta=135 chunk_pages=11-15 -->

<!-- figure-meta: page=135, position=bottom, type=diagram -->

**Fig. 10** Possible four HMs from the top left cell
---
P4: The difference between the sum of the elements in the four HM cells (from any given cell), and twice the element in that (cell), would again yield half the magic sum ($S/2$).
P5: For any chosen number of the arithmetic series occupying any of the 16 cells in a pandiagonal magic square ($M$), the set of four other numbers occupying the four HM cells from that chosen cell are UNIQUE.
Of these five properties, Rosser and Walker (1938) studied properties P1 and P2. Vijayaraghavan (1941) has sort of indicated property P4 and P5. To our knowledge, till date P3 has not been identified and stated by scholars. As we shall see later, this property is extremely useful in proving P5.
Drawing from the above mentioned works, in what follows we provide proofs for these properties. The proofs of some of the latter properties have a dependency on the former. Hence, we suggest the readers to go through the proofs sequentially. To clarify and reinforce the notation employed by us, please see Fig. 11. Here $M$ be a pandiagonal magic square of order four, whose magic sum is $S$. The elements filling the square $M$ are denoted by $m_{ij} (i, j = 1, \dots 4)$.

### 5.1 Proof for property P1

By definition, in any magic square the sum of the elements in rows and columns add up to the magic sum. Considering the sum of the first two rows and last two columns we have,

$$(m_{11} + m_{12} + m_{13} + m_{14} + m_{21} + m_{22} + m_{23} + m_{24}) = 2S \quad (2)$$

$$(m_{13} + m_{23} + m_{33} + m_{43} + m_{14} + m_{24} + m_{34} + m_{44}) = 2S \quad (3)$$

Equating (2) and (3) we get,

$$m_{11} + m_{12} + m_{21} + m_{22} = m_{33} + m_{43} + m_{34} + m_{44} \quad (4)$$

The implication of the equation (4) is that the sum of the elements in the two specific $2 \times 2$ square depicted in Fig. 12 by shaded regions are the same.
What this sum is is not known. It can be easily shown that this sum is equal to the magic sum ($S$).
For this we invoke one of the most crucial criterion that must be satisfied for a square to be considered pandiagonal. That is, leading and broken diagonal elements must independently add up to the magic sum ($S$). Thus we have,

$$m_{11} + m_{22} + m_{33} + m_{44} = S \quad (5)$$

$$m_{21} + m_{12} + m_{43} + m_{34} = S \quad (6)$$

Adding (5) and (6) we get

$$(m_{11} + m_{12} + m_{21} + m_{22}) + (m_{33} + m_{34} + m_{43} + m_{44}) = 2S \quad (7)$$

From (4) and (7) it is evident that

$$m_{11} + m_{12} + m_{21} + m_{22} = S = m_{33} + m_{34} + m_{43} + m_{44} \quad (8)$$

Thus through equations (4) and (8) we’ve shown that the sum of two specific $2 \times 2$ squares are equal and that this sum is equal to the magic sum ($S$). What remains to be shown is that this is not specific to these two $2 \times 2$ squares but is true for any $2 \times 2$ square across the torus. This can also be easily done.
For instance, by considering the first two rows and the first two columns and forming equations like (2) and (3), and equating them it can be shown that

$$m_{13} + m_{14} + m_{23} + m_{24} = m_{31} + m_{32} + m_{41} + m_{42}. \quad (9)$$

| $m_{11}$ | $m_{12}$ | $m_{13}$ | $m_{14}$ |
| :--- | :--- | :--- | :--- |
| $m_{21}$ | $m_{22}$ | $m_{23}$ | $m_{24}$ |
| $m_{31}$ | $m_{32}$ | $m_{33}$ | $m_{34}$ |
| $m_{41}$ | $m_{42}$ | $m_{43}$ | $m_{44}$ |

**Fig. 11** Panmagic square $M$ with generic elements considered for proving properties

![Fig. 14. Sum of elements in the shaded $2 \times 2$ squares are equal](figure-14-placeholder)

*Fig. 14. Sum of elements in the shaded $2 \times 2$ squares are equal*

<!-- figure-unresolved: figure=14 page_meta=136 chunk_pages=11-15 -->

<!-- figure-meta: page=136, position=top, type=diagram -->

**Fig. 12** Sum of elements in the shaded $2 \times 2$ squares are equal
---
This can also be seen to be equal to the magic sum ($S$), by considering the condition of pandiagonality. That is,

$$m_{14} + m_{23} + m_{32} + m_{41} = m_{33} + m_{34} + m_{43} + m_{44} = S \quad (10)$$

In a similar manner by considering different rows and columns it can be proved that in any pandiagonal magic square of order four, the sum of elements of any $2 \times 2$ square yields the magic sum ($S$).

### 5.2 Proof for Property P2

From P1 we know that

$$m_{11} + m_{12} + m_{21} + m_{22} = S \quad (11)$$

$$m_{21} + m_{22} + m_{31} + m_{32} = S \quad (12)$$

Equating (11) and (12) we get,

$$m_{11} + m_{12} = m_{31} + m_{32} \quad (13)$$

Now consider the sum of elements in the third row of the square $M$. We have,

$$m_{31} + m_{32} + m_{33} + m_{34} = S \quad (14)$$

Using (13) and (14) we get,

$$m_{11} + m_{12} + m_{33} + m_{34} = S \quad (15)$$

By definition, any broken diagonal of $M$ must add up to the magic sum ($S$). So we have,

$$m_{21} + m_{12} + m_{43} + m_{34} = S \quad (16)$$

Equating (15) and (16) we get,

$$m_{11} + m_{33} = m_{21} + m_{43} \quad (17)$$

Considering the sum of elements of the third column in $M$, we have:

$$m_{13} + m_{23} + m_{33} + m_{43} = S \quad (18)$$

And from P1 we know that,

$$m_{11} + m_{12} + m_{21} + m_{22} = S \quad (19)$$

$$m_{12} + m_{13} + m_{22} + m_{23} = S \quad (20)$$

Equating (19) and (20) we get,

$$m_{11} + m_{21} = m_{13} + m_{23} \quad (21)$$

Using (21) in (18) we get,

$$m_{11} + m_{21} + m_{33} + m_{43} = S \quad (22)$$

From (17) and (22) it is evident that

$$m_{11} + m_{33} = m_{21} + m_{43} = S/2, \quad (23)$$

Thus we have shown that property P2 is valid with respect to the two pairs of cells that are separated by one cell along the diagonal (that is in *koṣṭhaikāntara*). By appropriately choosing different $2 \times 2$ squares, rows, columns etc. and making similar arguments it can be shown that this is valid for any pairs of cells that are in *koṣṭhaikāntara*.

### 5.3 Proof for property P3

Consider any two cells that are in HM with the cell in the top left corner of the magic square. This choice can be made in two different ways, either by choosing the cells that are
(a) Along the same row/column (2 possibilities) or:
($m_{23}, m_{43}$) or ($m_{32}, m_{34}$)
(b) Along the diagonal (4 possibilities):
($m_{23}, m_{32}$), ($m_{23}, m_{34}$), ($m_{43}, m_{32}$) or ($m_{43}, m_{34}$)
Now consider the two cells[^8] ($m_{23}, m_{43}$) that are along the same column. It may be noted that $m_{11}, m_{31}$ are the only two cells that are in HM with $m_{23}$ and $m_{43}$ simultaneously. The sum of elements in the third row is given by,

$$m_{13} + m_{23} + m_{33} + m_{43} = S \quad (24)$$

By P2, we also know that,

$$m_{11} + m_{33} = S/2 \text{ and } m_{13} + m_{31} = S/2 \quad (25)$$

Using (25) in (24) we have,

$$S = (S/2 - m_{31}) + m_{23} + (S/2 - m_{11}) + m_{43}$$

$$= S - (m_{11} + m_{31}) + (m_{23} + m_{43}).$$

Therefore,

$$(m_{11} + m_{31}) = (m_{23} + m_{43}). \quad (26)$$

By considering the sum of the elements in row three, and and arguing in a similar manner it can be easily shown that,

$$(m_{11} + m_{13}) = (m_{32} + m_{34}). \quad (27)$$

This means that sum of elements of the two cells which are in same row/column, with one cell in between, is equal to sum of elements in those cells that are at once in HM with these two cells.
We now consider the other case where the two of the four cells that diagonally adjacent to each other. For instance, let us choose the pair with elements ($m_{23}, m_{32}$). These are

[^8]: Here we are referring to the cells by the elements occupying them.

anyway in HM with $m_{11}$. The only other cell with which it is at once in HM is with $m_{44}$. Now we need to prove that the sum of $m_{11}$ and $m_{44}$ is the same as the sum of the adjacent pair ($m_{23}, m_{32}$).
For this, consider the $2 \times 2$ cell made up of ($m_{22}, m_{23}, m_{32}, m_{33}$). By virtue of the property P1, we have

$$m_{22} + m_{23} + m_{32} + m_{33} = S \tag{28}$$

We also know by P2 that,

$$m_{11} + m_{33} = S/2 \text{ and } m_{22} + m_{44} = S/2, \tag{29}$$

Using (29) in (28) we have,

$$S = (S/2 - m_{44}) + m_{23} + m_{32} + (S/2 - m_{11})$$

$$= S - (m_{11} + m_{44}) + (m_{23} + m_{32})$$

Therefore,

$$(m_{11} + m_{44}) = (m_{23} + m_{32}) \tag{30}$$

By considering any of the other three pairs listed above, that are diagonally adjacent to each other, we can prove that the sum of elements in cells which are diagonally adjacent to each other is equal to sum of elements in the only two cells that are at once in HM with them.
Therefore, from (27) and (30), it is amply evident that sum of elements in two cells (diagonal or otherwise) that have common HM is equal to sum of cells with which they are in HM, which is the property P3.

## 5.4 Proof of property P4

To prove this property, consider the $3 \times 3$ square formed by the cells, of magic square $M$, in the right bottom, leaving out the first row and column. In this $3 \times 3$ square we can further choose four $2 \times 2$ squares consisting of adjacent cells. Doing so, and applying property P1 we obtain the following equation:

$$(m_{22} + m_{23} + m_{32} + m_{33}) +$$

$$(m_{23} + m_{24} + m_{33} + m_{34}) + \tag{31}$$

$$(m_{32} + m_{33} + m_{42} + m_{43}) +$$

$$(m_{33} + m_{34} + m_{43} + m_{44}) = 4S$$

Again by property P2 we have,

$$m_{22} + m_{44} + m_{42} + m_{24} = S \tag{32}$$

Using (32) in (31) we get,

$$2m_{23} + 2m_{32} + 2m_{34} + 2m_{42} + 4m_{33} = 3S \tag{33}$$

Once more invoking the relation $m_{11} + m_{33} = S/2$, in the above equation and doing some algebraic manipulation, it reduces to

$$(m_{23} + m_{32} + m_{34} + m_{43}) = S/2 + 2m_{11}. \tag{34}$$

Rearranging the terms we have,

$$(m_{23} + m_{32} + m_{34} + m_{43}) - 2m_{11} = S/2. \tag{35}$$

thereby proving property P4.

## 5.5 Proof of property P5

Equipped with these properties proved above, we are now in a position to prove property P5 as well which essentially states that for any given number, the entries in the four cells that are in HM with this cell are unique—irrespective of the cell in which the given number is placed.
We shall first prove this by considering a typical example. The example that we choose is a magic square with $m_{11} = 1$. What we need to demonstrate is that for number 1 that is placed in particular cell, the ONLY four numbers that can occupy the four HM positions from it are (2,3,5,9). To show this, we first consider equation (34). With $m_{11} = 1$, the equation reduces to:

$$(m_{23} + m_{32} + m_{34} + m_{43}) = 17 + 2(1) = 19 \tag{36}$$

Table 3 lists out all and only combinations of non-repetitive numbers from the set of 15 numbers (2, 3, ...16) that satisfy (36).
In Table 3, but for the set of numbers in the second row, all other five sets have been indicated as non-acceptable. The reasons for declaring these sets to be so are furnished below by considering the sets appearing in different rows sequentially.
**Row 1:** The set (2,3,4,10) cannot be a possible set because, of a contradiction. What’s the contradiction? By definition, all the four numbers that appear in the set have to be in HM with 1. Also by property P3, any two numbers ($p, q$) chosen from the set must satisfy the following equation:

### Table 3 Sets of all four numbers whose sum is 19

| No | Set of 4 numbers | Acceptable/otherwise |
| :--- | :--- | :--- |
| 1 | (2, 3, 4, 10) | Not acceptable |
| 2 | (2, 3, 5, 9) | Only acceptable set |
| 3 | (2, 3, 6, 8) | Not acceptable |
| 4 | (2, 4, 5, 8) | Not acceptable |
| 5 | (2, 4, 6, 7) | Not acceptable |
| 6 | (3, 4, 5, 7) | Not acceptable |

$$p + q = 1 + r \text{ (‘$r$’ in HM with } (p, q)) \tag{37}$$

With $(p, q) = (2, 3)$ the above equation will be satisfied only if $r = 4$. This means that, 4 has to be necessarily in HM with (2,3). This is impossible if the number 4 appears along with 2 and 3 in the set. Hence the set (2,3,4,10) has to be abandoned as a possible set.
**Row 3:** The set (2,3,6,8) is also not acceptable for the same reason stated above. Assume $(p, q) = (3, 6)$. Now equation (37) will be satisfied only if $r = 8$. This means that, 8 has to be necessarily in HM with (3,6). This clearly eliminates the possibility of 8 appearing with the set having 3 and 6. Hence the set (2,3,6,8) is ruled out as a possibility.
**Row 4:** The set (2,4,5,8) is also not a possible set because of the same reason. If we take $(p, q) = (4, 5)$, then (37) implies $r = 8$. Since 8 has to be in HM with (4,5), it cannot be a part of the set. But it is, and hence the set in (2,4,5,8) is ruled out.
**Rows 5, 6:** The sets (2,4,6,7) and (3,4,5,7) are also not possible candidates. This is because if we take $(p, q) = (2, 6)$ or (3, 5), then according to (37) $r = 7$. Since it has to be in HM with the considered pairs of numbers, it cannot be a part of the set.
Thus by the process of elimination, we have proved that the only possible set of four numbers that can be in HM with number 1 is (2,3,5,9) as shown in the Fig. 13a. In other words, the set of four numbers is fixed and unique. Needless to say, these four numbers can be placed in 4! ways. However, once these four numbers are fixed in the four cells, the places of all other numbers in the magic squared are fixed.
Thus far, we have only proved that the 4 numbers that are in HM with 1 in the pandiagonal magic square with elements (1, 2, 3, ...16), is given by the set (2,3,5,9), which is unique. In a similar manner, by considering the number 2, and all the possible sets of four numbers (which is incidentally 13) which give a sum of 21, by the process of elimination as indicated above, one can show that, only the set (1, 4, 6, 10) can be accepted as a possible set as shown in 13b.
Likewise, by considering any of the 14 numbers (3, 4, ...16), and the sets of four numbers corresponding to the sum dictated by (34), and eliminating the impossible sets, we can get a unique set, thus proving property P5. Table 4 presents the fixed set of numbers that get positioned by HMs from a given number.

### Table 4 Set of numbers positioned in HMs with respect to a given number

| Given number | Set of numbers positioned by HMs | | | |
| :--- | :--- | :--- | :--- | :--- |
| | Within the pair | Within pair of pairs | With adjacent pair of pairs | With the next to adjacent pair of pairs |
| 1 | 2 | 3 | 5 | 9 |
| 2 | 1 | 4 | 6 | 10 |
| 3 | 4 | 1 | 7 | 11 |
| 4 | 3 | 2 | 8 | 12 |
| 5 | 6 | 7 | 1 | 13 |
| 6 | 5 | 8 | 2 | 14 |
| 7 | 8 | 5 | 3 | 15 |
| 8 | 7 | 6 | 4 | 16 |
| 9 | 10 | 11 | 13 | 1 |
| 10 | 9 | 12 | 14 | 2 |
| 11 | 12 | 9 | 15 | 3 |
| 12 | 11 | 10 | 16 | 4 |
| 13 | 14 | 15 | 5 | 9 |
| 14 | 13 | 16 | 6 | 10 |
| 15 | 16 | 13 | 7 | 11 |
| 16 | 15 | 14 | 8 | 12 |

# 6 Conclusion

In this study, having set the context and content of the text *Gaṇitakaumudī*, we highlighted the motivation for studying the *turagagati* method of constructing $4 \times 4$ pandiagonal magic squares as elucidated by Nārāyaṇa Paṇḍita. The verses that present this method in the *Gaṇitakaumudī* allows scope for interpreting the algorithm to either place the pairs from a sequence only through HMs or by considering moves in addition to HMs. The current paper presents the algorithms pertaining to construction of pandiagonal magic square purely through HMs only.
We have completely worked out the algorithm for constructing the magic squares using moves that involve moves other than HMs. However, we felt that the algorithm that employs only HMs (Sect. 4) is far more elegant. Of foremost importance to Indian mathematicians is simplicity and an optimised set of rules. This inclination is visible throughout the mathematical tradition of India. Hence the algorithm that employs only the HMs by taking pairs in order and by jumping the order, within the pair, within pair of pairs and across pair of pairs, seems to be the way that befits the above said factor.

![Fig. 13. Numbers in HMs from 1, 2, 3 and 4](media/p18_page.png)

*Fig. 13. Numbers in HMs from 1, 2, 3 and 4*

<!-- figure-resolved-page-render: page=18 image=media/p18_page.png -->

<!-- figure-meta: page=18, position=top, type=diagram -->

This work also highlights the most impressive advancement of magic square construction in the 14th century CE, as well as the genius of Nārāyaṇa Paṇḍita for having presented the method with great nuance and precision. What we have presented in this paper is only a small section of the *Bhadragaṇita* chapter in the *Gaṇitakaumudī*. Other sections of this chapter offer immense scope to study further, mathematically analyse and present the various methods elucidated by Nārāyaṇa Paṇḍita. The very same algorithm too has to be analysed for larger squares of order $4n$ to see how to further refine the conditions while scaling the order of the square. This interesting domain of *Bhadragaṇita*, thus, never ceases to stimulate the researcher and the learner. We intend to present such studies in subsequent papers.

## Appendix: All $4 \times 4$ pandiagonal magic squares with fixed position of the first element

This appendix presents all the 24 possible pandiagonal magic squares that can be constructed with 1 in the top-left cell (Fig. 14).

![Fig. 14. All possible ways with 1 fixed at the top left corner cell (1,1)](media/p19_page.png)

*Fig. 14. All possible ways with 1 fixed at the top left corner cell (1,1)*

<!-- figure-resolved-page-render: page=19 image=media/p19_page.png -->

<!-- figure-meta: page=19, position=top, type=diagram -->

### B1

| 1 | 14 | 11 | 8 |
|---|---|---|---|
| 12 | 7 | 2 | 13 |
| 6 | 9 | 16 | 3 |
| 15 | 4 | 5 | 10 |

### B2

| 1 | 14 | 7 | 12 |
|---|---|---|---|
| 8 | 11 | 2 | 13 |
| 10 | 5 | 16 | 3 |
| 15 | 4 | 9 | 6 |

### B3

| 1 | 8 | 11 | 14 |
|---|---|---|---|
| 12 | 13 | 2 | 7 |
| 6 | 3 | 16 | 9 |
| 15 | 10 | 5 | 4 |

### B4

| 1 | 12 | 7 | 14 |
|---|---|---|---|
| 8 | 13 | 2 | 11 |
| 10 | 3 | 16 | 5 |
| 15 | 6 | 9 | 4 |

### B5

| 1 | 12 | 13 | 8 |
|---|---|---|---|
| 14 | 7 | 2 | 11 |
| 4 | 9 | 16 | 5 |
| 15 | 6 | 3 | 10 |

### B6

| 1 | 8 | 13 | 12 |
|---|---|---|---|
| 14 | 11 | 2 | 7 |
| 4 | 5 | 16 | 9 |
| 15 | 10 | 3 | 6 |

### B7

| 1 | 8 | 11 | 14 |
|---|---|---|---|
| 15 | 10 | 5 | 4 |
| 6 | 3 | 16 | 9 |
| 12 | 13 | 2 | 7 |

### B8

| 1 | 12 | 7 | 14 |
|---|---|---|---|
| 15 | 6 | 9 | 4 |
| 10 | 3 | 16 | 5 |
| 8 | 13 | 2 | 11 |

### B9

| 1 | 14 | 11 | 8 |
|---|---|---|---|
| 15 | 4 | 5 | 10 |
| 6 | 9 | 16 | 3 |
| 12 | 7 | 2 | 13 |

### B10

| 1 | 14 | 7 | 12 |
|---|---|---|---|
| 15 | 4 | 9 | 6 |
| 10 | 5 | 16 | 3 |
| 8 | 11 | 2 | 13 |

### B11

| 1 | 12 | 13 | 8 |
|---|---|---|---|
| 15 | 6 | 3 | 10 |
| 4 | 9 | 16 | 5 |
| 14 | 7 | 2 | 11 |

### B12

| 1 | 8 | 13 | 12 |
|---|---|---|---|
| 15 | 10 | 3 | 6 |
| 4 | 5 | 16 | 9 |
| 14 | 11 | 2 | 7 |

### B13

| 1 | 15 | 10 | 8 |
|---|---|---|---|
| 12 | 6 | 3 | 13 |
| 7 | 9 | 16 | 2 |
| 14 | 4 | 5 | 11 |

### B14

| 1 | 15 | 6 | 12 |
|---|---|---|---|
| 8 | 10 | 3 | 13 |
| 11 | 5 | 16 | 2 |
| 14 | 4 | 9 | 7 |

### B15

| 1 | 15 | 10 | 8 |
|---|---|---|---|
| 14 | 4 | 5 | 11 |
| 7 | 9 | 16 | 2 |
| 12 | 6 | 3 | 13 |

### B16

| 1 | 15 | 6 | 12 |
|---|---|---|---|
| 14 | 4 | 9 | 7 |
| 11 | 5 | 16 | 2 |
| 8 | 10 | 3 | 13 |

### B17

| 1 | 15 | 4 | 14 |
|---|---|---|---|
| 8 | 10 | 5 | 11 |
| 13 | 3 | 16 | 2 |
| 12 | 6 | 9 | 7 |

### B18

| 1 | 15 | 4 | 14 |
|---|---|---|---|
| 12 | 6 | 9 | 7 |
| 13 | 3 | 16 | 2 |
| 8 | 10 | 5 | 11 |

### B19

| 1 | 8 | 10 | 15 |
|---|---|---|---|
| 12 | 13 | 3 | 6 |
| 7 | 2 | 16 | 9 |
| 14 | 11 | 5 | 4 |

### B20

| 1 | 12 | 6 | 15 |
|---|---|---|---|
| 8 | 13 | 3 | 10 |
| 11 | 2 | 16 | 5 |
| 14 | 7 | 9 | 4 |

### B21

| 1 | 8 | 10 | 15 |
|---|---|---|---|
| 14 | 11 | 5 | 4 |
| 7 | 2 | 16 | 9 |
| 12 | 13 | 3 | 6 |

### B22

| 1 | 12 | 6 | 15 |
|---|---|---|---|
| 14 | 7 | 9 | 4 |
| 11 | 2 | 16 | 5 |
| 8 | 13 | 3 | 10 |

### B23

| 1 | 14 | 4 | 15 |
|---|---|---|---|
| 8 | 11 | 5 | 10 |
| 13 | 2 | 16 | 3 |
| 12 | 7 | 9 | 6 |

### B24

| 1 | 14 | 4 | 15 |
|---|---|---|---|
| 12 | 7 | 9 | 6 |
| 13 | 2 | 16 | 3 |
| 8 | 11 | 5 | 10 |

**Acknowledgements** The authors would like to place on record their sincere gratitude to Ministry of Education (MoE), Government of India for the generous support extended to them to carry out research activities on Indian science and technology by way of initiating the Science and Heritage Initiative (SandHI) at IIT Bombay. They are also very grateful to the History of Mathematics in India (HOMI) project of IIT Gandhinagar for the generous support. Additionally, one of the authors expresses his unreserved gratitude to the Prime Minister's Research Fellowship granted to him by MoE. Also, many thanks to Prof. M. D. Srinivas for initial discussions on the topic and to the anonymous referee for their useful suggestions.

# References

Bhowmik (2018). Personal communication.
Brown, P. G. (1997). The magic of Moschopoulos. *Parabola*, *33*(3), 1–6.
Gupta, R. C. (2005). Early Pandiagonal magic squares in India. *Bulletin of Kerala Mathematics Association*, *2*, 25–44.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2019). Magic squares in India. *Studies in Indian mathematics and astronomy: Selected articles of Kripa Shankar Shukla* (pp. 377–437). Springer.
Kusuba, T. (1993). *Combinatorics and magic squares in India : a study of Nārāyaṇa Paṇḍita’s “Gaṇitakaumudī”*.
Lehmer, D. N. (1933). A census of squares of order four. *Bulletin of the American Mathematical Society*, *39*, 981.
Ramanujan, S., Aiyangar, S. R., & Berndt, B. C. (1985). *Ramanujan’s notebooks: Part I*. Springer.
Ramasubramanian, K. (2019). Early Pandiagonal Magic Squares in India. *Gaṇitānanda: Selected Works of Radha Charan Gupta on History of Mathematics* (pp. 299–312). Singapore: Springer.
Rosser, B., & Walker, R. J. (1938). On the transformation groups of diabolic magic squares of order four. *Bulletin of the American Mathematical Society*, *44*, 416–420.
Sesiano, J. (2019). *Magic squares*. Springer.
Shukla, K. S., & (revised). Bibhutibhusan Datta and Avadhesh Narayan Singh. (1992). Magic squares in India. *Indian Journal of History of Science*, *27*(1), 51–120.
Singh, Paramanand. (1978). *A critical study of the contributions of Nārāyaṇa Paṇḍita to Hindu Mathematics*. Bihar University.
Singh, Paramanand (1998-2002). Ganita Kaumudi of Nārāyaṇa Pandita, Translation and notes in *Ganita Bharati*, New Delhi, Vols. 20–24.
Vijayaraghavan, T. (1941). On Jaina magic squares. *The Mathematical Student*, *9*(3), 97–102.
Springer Nature or its licensor (e.g. a society or other partner) holds exclusive rights to this article under a publishing agreement with the author(s) or other rightsholder(s); author self-archiving of the accepted manuscript version of this article is solely governed by the terms of such publishing agreement and applicable law.
