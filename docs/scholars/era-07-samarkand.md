# Era VII — Samarkand and the Fifteenth Century (1400–1500)

Ulugh Beg, grandson of Tamerlane and himself a competent mathematician, built at Samarkand an observatory and madrasa that assembled the century's best scientists. The result: the highest computational precision achieved anywhere in the world before logarithms, and the last universally acknowledged summit of the tradition. In the west, al-Qalasadi codified algebraic symbolism.

---

## Ghiyath al-Din Jamshid al-Kashi

**Ghiyath al-Din Jamshid ibn Masud al-Kashi** (c. 1380–1429) · Kashan, Samarkand · computation, arithmetic, trigonometry, astronomy

The greatest computational mathematician of the Middle Ages, anywhere.

**Pi.** In *al-Risala al-Muhitiyya* ("Treatise on the Circumference," 1424), al-Kashi computed \(2\pi\) using inscribed and circumscribed polygons of \(3 \times 2^{28}\) = 805,306,368 sides, obtaining the value in sexagesimal and converting to **16 correct decimal places**: \(2\pi \approx 6.2831853071795865\). This tripled the standing record (Madhava's school in Kerala had about 11 places by series; in the classical polygon line the previous best was Chinese, 7 places) and stood until Ludolph van Ceulen (c. 1596–1610). Crucially, al-Kashi **planned the precision in advance** by an error analysis: he chose the polygon count so the uncertainty would be less than the width of a horsehair on a circle the size of the known universe, precision engineering, not virtuosity for its own sake.

**Decimal fractions.** *Miftah al-Hisab* ("The Key of Arithmetic," 1427), his encyclopedia of practical and theoretical calculation, gives the first fully systematic treatment of **decimal fractions** as a general computational instrument (notation, all operations, conversions to and from sexagesimal), consciously modeled on sexagesimal practice. When Simon Stevin's *De Thiende* (1585) introduced decimal fractions to Europe, it was re-walking this ground; a line of transmission through Ottoman and Byzantine intermediaries has been suggested but not established.

**Root extraction and iteration.** The *Miftah* gives the general algorithm for extracting **\(n\)-th roots** (Ruffini–Horner-type digit-by-digit scheme) with the binomial table as its engine. His *Risala al-Watar wa-l-Jayb* (Treatise on the Chord and Sine) computes \(\sin 1°\) from the cubic \( \sin 3° = 3\sin 1° - 4\sin^3 1°\) by a **fixed-point iteration** whose convergence he exploits digit by digit, obtaining \(\sin 1°\) to about 9 sexagesimal places (~16 decimal digits' worth). This is textbook numerical analysis, iterate a contraction, harvest guaranteed digits, five centuries before the terminology.

**The law of cosines.** The *Miftah* solves triangles from two sides and the included angle by the method equivalent to \(c^2 = a^2 + b^2 - 2ab\cos C\); in France the result is still traditionally called the *théorème d'Al-Kashi*.

**Instruments and astronomy.** He directed computations for Ulugh Beg's *Zij-i Sultani*, invented the "Plate of Zones" analog computer for planetary positions, and his letters to his father from Samarkand are a unique inside account of a medieval research institute (including candid gossip about colleagues).

*Sources: DSB (A. P. Youschkevitch & B. Rosenfeld, "al-Kashi"); P. Luckey's classic studies of the Muhitiyya and the sine of 1°; Berggren, Episodes; Van Brummelen; Kennedy, "A Letter of Jamshid al-Kashi to His Father" (with Aydin Sayili's work on the observatory).*

---

## Qadi Zada al-Rumi

**Qadi Zada al-Rumi** (c. 1364 – c. 1436) · Bursa, Samarkand · geometry, astronomy, teaching

"The Judge's son from Rum (Anatolia)," who left Ottoman lands for Samarkand, became Ulugh Beg's teacher, and headed the madrasa's teaching. His commentary on al-Chaghmini's astronomy and on Shams al-Din al-Samarqandi's *Ashkal al-Ta'sis* (a compilation of 35 fundamental Euclid propositions) became standard madrasa textbooks for centuries across the Ottoman world, and he computed \(\sin 1°\) by a method paralleling al-Kashi's. After al-Kashi's death he led the observatory until his own; the *Zij-i Sultani* team's continuity ran through him.

*Sources: DSB; Fazlıoğlu's studies of Ottoman mathematics; Rosenfeld & Ihsanoglu.*

---

## Ulugh Beg

**Mirza Muhammad Taraghay ibn Shahrukh, "Ulugh Beg"** (1394–1449) · Samarkand · astronomy, patronage

Timurid prince (ruler of Transoxiana; briefly emperor), founder of the Samarkand madrasa (c. 1417–1420) and observatory (c. 1424–1429), whose main instrument, a meridian arc of roughly 40 m radius (the "Fakhri sextant," its underground portion excavated in 1908), pushed naked-eye positional accuracy to its practical limit. The observatory's masterwork, the ***Zij-i Sultani*** (c. 1437–1449), contains sine and tangent tables computed at intervals of one minute of arc, accurate to about nine sexagesimal-fractional-equivalent decimal places, and a **star catalogue of 1,018 stars from fresh observations**, essentially the first comprehensive re-observation of the sky since Ptolemy's (largely Hipparchus-derived) catalogue. Ulugh Beg was murdered in 1449 in a coup led by his son; the observatory decayed, and its staff dispersed, one, Ali Qushji, eventually to Istanbul, a documented conduit of Samarkand science toward the Ottoman world and its European contacts. The star catalogue was printed in Europe (Oxford, 1665, by John Greaves's and Thomas Hyde's orientalist circle) and used by European astronomers including in Flamsteed's era.

*Sources: DSB (T. Kari-Niazov, "Ulugh Beg"); Aydin Sayili, The Observatory in Islam; E. B. Knobel, Ulugh Beg's Catalogue of Stars (1917); Van Brummelen.*

---

## al-Qalasadi

**Abu al-Hasan Ali ibn Muhammad al-Qalasadi** (1412–1486) · Baza (al-Andalus), Granada, Tunisia · arithmetic, algebra, notation

The last major mathematician of al-Andalus (he fled the collapsing emirate of Granada and died in Tunisia). His arithmetic works, especially *Kashf al-Asrar an Ilm Huruf al-Ghubar* ("Unveiling the Secrets of the Dust Letters") and his commentaries on Ibn al-Banna, present the mature **Maghrebi algebraic symbolism**: dedicated signs derived from Arabic letters/words for the unknown (*shay*, ش), its square (*mal*, م), cube (*kab*, ك), for roots (from *jidhr*), equality (from *adala*), and a mark for "therefore/result", with these symbols written **in equations operated on as such**. He did not invent the system (it appears in Maghrebi manuscripts by the 12th–13th centuries) but he codified and popularized it. This is one of the world's earliest sustained algebraic symbolisms, roughly contemporary with (and independent of) the German cossist abbreviations, and well before Viète's letters (1591). No transmission to European symbolism is documented; the parallel evolution itself is historically instructive. He also treated the approximation of square roots by iterated refinement, and successive convergents of continued-fraction type.

*Sources: Woepcke's 19th-century notice; M. Abdeljaouad, "The eight hundredth anniversary of Maghrebian algebraic symbolism" and related studies; Djebbar; Katz.*

---

## Sibt al-Maridini

**Badr al-Din Muhammad Sibt al-Maridini** (1423 – c. 1506) · Cairo · arithmetic, astronomy, instruments

Muwaqqit at al-Azhar in Cairo and the most prolific author of **teaching texts** of his era: concise treatises on sexagesimal arithmetic (his *Raqa'iq al-haqa'iq fi hisab al-daraj wa-l-daqa'iq* on degrees-and-minutes computation was a standard), on the quadrant (the sine quadrant, or *rub al-mujayyab*, an analog trigonometric computer whose use his manuals made routine), and on inheritance arithmetic. His books remained in the curriculum of al-Azhar into the 19th century, a measure of how the late tradition institutionalized its computational toolkit.

*Sources: King, In Synchrony with the Heavens and his Cairo survey of scientific manuscripts; Rosenfeld & Ihsanoglu.*

---

## Ibn Ghazi al-Miknasi

**Ibn Ghazi al-Miknasi** (1437–1513) · Meknes, Fez · arithmetic, algebra

Maghrebi jurist and mathematician whose *Munyat al-Hussab* ("The Aspiration of Reckoners"), a poem, with his own prose commentary *Bughyat al-Tullab*, summarizes the Ibn al-Banna school's arithmetic and algebra at the end of its creative arc: numeration, fractions, roots, false position, algebra with the Maghrebi symbols. Valuable to historians as a late, complete snapshot of the western tradition just as printed European mathematics was beginning its ascent.

*Sources: Djebbar; Lamrabet; Rosenfeld & Ihsanoglu.*
