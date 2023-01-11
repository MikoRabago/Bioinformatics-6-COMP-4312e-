# Bioinformatics 6 (COMP 4312e)
A repository containing all the file projects that I have for the Bioinformatics 6 (COMP 4312e) course.

Link to this card: https://trello.com/c/HF32d968

Finding Mutations in DNA and Proteins (Bioinformatics VI)

About this Course
In previous courses in the Specialization, we have discussed how to sequence and compare genomes. This course will cover advanced topics in finding mutations lurking within DNA and proteins.

In the first half of the course, we would like to ask how an individual's genome differs from the "reference genome" of the species. Our goal is to take small fragments of DNA from the individual and "map" them to the reference genome. We will see that the combinatorial pattern matching algorithms solving this problem are elegant and extremely efficient, requiring a surprisingly small amount of runtime and memory.

In the second half of the course, we will learn how to identify the function of a protein even if it has been bombarded by so many mutations compared to similar proteins with known functions that it has become barely recognizable. This is the case, for example, in HIV studies, since the virus often mutates so quickly that researchers can struggle to study it. The approach we will use is based on a powerful machine learning tool called a hidden Markov model.

Finally, you will learn how to apply popular bioinformatics software tools applying hidden Markov models to compare a protein against a related family of proteins.

SYLLABUS
Finding Mutations in DNA and Proteins (Bioinformatics VI)

Introduction to Read Mapping
<p>Welcome to our class! We are glad that you decided to join us.</p>

<p>In this class, we will consider the following two central biological&nbsp;questions (the computational approaches needed to solve them are shown in parentheses):</p>

<ol><li>How Do We Locate Disease-Causing Mutations? (<em>Combinatorial Pattern Matching</em>)</li><li>Why Have Biologists Still Not Developed an HIV Vaccine?&nbsp;(<em>Hidden Markov Models</em>)</li>

</ol><p>As in previous courses, each of these two chapters is accompanied by a Bioinformatics Cartoon created by talented artist Randall Christopher and serving as a chapter header in the Specialization's bestselling <a href="BioinformaticsAlgorithms.github.io" target="_blank">print companion</a>. You can find the first chapter's cartoon at the bottom of this message. </p>

<p><img src="https://stepic.org/media/attachments/lessons/292/chapter7_cropped.jpg" title="Image: https://stepic.org/media/attachments/lessons/292/chapter7_cropped.jpg" width="528"></p>

The Burrows-Wheeler Transform
<p>Welcome to week 2 of the class!</p>

<p>This week, we will introduce a paradigm called the Burrows-Wheeler transform; after seeing how it can be used in string compression, we will demonstrate that it is also the foundation of modern read-mapping algorithms.</p>

Speeding Up Burrows-Wheeler Read Mapping
<p>Welcome to week 3 of class!</p>

<p>Last week, we saw how the Burrows-Wheeler transform could be applied to multiple pattern matching. This week, we will speed up our algorithm and generalize it to the case that patterns have errors, which models the biological problem of mapping reads with errors to a reference genome.</p>

Introduction to Hidden Markov Models
<p>Welcome to week 4 of class!</p>

<p>This week, we will start examining the case of aligning sequences with many mutations -- such as related genes from different HIV strains -- and see that our problem formulation for sequence alignment is not adequate for highly diverged sequences.</p> <p>To improve our algorithms, we will introduce a machine-learning paradigm called a hidden Markov model and see how dynamic programming helps us answer questions about these models.</p>

Profile HMMs for Sequence Alignment
<p>Welcome to week 5 of class!</p>

<p>Last week, we introduced hidden Markov models. This week, we will see how hidden Markov models can be applied to sequence alignment with a profile HMM. We will then consider some advanced topics in this area, which are related to advanced methods that we considered in a previous course for clustering.</p>

Bioinformatics Application Challenge
<p>Welcome to the sixth and final week of class!</p>

<p>This week brings our Application Challenge, in which we apply the HMM sequence alignment algorithms that we have developed.</p>
