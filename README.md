
<b> AUTORI: </b><b> Sima Andra, Sfectu Anda, Stancu Mirel</b>

<b>RUTE: </b>
Toate rutele sunt prefixate cu http://localhost:3001/.

<h1>Aplicatie web pentru acordarea de feedback continuu</h1>
<h2>Aspecte arhitecturale</h2>
Acest proiect are ca obiectiv realizarea unei aplicații web pentru acordarea de feedback continuu unei activitati (un curs sau seminar). Arhitectura va fi de tip Single Page Application accesibilă în browser de pe desktop, dispozitive mobile sau tablete (in functie de preferințele utilizatorului).
Front-end-ul va fi realizat cu ajutorul unui framework bazat pe componente, in React.js. Back-end-ul va avea o interfață REST și va fi realizat în node.js Stocarea se va face peste o bază relațională (SQLite) și accesul la baza se va face prin intermediul unui ORM (unui API de persistenţă și date expuse de un serviciu extern).

<b>1.Profesorii </b>– Acestia pot defini o activitate la o anumită dată , avand o descriere și un cod unic de acces la activitate pe care il utilizeaza studentii . Ei pot vedea feedback-ul anonim continuu cu momentele de timp asociate.

<b>2.Studentii </b>– tipul de utilizator care are acces la interfata pentru transmiterea feedback-ului, unde introduce codul activitatii, care trebuie sa fie valid si sa fie o activitate in desfasurare, pentru ca acest cod este activ doar in timpul aferent, capatat de la profesorul care il sustine. De asemenea, adauga o descriere a feedback-ului, precum o justificare, si emoticonul ales.

