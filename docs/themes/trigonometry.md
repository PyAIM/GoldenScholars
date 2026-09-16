# Trigonometry

## The Branch of Mathematics Most Fully "Made in the Islamic World"

Greek astronomy computed with the **chord** of an arc; Indian astronomy introduced the half-chord, the **sine**. The Islamic tradition took the Indian sine, added five more functions, proved the governing theorems, built the tables, and wrote the first books in which trigonometry is a mathematical subject rather than an astronomer's toolbox. Of all the major branches of school mathematics, trigonometry is the one whose creation as a discipline happened most completely within this tradition.

## The Function Set

- **Sine** (*jayb*): inherited from India, tabulated from the earliest zijes ([al-Khwarizmi](../scholars/era-01-foundations.md#al-khwarizmi), [Habash](../scholars/era-01-foundations.md#habash-al-hasib)). The Latin word *sinus* ("bay/fold") is a translation-by-mistake: Arabic *jyb/jayb* transliterated Sanskrit *jya/jiva*, but the consonantal skeleton was read as *jayb* "pocket, fold," which Gerard of Cremona rendered *sinus*. Every "sin" key on every calculator commemorates this mistranslation.
- **Tangent and cotangent**: born as **shadow functions**, the lengths of shadows cast by a standard gnomon, tabulated by Habash and fully theorized by [al-Biruni](../scholars/era-03-golden-age.md#al-biruni) in the *Exhaustive Treatise on Shadows*.
- **Secant and cosecant**: the corresponding hypotenuse ("diameter of the shadow") functions, in use by the tenth century.
- [Abu al-Wafa](../scholars/era-02-tenth-century.md#abu-al-wafa-al-buzjani) consolidated **all six**, proved the identities linking them, established addition and half/double-angle formulas in modern-equivalent form, and computed sines to high precision with a rigorous interpolation, his table's accuracy was not matched in Europe until the sixteenth century.

## The Theorems

- **Plane law of sines**: \(\dfrac{a}{\sin A} = \dfrac{b}{\sin B} = \dfrac{c}{\sin C}\), stated and proved within the tradition (attribution among Abu al-Wafa's generation and al-Tusi's systematization).
- **Spherical law of sines**: \(\dfrac{\sin a}{\sin A} = \dfrac{\sin b}{\sin B} = \dfrac{\sin c}{\sin C}\), the workhorse of astronomy, discovered c. 980–1000 (claimants: Abu al-Wafa, [Abu Nasr Mansur](../scholars/era-03-golden-age.md#abu-nasr-mansur), [al-Khujandi](../scholars/era-02-tenth-century.md#al-khujandi)); it replaced the clumsy Menelaus configuration.
- **Law of cosines**: solving a triangle from two sides and the included angle appears operationally in [al-Kashi](../scholars/era-07-samarkand.md#ghiyath-al-din-jamshid-al-kashi)'s *Key of Arithmetic*; French usage still calls the theorem *le théorème d'Al-Kashi*.
- **"Geber's theorem"** and the rule of four quantities in spherical right triangles ([Jabir ibn Aflah](../scholars/era-04-twelfth-century.md#jabir-ibn-aflah)).
- The **polar triangle** and the complete solution of spherical triangles from any three given parts ([Nasir al-Din al-Tusi](../scholars/era-05-maragha.md#nasir-al-din-al-tusi), *Treatise on the Complete Quadrilateral*, the first self-contained trigonometry book).

## The Tables

Trigonometric tables are numerical analysis in action: node spacing, interpolation schemes (linear, then second-order), and error control. Landmarks: Abu al-Wafa's sines; Ibn Yunus's *Hakimi Zij*; [al-Khalili](../scholars/era-06-fourteenth.md#al-khalili)'s ~13,000-entry universal auxiliary tables (functions of two and three variables); the Samarkand *Zij-i Sultani*'s sine and tangent tables at one-arcminute intervals; al-Kashi's \(\sin 1°\) by fixed-point iteration to ~16 decimal-equivalent places. The problem al-Kashi's iteration solves, getting from the constructible \(\sin 3°\) to \(\sin 1°\) through an irreducible cubic, is the *casus irreducibilis* that would later force Europeans (Bombelli, 1572) to take complex numbers seriously.

## The Applications That Drove It

Prayer times (spherical astronomy of the Sun's altitude), the **qibla** (a general spherical-triangle problem: given two points' coordinates, find the bearing of the great circle between them, solved exactly by Ibn Muadh, al-Biruni, and tabulated by al-Khalili), calendar visibility problems, geodesy (al-Biruni's Earth measurement), and cartography (al-Biruni analyzed map projections; stereographic projection theory underlies the astrolabe).

## Transmission and Modern Connection

Jabir ibn Aflah's Latin *Islah* and the astronomical corpus carried Islamic trigonometry to Europe, where Regiomontanus's *De triangulis omnibus* (1464) assembled the same edifice for Latin readers (with documented borrowings from Geber). From Regiomontanus the line runs through Rheticus's tables and Viète to the analytic trigonometry of Euler, who finally defined the functions on the unit circle as pure numbers, the modern subject. Every GPS fix, Fourier transform, and rotation matrix computes with the function set and theorems this tradition assembled: the sine in \(e^{i\theta} = \cos\theta + i\sin\theta\) walked to Europe from Baghdad, and to Baghdad from India.

*Sources: Glen Van Brummelen, The Mathematics of the Heavens and the Earth: The Early History of Trigonometry (2009), the standard modern history; Berggren, Episodes, chs. 5–6; Kennedy, Survey; King, In Synchrony with the Heavens.*
