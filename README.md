# Moroccan-Arabic-Latin-Orthography
A Latin Orthography for Moroccan Arabic, A better solution for Arabizi.

# Check Here
* **Full Proposal:** [README.md], **Read below** ⬇️
* **Brief Version:** [brief.md](https://github.com/abdelhaqueidali/Moroccan-Arabic-Latin-Orthography/blob/main/brief.md)
* **System Comparisons:** [comparison.md](https://github.com/abdelhaqueidali/Moroccan-Arabic-Latin-Orthography/blob/main/comparison.md)

---

# A Latin Orthography for Moroccan Arabic (Darija)

This repository presents a standardized Latin-script orthography for Moroccan Arabic (Darija), adapted directly from the established Amazigh-Latin system to resolve long-standing issues in conventional Darija writings. Rather than inventing new symbols or  reassigning new letters, this approach leverages an established alphabet already integrated into modern smartphone and desktop keyboards. By aligning with this system, Darija directly benefits from existing input methods, character sets, and computational infrastructure.

To demonstrate its practical application, this project includes comprehensive writing rules, and there will be in the future annotated text examples, song lyrics, and mini-dictionary glossaries. It is designed as a practical reference for anyone seeking a structured Latin-script solution for Darija.

## Scope & Intent
* **Framework First:** This proposal establishes the core orthographic rules (graphemes, word boundaries, and clitics). It deliberately excludes advanced grammatical standardization or regional lexical variants (e.g., choosing between *gelb* vs. *qelb*). Lexical standardization remains a separate effort.
* **Open for Improvement:** While functional and ready for use, this system remains open to feedback and refinement.

---

# ​A Latin Orthography for Moroccan Arabic (Amazigh Model)

## Introduction
Writing Moroccan Arabic (referred to as Darija) in the Arabic script remains the default orthography, accounting for the majority of written usage. It relies on the well-established conventions of Standard Arabic and remains the preferred choice for long-form writing, journalism, and projects such as the Moroccan Arabic Wikipedia. Despite some inconsistencies, it remains a solid choice for writing Darija. 

Latin-based writing, by contrast, is overwhelmingly dominated by Arabizi. It is used primarily in casual messaging, social media, and among diaspora communities online, where it facilitates seamless fast texting and easy code-switching between Darija and European languages. However, Arabizi was never designed as a true orthography; it was adopted organically as early computers lacked support for the Arabic script. Instead, it compresses Darija phonology into the basic 26-letter Latin alphabet by introducing numerals (such as 3, 7, and 9) to represent sounds absent from Latin. While this approach is efficient for rapid informal communication, its lack of standardized spelling conventions makes it unsuitable for sustained writing, educational materials, digital corpora, or computational processing.

Academic Latin transliteration systems also exist, but they serve linguists rather than everyday writers. These systems prioritize reversibility over usability. Furthermore, existing Latin renderings rarely agree on grammatical segmentation. Writers variously join or split grammatical elements, producing inconsistent forms.

This proposal builds upon the Standard Latin Amazigh orthography, which has already solved many of these design challenges, it also offers access to existing Azerty keyboards on computer systems and smarphones with the extended Latin letters. This system is suitable for Darija since Amazigh writing employs a dedicated letter for each phoneme, minimizes the use of diacritics, and applies consistent rules for word boundaries and morphology. 

The following sections present an adapted Latin orthography for Moroccan Darija that applies these same principles. The result is a practical writing system that is easy to use, yet precise enough for linguistic work and natural language processing.

---

## I. The Alphabet
The proposed Latin alphabet for Moroccan Darija consists of 29 primary letters:
**a, b, c, d, ḍ, e, ɛ, f, g, ɣ, h, ḥ, i, j, k, l, m, n, q, r, s, ṣ, t, ṭ, u, w, x, y, z**

This inventory closely follows the Standard Latin Amazigh alphabet while introducing only the symbols necessary to represent phonemic distinctions found in Darija.

### 1. Dedicated Letter for Ayn (ɛ)
Rather than using the academic modifier letter (ʿ) or the Arabizi numeral (3), this system adopts the full letter **ɛ / Ɛ** to represent the voiced pharyngeal fricative (/ʕ/). Unlike superscript symbols or apostrophe-like marks, **ɛ** functions as a normal alphabetic letter, making reading and typing considerably more intuitive.
*   *ɛeyn* / *ɛayn* (eye)
*   *ɛafa-k* (please)
*   *mɛa* (with)

### 2. A Single Letter for the "Sh" Sound (c)
The letter **c / C** represents the voiceless postalveolar fricative (/ʃ/). Since the Latin letter C has no independent phonetic function in Darija, it can be reassigned to this sound, eliminating the need for digraphs such as *sh* or *ch*, or the academic symbol *š*.
*   *cuf* (See/look)
*   *cbab* (Youths)
*   *mca* (He went)

### 3. A Dedicated Letter for Ghayn (ɣ)
The letter **ɣ / Ɣ** represents the voiced uvular fricative (/ʁ/). This replaces digraphs such as *gh* and academic forms such as *ġ*.
*   *ɣali* (expensive)
*   *deɣya* (quickly)

### 4. The Kh Sound (x)
The letter **x / X** represents the voiceless uvular fricative (/x/). This follows both IPA conventions and the Amazigh alphabet, avoiding digraphs like *kh* or specialized characters such as *ḫ*.
*   *xubz* / *xwbz* (Bread)
*   *xal* (Maternal uncle)

### 5. Unified Underdot System for Emphatics
All emphatic consonants are written using a single underdot. The primary emphatics are:
*   **ḍ** for ض
*   **ṣ** for ص
*   **ṭ** for ط

The letter **ḥ** also carries an underdot, not because it is emphatic, but to represent the voiceless pharyngeal fricative (ح), distinguishing it from ordinary *h* (ه).
*   *ḍur* (turn)
*   *ṣḥaḥ* (strong)
*   *ṭyyara* (airplane)
*   *ḥut* (fish)

**Secondary Emphatics:**
The letters **ṛ** and **ẓ** are not included in the standard set, they should not be used in a standard piege of writing using this system, however they may optionally be used where emphatic pronunciation exists independently of nearby emphatic consonants, where it may be important such 1s in phonetic transcription. Because emphasis naturally spreads across neighboring sounds, these markings are usually unnecessary (e.g., in *Ḍar*, the emphasis of *ḍ* makes *ṛ* redundant). However, where *z* and *r* exist in a word with no other emphatic letters, writers may choose to label one or both: *zher*, *ẓher*, *zheṛ* (labeling *ẓ* is recommended). All could be labeled according to the desired degree of phonetic precision.
Likewise, rare emphatic realizations of other consonants (ḅ, ṃ, ḷ) may be indicated with underdots in phonetic contexts, though such usage is should not be used in ordinary writing.

### 6. Omitted and Restricted Latin Letters
**The Letter O:**
The vowel *o* is omitted from standard spelling. In Darija, [o] is generally an allophonic realization of *u*, occurring next to emphatic or pharyngeal consonants. Writing both letters introduces unnecessary variation without representing a phonemic distinction.
*   Use *xubz* and *ḍur* (rather than *xobz* or *dor*).
Letter *a* has as well an allophonic which isn't in the standard 26 Latin Alphabet of European languahes, which us *ɑ*.
*  *dar* is what is being used for house and not *dɑr*, in this standard system, it would be preferable to write Ḍar as there is emphasis on *D*. 

**The Letters P and V:**
The letters *p* and *v* are reserved for recent loanwords in which these sounds remain distinct. Older borrowings continue to follow established Darija pronunciations.
*   *ppisṭac* (pistachio)
*   *ppnu* (tire)
*   *vitamin* (vitamin)
*   *villa* (villa)
*   *plastik (plastic)  

### 7. Foreign Words and Code-Switching
Foreign words, proper names, trademarks, and place names may retain their original Latin spelling when they have not been fully integrated into Darija. Respelling internationally recognized names phonetically often reduces readability while providing little practical benefit.
*   *Mcit l Paris.*
*   *ka nqra Python.*
*   *ɛend-i rendez-vous.*

When a foreign word becomes fully lexicalized in Darija, a phonetic spelling remains acceptable.
*  *baliza* (suit-case) from La valise. 
*  *jafil* (bleach) feom Javil.

### 8. The hamza
The hamza will be written using simply "e". A circumflex accent will be on *ê* if it is directly after a consonant to avoid mistaking it to a shwa.
*   *Aasmae* أسماء
*   *Fuead* فؤاد
*   *Mueassasa* مؤسسة
*   *Ietiman* ائتمان
*   *Faḍae* فضاء
*   *Juzê*, *ajzae* جزء، أجزاء

Where vowels meet, the "e" can be redundant, so another solution for this case where needed is:
*  *Fuad*
*  *Muassasa*
UA won't be read as WA, they would be U-A, also reading it as WA produces the natural sound that Darija speakers would say, especially the elderlied who can't pronounce the Hamza, youths usually can for being taught Standard Arabic.

Note:
At the start of words or after the definitive article *L*, it is usually normalized to a normal vowel.
*  *Leinsan* => *linsan*
*  *einsan* => *insan*
*  *Leimtiḥan* -> *Limtiḥan*
*  *eimtiḥan* -> *imtiḥan*

However, if the circumstances needs showing the Hamza for following Standard Arabic pronunciation or for dialect variants, there light be, the modifier letter apostrophe **ʼ** should be used:
*  *ʼinsan*
*  *lʼinsan*

A normal apostrophe can work in this case, after the definitive article or at the start of a word, however, it breaks words since it is a punctuation mark character. For example, if you write a hashtag, the modifier lether apostrophe works keeps the whole word it is in as one hashtag, while using an apostrophe breaks the hashtag to the point where that apostrophe is found.

### 9. Omission of the Labialization Marker (ʷ)
The modifier letter **ʷ** is omitted from the standard inventory to avoid redundancy. Instead, when labialization is phonemically distinct or necessary for clarity, it is represented using a standard **w**.
 * *lxḍra* (green – feminine)
*  *lxwḍra* (vegetables)
 
---

## II. Word Boundaries and Segmentation
A functional orthography requires predictable rules governing spaces, hyphens, and clitic attachment. This system balances readability with morphological transparency. Short grammatical elements attach directly to their host whenever possible, while hyphens are reserved for locations where they improve structural clarity, and also be economic with the hyphens as much as possible to not clutter texts with heavy hyphenations, hyphens are replaced with a space in some cases. 

### 1. The Definite Article
The definite article is always attached directly to the following noun. Native words beginning with moon consonants simply receive *l*:
*   *lbab* (the door)
*   *lqelb / lgelb* (the heart)
*   *lḥal* (the situation)

With sun consonants, assimilation is written directly through consonant doubling:
*   *ssuq* (the market)
*   *ccariɛ* (the street)
*   *ṭṭriq / ṭṭrig* (the road)

When the following word begins with an initial consonant cluster, an epenthetic *e* is inserted in speech (e.g., *lemdina*, *lekbir*).

For unintegrated foreign words, an apostrophe separates the article from the borrowed form:
*   *l'visa*
*   *l'podcast*
*   *l'PC*

Note: the apostrophe also used for verb affixation added to foreign verbs (e.g., *m'follow'in-ni* *they follow me - on social media*, it would be like this when respelled in Ddarija: *mfulwin-ni*) 

### 2. Aspect and Future Markers
Aspectual particles remain independent words, to reduce the hyphens, they are avoided in this case for its redundancy despite them being realized in speech as one element.
*   *ka ncuf*
*   *ka nekteb*
*   *ka idir*
*   *ɣa nji*
*   *ɣa nɛic*
*   *ɣadi tendem*

### 3. Negation
Negation follows the discontinuous pattern: **ma... -c**. The particle *ma* remains separate, no need for a hyphen, it keeps the text cleaner, while *-c* attaches to the end of the verbal complex.
*   *ma bɣit-c*
*   *ma ka ncuf-c*
*   *ma ndir-c*
*   *ma ɣadi-c*
*   *ma ka nɛerf-ha-c*

### 4. Prepositions
Simple prepositions remain separate before nouns.
*   *f lbal*
*   *f ddar*
*   *b ssif*
*   *b lḥubb*

When followed by pronominal suffixes, they should be hyphenated, however they can be glued for casual texting:
*  *li-ya* / *liya*
*  *li-k* / *lik*
*   *fi-ya* / *fiya*
*   *fi-k* / *fik*
*   *mɛa-na* / *mɛana*
*   *ɛli-hum* / *ɛlihum*


The forms where *i* is reduxed to *e*:
*  *li* (-ya is absent)  
*  *l-ek* / *lek*
*   *f-ek* / *fek*
*   *ɛl-ek* / *ɛlek*

### 5. Attached Pronouns
Pronominal suffixes aren written hyphenated to improve morphological transparency.
*   *qelb-i* / *gelb-i*
*   *raṣ-ek¹*
*   *jab-ha*
*   *ɛṭa-ni*

1: The "e" can be inserted where it appears before prominal suffixes and this concerns "-k" (e.g., *qelb-ek, ɛeyn-ek*) 

### 6. Demonstratives and Presentatives
Presentative particles and demonstratives follow the same principle, they should be hyphenated in standard texts, and can be glued together for everyday usage.
*   *ra-h* / *rah*
*   *ra-ni* / *rani*
*   *had-a* / *hada*
*   *had-i* / *hadi*
*   *had-uk* / *haduk*

Contracted demonstratives are always independent words:
*   *dak lweld*
*   *dik lbent*
*   *duk ddrari*

### 7. The Epenthetic Schwa (e)
Besides appearing as part of the conventional spelling of many Darija words, the letter *e* may also appear between morphemes to break difficult consonant clusters. This epenthetic schwa is not considered part of the lexical stem of the word, but a pronunciation aid that may surface depending on the grammatical form. **It can be placed where it is realized, especially when it is clear.**

**A. After the Definite Article**
When the definite article *l* precedes a noun beginning with a consonant cluster, an *e* is inserted.
*   *lemdina*
*   *lekbir*
*   *leɛmer*

**B. Before Attached Pronouns**
Likewise, an epenthetic vowel may appear before attached pronouns during speech but is generally omitted in writing.
*   *xellit-ek*, *dert-ek*, *qelb-ek*

**C. Movement of the Schwa**
Because the schwa is often not part of the lexical stem, its position may shift as prefixes, suffixes, or other elements are added or in alternative forms of the same word root.
*   *nɛes* (to sleep) -> *ka tenɛes* (you sleep / she sleeps)
*   *nsa* (to forget) -> *nessi* (to make someone forget) -> *ka nenssi* (I make someone forget)

**General Principle:** The schwa is written when it is realized, the clearer it is the more important to be written it becomes. When grammatical changes cause the schwa to shift position, each word form should simply be written according to its own natural pronunciation. And words that may take more than one form in placing that *e*, the one that follows the usual pattern of similar words is what should be chosen. This concerns Lexical standardization regarding spelling of words with different forms to a single one. This needs a solution at the level of lexical standardization. 

---

## III. Nouns (Isem)
Darija distinguishes masculine and feminine nouns.

**Masculine nouns** have no dedicated ending.
*   *rajel* (man)
*   *weld* (boy)
*   *qelb* (heart)
*   *bab* (door)

**Feminine nouns** mostly end in *-a*.
*   *mdina* (city)
*   *xedma* (work)
*   *lqeṣṣa* (story)
*   *ṭṭebla* (table)

The ending *-a* corresponds historically to the Arabic tae marbuṭa (ة). Although pronounced as *-a* in isolation, its underlying consonant is *t*, which reappears whenever another element follows.
*   *mdina* -> *mdint Zagura*
*   *xedma* -> *xedmt-i*
*   *hiwaya* -> *hiwayt-ek*

For this reason, the dictionary form is written with *-a*, while derived forms restore the historical *t*. An *ä* can be used for NLP and automation tools to mark this underlying *t*, and use *ẗ* where it becomes *t*, e.g., *mdinä* becomes *mdinẗ-na*, in both, this is just for automation oriented tasks not for user ready-to-read text forms. This approach keeps clear that it is an *a* and a *t* in both cases, only two dots are added on top to mark the etymological tae marbuta *ة* for text retrieving tools. 

---

## IV. Verbs (Fiɛel)
Darija verbs are built around consonantal roots and several derived stems. Conjugation is largely prefix- and suffix-based. Most verbs can be described using four principal forms: Imperative, Present, Past, and Participle.

### 1. The Imperative
The simplest verbal form, serving as the base for many derived patterns. Person endings attach directly.
*   *kul* - *kuli* - *kulu* (eat - you s., you s.f., you p.)
*   *sir* - *siri* - *siru* - (go)

### 2. Present
The present uses prefixes and suffixes that identify person:
*   Ana: **n-** (ka¹ *ncuf*)
*   Nta: **t-** (ka *tcuf*)
*   Nti: **t-...-i** (ka *tcufi*)
*   Huwa: **i-** (ka *icuf*)
*   Hiya: **t-** (ka *tcuf*)
*   Ḥna: **n-...-u** (ka *ncufu*)
*   Ntuma: **t-...-u** (ka *tcufu*)
*   Huma: **i-...-u** (ka *icufu*)

1: *ka* is added to help with realizing the verbs usage, you can replace it with other particles that go with the present verbs: e.g., xaṣṣ *tcuf*, ɣadi *ncuf*, ta *ncuf*, ma dertc *ncuf*-u lyum.

Habitual/progressive meaning uses **ka** or **ta**:
*   *ka ncuf* / *ta ncuf*
*   *ka tdir* / *ta tdir*

Future meaning uses **ɣa**, **ɣadi**, or **a**:
*   *ɣa ncuf*
*   *ɣadi nji*
*   *a nemci*

### 3. Past
The past distinguishes two stem shapes (Stem A and Stem B), which align with specific pronouns.
Example: *kla* (to eat)
*   **Stem A ("kli"):** Ana (*klit*), Nta (*kliti*), Nti (*kliti*), Ḥna (*klina*), Ntuma (*klitu*)
*   **Stem B ("kla"):** Huwa (*kla*), Hiya (*klat*), Huma (*klaw*)

*(Note: Sometimes "Hiya" gets -a added before -t when the verb ends in a consonant with no "a" before it. e.g., huwa nɛes, hiya nɛesat, while it syays just - t in huwa kla, hiya klat, huwa dar, hiya dart - ending in a consonant here doesn't trigger this change because it is "a" plus a consonant while the previous one is "e", in other cases where it is a consonant or a semi-vowel)*

### 4. Prefix Adjustments
Some prefixes change slightly to avoid impossible consonant clusters:
*   If a present stem begins with *tt* or *t*, the prefix *t* becomes *te*: (e.g., *hiya ɣa tttfehhem* => *hiya ɣa tettfehhem*)
*   *n + n...* becomes *ne...*: (e.g., *ana ɣa nnzel* => *ana ɣa nenzel*)
*   When a stem begins with a vowel, the third-person prefix *i-* becomes *y-*: (e.g., *akwl* => *huwa ka yakwl*)

### 5. Stem Alternations
The internal schwa is mobile. Its position changes when prefixes or suffixes are attached.
*   *nɛes* => *ka tenɛes*
*   *nsa* => *nessi* => *ka nenssi*

### 6. Participles
Darija has productive active and passive participles that inflect like adjectives.
*   **Masculine singular:** *dayer*, *medyur* | *kateb*, *mektub*
*   **Feminine singular:** *dayra*, *medyura*
*   **Masculine plural:** *dayrin*, *medyurin*
*   **Feminine plural:** *dayrat*
The stems are *dayer, medyur, kateb, mektub*. 

They frequently function as adjectives or verbal predicates:
*   *ana lli dayer imci l temma*
*   *hiya dayra nnegliziya*
*   *huma dayrin hukkak*

### 7. Negation
Verbs are negated with the discontinuous particle **ma... -c**.
*   *ma ncuf-c*
*   *ma ka nji-c*
*   *ma ɣa tdir-c*

---

## V. Text Examples

Had nneṣṣ mektub b waḥed l'orthography d Ddarija b llatini. Lhadaf huwa ikun ɛend-na waḥd ssistam lli isehhel lketba w f nafs lweqt ikun waḍḥ. Arabizi ma imken-c ixdem fac tji l scaling lli ɣa iḥtaj-u lwaḥd fac ibɣi ikteb qeṣṣa, ktab, wella muḥtawa b luɣa dqiqa. Hada ka iḥell lmuckil f janib ccekl llatini. Amma f janib lɛerbi fra-h meḥlul yaḍ w nnas ka istɛemlu-h ḥit kayna Lɛerbiya Lmiɛyariya Jjdida lli ka ihezzu ɛli-ha ṭriqt lketba, ka ibqqaw ɣa umur bsiṭa w sahla lli ka iqder ikun fi-hum niqac bac tettweḥḥed kter. Lhadaf men had lektba hiya llatini d Ddarija lli ma ɛendu-c ci ckel mnaseb lli iqderu nnas irejɛu li-h. iqder iban ṣɛib walakin ra-h ma ṣɛib-c ɛla Arabizi, b lɛeks, had-a sahel men naḥiya dyal lwuḍuḥ w ddiqqa w f nafs lweqt sahel f lketba w f leqraya.

* Ṣifṭ-u = Waḥed ṣifṭ ci ḥaja
* Ṣifṭu = ci weḥdin ṣifṭu ci ḥaja
* Dar = dar ci ḥaja
* Ḍar = leblaṣa fin ka isken lwaḥed
* B ac = b acmen ḥaja
* Bac = dir hakka bac tewḍaḥ ktebt-ek
* Wac mciti = wac derti lfiɛl
* W ac derti = w acnahiya lḥaja lli derti

Bzzaf dyal leḥwayj ka iwḍaḥ-u b had ssistam, w la ɛrefti kifac xeddam ɣa ishal tɛerf ki xeddam lḥerf d lɛerbiya f Ddarija, w teqder tṣeḥḥeḥ w tmeɛyer ktebt-ek bi-h ḥtta ḥewwa. 
