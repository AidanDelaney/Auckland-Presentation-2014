title:
class: big
image: images/tardis.jpg

---

title: 
class: big
image: images/telefon.png

---

title: Historical
class: big
image: images/SchoolOfAthens.jpg
content_class: flexbox vcenter

---

title: Euclid's Diagrammatic Proof
subtitle:
class: big
image: images/euclid.jpg

---

title: Leonhard Euler
subtitle:
class: big
image: images/Torgau.jpg

---

title: John Venn
subtitle:
class: big
image: images/Everett-Millais.jpg

---

title: Gottlob Frege
image: images/vanGogh.jpg

---

title: C.S. Peirce
image: images/Klimt.jpg

---

title:
image: images/vanderLeck.jpg
class: big
build_lists: true

- G&ouml;del
- Zermelo, Fraenkel, Skolem, Tarski
- Turing

---

title: Sun-Joo Shin
image: images/Bacon.jpg

---

title: Modern Developments
image: images/Banksy.jpg
class: big

- Brighton
    * Stuart Kent
    * John Howse
    * Gem Stapleton
- Kent
    * Yossi Gil
    * Simon Thompson
    * Peter Rodgers

---

title: Recap
class: segue dark nobackground

---

title: Euler Diagrams
content_class: flexbox vcenter big

Visualise the relationship between sets.

![Euler diagrams](images/euler-eg-pg122.png)

---

title: Venn Diagrams
content_class: flexbox vcenter big

<blockquote style="font-size:16pt;">
The [diagrammatic scheme] here offered may be said to underlie Boole's method, and to be the appropriate diagrammatic representation for it.
</blockquote>

![A Venn diagram](images/syllogism-mortals-venn-diagram.svg)

---

title: Modern Euler Diagrams
content_class: flexbox vcenter

![An Euler diagram](images/syllogism-mortals-euler-box-diagram.svg)

---

title: Properties of Euler Diagrams
class: big

- WISWYG
    * 1-to-1 mapping between contous and the sets that they represent.
- Free Rides (Shimojima, 1999)
    * Philosophers are not Mortal!

    <footer class="source">Atsushi Shimojima, Derivative Meaning in Graphical Representations, IEEE VL, 1999.</footer>
---

title: Syllogistic Reasoning using Euler Diagrams
class: big

- The major premise ``No mortals are philosophers'' is represented by the contour denoting ``Mortals'' being disjoint from the contour denoting ``Philosophers''.
- The minor premise ``Every Athenian is mortal'' is represented by the containment of the contour denoting ``Athenians'' within the contour denoting ``Mortals''.
- The conclusion ``Therefore no philosopher is Athenian'' is clear due to the contours denoting ``Athenians'' and denoting ``Philosophers'' being disjoint.

---

title: Syllogistic Reasoning
class: big

- Diagrams can assist in Syllogistic reasoning (Sato et al, 2010).
- Are we reasoning using diagrams or sententially?

<footer class="source">Yuri Sato and Koji Mineshima and Ryo Takemura, The Efficacy of Euler and Venn Diagrams in Deductive Reasoning: Empirical Findings, Diagrams, 2010.</footer>

---

title: Spider Diagrams
content_class: flexbox vcenter

![Diagram from Blake's orientation experiment](images/Blake.svg)

<footer class="source">Andrew Blake, Gem Stapleton, Peter Rodgers, Liz Cheek, John Howse: Does the Orientation of an Euler Diagram Affect User Comprehension? DMS 2012</footer>

---

title: Rodgers (2014)
content_class: flexbox vcenter

![Diagram from Rodgers](images/supernationalbodies.png)

<footer class="source">Rodgers, P.: A survey of euler diagrams. Journal of Visual Languages and Computing 25, 134–155 (2014)</footer>

---

title: Riche & Dwyer (2010)
content_class: flexbox vcenter

![Diagram from Riche & Dwyer](images/RicheDwyer.png)

<footer class="source">Riche, N.H.; Dwyer, T., "Untangling Euler Diagrams," Visualization and Computer Graphics, IEEE Transactions on , vol.16, no.6, 2010</footer>

---

title: Large Euler Diagrams II
class: big

- Let \\(d\\) be a diagram displayed on a screen.  If \\(d\\) is unreadable, then we say that \\(d\\) is a _large_ diagram.
- This definition suffices as a working definition.
- It allows us to remain abastracted from a discussion on the size or quality of screens.

---

title: More motivation for large Euler Diagrams I
content_class: flexbox vcenter

![Howse's work on specification](images/PNCC_v3_1.jpg)

---

title: More motivation for large Euler Diagrams II
content_class: flexbox vcenter

![Howse's work on specification](images/RangitikeiCemetery2.svg)

---

title: Generating and Navigating Large Euler Diagrams
class: big

- We wish to generate diagrams that do not comfortably fit on a screen.
- Furthermore, we wish to navigate these diagrams to find information within them.
- At this point we could do with a theory of information seeking.

---

title: Information Seeking
class: segue dark nobackground

---

title: Shneiderman’s information seeking mantra
class: big

- overview first,
- zoom & filter, then
- details-on-demand.

We'll consider each of the above using a Chess program as an example.

<footer class="source">Shneiderman, B.: The eyes have it: a task by data type taxonomy for information visualizations. In: Visual Languages, 1996. Proceedings., IEEE Symposium on. pp. 336–343 (Sep 1996)</footer>

---

title: Overview first I
class: big
content_class: flexbox vcenter

![Chess board overview](images/overview.png)


---

title: Overview first II
class: big
content_class: flexbox vcenter

![Map overview](images/map-overview.png)

---

title: Zoom & Filter I
class: big
content_class: flexbox vcenter

![Chess board Zoom & Filter](images/zoomandfilter.png)

---

title: Zoom & Filter II
class: big
content_class: flexbox vcenter

![Map overview](images/map-zoom-and-filter.png)

---

title: Details-on-Demand I
class: big
content_class: flexbox vcenter

![Chess board Details-on-demand](images/details-on-demand.png)

---

title: Details-on-Demand II
class: big
content_class: flexbox vcenter

![Map overview](images/map-details-on-demand.png)

---

title: Generating Large Diagrams
class: segue dark nobackground

---

title: Manual Generation of Euler Diagrams
class: big
content_class: flexbox vcenter

![Howse's SSN diagram](images/SSNSolution.svg)

---

title: Activity
subtitle:
class: segue dark nobackground

---

title: A real world(ish) example
class: big
build_lists: false

Draw an Euler diagram describing the following facts:

- A _Social Object_ is not a _Physical Object_.
- A _Sensor_ is a _Physical Object_.
- An _Observation_ is a _Social Object_.
- A _Device_ is a _Physical Object_.
- A _Sensing Device_ is a _Device_ and is a _Sensor_.

---

title: Automatic Generation of Euler Diagrams
subtitle:
class: segue dark nobackground

---

title: List of Automatic Generation algorithms

<!-- Note here that I've ignored any Venn-diagram only tools, such as the [GNU R VennDiagram](http://cran.r-project.org/web/packages/VennDiagram/VennDiagram.pdf) package. -->

- [iCircles](www.eulerdiagrams.com/inductivecircles.html) -- As seen in [Speedith](https://github.com/urbas/speedith).
    *  G. Stapleton, J. Flower, P. Rodgers and J. Howse. [Automatically Drawing Euler Diagrams with Circles](http://www.cs.kent.ac.uk/pubs/2012/3211/index.html). Journal of Visual Languages and Computing, 23(3):163–193, 2012.
- [EulerAPE](http://www.eulerdiagrams.org/eulerAPE/) -- Also see EulerForce.
    * L. Micallef and P. Rodgers ["eulerAPE: Drawing Area-Proportional 3-Venn Diagrams Using Ellipses"](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0101717), 2014.
- [VennMaster](http://sysbio.uni-ulm.de/?Software:VennMaster)
    * H. Kestler, et al. ["Generalized Venn diagrams: a new method of visualizing complex genetic set relations."](http://bioinformatics.oxfordjournals.org/cgi/content/full/21/8/1592?view=long&pmid=15572472) Bioinformatics 21.8, 2005.
- [VennFS2](http://isis.dia.unisa.it/projects/vennfs/)
    * R. De Chiara, U. Erra and V. Scarano, ["VENNFS: A Venn-Diagram File Manager"](http://isis.dia.unisa.it/papers/vennfs.pdf) IV, 2003.
- [VennEuler](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=5728808)
    * L. Wilkinson ["Exact and Approximate Area-Proportional Circular Venn and Euler Diagrams"](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=5728808), IEEE Visualization and Computer Graphics, 2012.

---

title: iCircles
class: big

Demo time

---

title: Generating (almost) Arbitrarly Large Diagrams
class: big

- Our large diagrams are _sparse_.
- Diagrams are generated for the purpose of navigating.
- We use iCircles to generate small clusters.
- Then use WebCola to layout the clusters.
- (Note: the prototype is un-demoable).

---

title: A Large Diagram
content_class: flexbox vcenter

![A large diagram](images/clusters.svg)

---

title: Navigating Large Diagrams
class: segue dark nobackground

---

title: Anchoring the Diagram I
content_class: flexbox vcenter

![Grid](images/grid.svg)

---

title: Anchoring the Diagram II
content_class: flexbox vcenter

![Grid](images/grid-partial.svg)

---

title: Overview
content_class: flexbox vcenter

![Zoom & Filter](images/clusters-overview.svg)

---

title: Zoom & Filter
content_class: flexbox vcenter

![Zoom & Filter](images/clusters-filter.svg)

---

title: Details-on-Demand I
content_class: flexbox vcenter

![Zoom & Filter](images/details.svg)

---

title: Details-on-Demand II
content_class: flexbox vcenter

![Zoom & Filter](images/details-align.svg)

---

title: Future Work & Conclusion
class: segue dark nobackground

---
title: Future Work
class: big

- This is preliminary work and requires a good prototype implementation.
- We need large real-world datasets to layout (probably biological).
- Comparative studies with other visualisations for large Euler diagrams.

---

title: Conclusion
class: big

- We have used Shneiderman’s information visualisation framework to consider how to navigate large Euler diagrams.
- We'd like to think of other ways to navigate large Euler diagrams.
