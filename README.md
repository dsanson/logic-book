# Mastering Symbolic Logic

This is the source for the content of my open-source interactive logic "textbook",
[Mastering Symbolic
Logic](https://carnap.io/shared/dsanson@gmail.com/Book_s22).

This includes the reading, exercises, and supplements for each chapter. It
does not include the "Mastery Checks".

It is work in progress.

## Content and Design

This is yet another introductory logic textbook, 
 designed for a first course in symbolic logic.
Section I provides an informal introduction to the basic concepts of logic and argument analysis. 
Section II covers propositional logic, including translation, truth tables, and derivations.
Section III covers predicate logic, including translations, countermodels, and derivations.

The book uses the [Carnap variant of the Kalish-Montague system](https://carnap.io/srv/doc/montague.md){target="_blank"
rel="noopener noreferrer"} for natural deduction.

The book is designed to be online and interactive.
"Reading" assignments include multiple choice and 
 short answer comprehension questions, 
 meant to help the student actively engage.
They also include practice exercises,
 with embedded videos demonstrating solutions.

"Exercise" assignments are meant to provide the student
 the opportunity to practice the skills covered in the reading.

"Mastery Checks" are short (3 to 6 question) tests of how well
 the student has learned those skills.
The are meant to be low stakes,
 with a generous "retake" policy.

Most chapters also include a "Supplement",
 offering further practice, videos, and so on.

I've designed the book to support my use of a "mastery grading scheme".
The student's grade is based on how many units they complete and how many they
master, where completion is defined as:

-   Scoring 100% on the reading assignment
-   Scoring 80+% on the exercises
-   Scoring 60+% on the mastery check

And mastery is defined as:

-   Scoring 100% on the reading assignment
-   Scoring 80+% on the exercises
-   Scoring 80+% on the mastery check

## Adopting this book for your own courses

The design of this "book" is tightly tied to the design of my own courses.
It includes embedded videos of me yammering on.
It includes "progress bars" that are based on my grading scheme.
"Unit 0" just is my course syllabus, presented as a reading assignment.

So anyone considering using this book in their own course will likely need to
make substantial modifications.

Modifications would also need to be made to the custom javascript and CSS:

-   <https://github.com/dsanson/carnap-css>
-   <https://github.com/dsanson/carnap-custom-js>

Both include code that is specific to my courses.
Unfortunately, at this time, both are a bit of a mess,
 but I do hope to clean them up over time.

## Acknowledgments

This is designed to be used with 
 [Graham Leach-Krause](https://www.k-state.edu/philos/people/faculty/leachkrouse.html){target="_blank"
    rel="noopener noreferrer"}'s 
 [carnap.io](https://carnap.io){target="_blank" rel="noopener noreferrer"} project,
 an open-source "framework for teaching and studying formal logic." 
Carnap is responsible for machine grading all student work.
Without Carnap, or something like it, a book and course of this design would
not be possible.
I can't say enough good things about Carnap,
 and about Graham.

Before writing this book, I taught from Graham's book,

-   Graham Leach-Krause, [*The Carnap Book*](https://carnap.io/book/1){target="_blank" rel="noopener noreferrer"}

Some of the chapters of this book began as forks of chapters of Graham's book.

I also spent several years using
David Kaplan's [Logic 2010](https://logiclx.humnet.ucla.edu/){target="_blank" rel="noopener noreferrer"},
and the textbook bundled with Logic 2010,

-   [Terry Parsons](https://philosophy.ucla.edu/?p=3734){target="_blank"
    rel="noopener noreferrer"}, *An Exposition of Symbolic Logic*.

Those who have used this book will likely see its influence here.

In the background of both of these books is the classic textbook,

-   [Donald Kalish](https://en.wikipedia.org/wiki/Donald_Kalish){target="_blank"
    rel="noopener noreferrer"},
    [Richard Montague](https://en.wikipedia.org/wiki/Richard_Montague){target="_blank"
    rel="noopener noreferrer"}, and
    [Gary
    Mar](https://www.stonybrook.edu/commcms/philosophy/people/_faculty/mar.php){target="_blank"
    rel="noopener noreferrer"}, [*Logic: Techniques of Formal
    Reasoning*](http://www.worldcat.org/oclc/1113548568){target="_blank"
    rel="noopener noreferrer"}.

For a nice account of how 
 Kalish and Montague's text is related to other classic logic texts, 
 see Francis Pelletier, "[A History of Natural Deduction and Elementary Logic
Textbooks](https://www.sfu.ca/~jeffpell/papers/pelletierNDtexts.pdf){target="_blank"
rel="noopener noreferrer"}".
