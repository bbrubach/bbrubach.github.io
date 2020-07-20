---
layout: page
title: Research
permalink: /research/
---



Much of my research is captured by the following ongoing projects. 
On the theoretical computer science side, my focus is primarily on matching, clustering, and string algorithms with a special interest in stochastic problems. 
I consider these problems in the context of several application areas including e-commerce, fairness, accountability, and transparency in automated systems, mechanism design for social good, and bioinformatics.



<br>
<hr>
<br>



<h2>
Redistricting and gerrymandering 
</h2>

One of my newer projects is studying important problems surrounding political redistricting and gerrymandering. My work targets three broad areas:
<ol>
  <li>
    Developing measures to evaluate districts and detect gerrymandering (especially partisan gerrymandering) in ways that can inform legal standards.
  </li>
  <li>
    Evaluating the measures themselves (measuring the measures) and their longterm consequences (e.g., effects on voter incentives).
  </li>
  <li>
    Designing algorithmic solutions to generate "fairer" district maps with an eye toward fairness to individuals and communities rather than political parties.
  </li>
</ol>


<h3>Representative work</h3>
  <ul>


  <li>
  <strong>Meddling Metrics: the Effects of Measuring and Constraining Partisan Gerrymandering on Voter Incentives</strong>. with <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a> and Shawn Zhao. <i>ACM Conference on Economics and Computation</i> (EC), 2020. (<a href="/files/Paper-MeddingMetrics-EC20.pdf">conference version</a>)
  </li>

  <li>
  <strong>A Pairwise Fair and Community-preserving Approach to <i>k</i>-Center Clustering</strong>. with Darshan Chakrabarti, <a href="http://jpdickerson.com/">John P. Dickerson</a>, <a href="http://www.cs.umd.edu/users/samir/">Samir Khuller</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and Leonidas Tsepenekas. <i>International Conference on Machine Learning</i> (ICML), 2020. (<a href="/files/Paper-PairFair-ICML20.pdf">conference version</a>)
  </li>

  </ul>


<strong>Collaborators:</strong> Darshan Chakrabarti, <a href="http://jpdickerson.com/">John P. Dickerson</a>, <a href="http://www.cs.umd.edu/users/samir/">Samir Khuller</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and Shawn Zhao.




<!--<img src="../files/BrubachSquarePicture.jpeg" style="width: 200px">
-->




<br>
<hr>
<br>



<h2>
Online matching and e-commerce
</h2>

Online matching problem are ubiquitous in e-commerce. I study mostly stochastic variants of these problems that capture the uncertainty in the real world and making decisions based on predictions. Variants include random vertex arrival models and stochastic rewards (graph edges that only exist with some estimated probability).

<h3>Representative work</h3>
  <ul>
  
    <li>
    <strong>Vertex-weighted Online Stochastic Matching with Patience Constraints (working paper)</strong>. with Nathaniel Grammel and <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>. (<a href="https://arxiv.org/abs/1907.03963">arxiv version</a>)
    </li>

    <li>
    <b>Attenuate Locally, Win Globally: An Attenuation-based Framework for Online Stochastic Matching with Timeouts</b>. with <a href="http://karthikabinavs.xyz">Karthik A. Sankararaman</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and <a href="https://sites.google.com/site/panxupi/">Pan Xu</a>. <i>Algorithmica</i>, 2019
    </li>

    <li>
    <strong>New Algorithms, Better Bounds, and a Novel Model for Online Stochastic Matching</strong>. with <a href="http://karthikabinavs.xyz">Karthik A. Sankararaman</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and <a href="https://sites.google.com/site/panxupi/">Pan Xu</a>. <i>Proc. European Symposium on Algorithms</i> (ESA), 2016. (<a href="http://arxiv.org/abs/1606.06395">long version</a>) (<a href="http://www.cs.umd.edu/~bbrubach/ESA16-Matching-Slides.pdf">slides</a>)
    </li>

  </ul>


<strong>Collaborators:</strong> Nathaniel Grammel, <a href="http://karthikabinavs.xyz">Karthik A. Sankararaman</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and <a href="https://sites.google.com/site/panxupi/">Pan Xu</a>.


<br>
<hr>
<br>



<h2>
Sequence comparison and clustering in metagenomics/genomics
</h2>

I design and implement algorithms for metagenomics and genomics. My applied work has been in the area of 16S rRNA sequence clustering. On the theortical side, I am broadly interested in string algorithms for problems such as computing edit distance. I am also fascinated by measures of rearrangements between two strings and in particular, the Maximum Duo-preservation String Mapping (MPSM) problem.

<h3>Representative work</h3>
  <ul>

    <li>
    <strong>Better Greedy Sequence Clustering with Fast Banded Alignment</strong>. with <a href="http://www.cbcb.umd.edu/~jayg/">Jay Ghurye</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and <a href="http://www.cbcb.umd.edu/~mpop/">Mihai Pop</a>. <i>Proc. Algorithms in Bioinformatics - 17th International Workshop</i> (WABI), 2017. (<a href="http://drops.dagstuhl.de/opus/volltexte/2017/7642/pdf/LIPIcs-WABI-2017-3.pdf">conference version</a>)
    </li>

    <li>
    <strong>A Succinct Four Russians Speedup for Edit Distance Computation and One-against-many Banded Alignment</strong>. with <a href="http://www.cbcb.umd.edu/~jayg/">Jay Ghurye</a>. <i>Proc. 29th Annual Symposium on Combinatorial Pattern Matching</i> (CPM), 2018. (<a href="http://drops.dagstuhl.de/opus/volltexte/2018/8696/pdf/LIPIcs-CPM-2018-13.pdf">conference version</a>)
    </li>

    <li>
    <strong>Fast Matching-based Approximations for Maximum Duo-preservation String Mapping and its Weighted Variant</strong>. <i>Proc. 29th Annual Symposium on Combinatorial Pattern Matching</i> (CPM), 2018. (<a href="http://drops.dagstuhl.de/opus/volltexte/2018/8706/pdf/LIPIcs-CPM-2018-5.pdf">conference version</a>)
    </li>

    <li>
    <strong>Further Improvement in Approximating the Maximum Duo-Preservation String Mapping Problem</strong>. <i>Proc. Algorithms in Bioinformatics - 16th International Workshop</i> (WABI), 2016. (<a href="http://www.cs.umd.edu/~bbrubach/WABI16-MPSM-Slides.pdf">slides</a>)
    </li>
    
  </ul>


<strong>Collaborators:</strong> <a href="http://www.cbcb.umd.edu/~jayg/">Jay Ghurye</a>, Tu Luan, <a href="http://www.cbcb.umd.edu/~mpop/">Mihai Pop</a>, and <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>.


<br>
<hr>
<br>



<h2>
Clustering
</h2>

A lot of my work, including applications to redistricting and bioinformatics as well as approximation algorithms, falls under the broad category of clustering. I am especially interested in various definitions of fairness in clustering and stochastic problems. Much of my focus has been on the <i>k</i>-center problem and related radius-based approaches.

<h3>Representative work</h3>
  <ul>

    <li>
    <strong>The Hard, the Soft, and the Probabilistic: Metric Clustering with Pairwise Constraints (working paper)</strong>. with <a href="http://jpdickerson.com/">John P. Dickerson</a>, <a href="http://www.cs.umd.edu/users/samir/">Samir Khuller</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and Leonidas Tsepenekas. (<em>under review</em>) (<a href="">arxiv version coming soon</a>)
    </li>
  <li>
  <strong>A Pairwise Fair and Community-preserving Approach to <i>k</i>-Center Clustering</strong>. with Darshan Chakrabarti, <a href="http://jpdickerson.com/">John P. Dickerson</a>, <a href="http://www.cs.umd.edu/users/samir/">Samir Khuller</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and Leonidas Tsepenekas. <i>International Conference on Machine Learning</i> (ICML), 2020. (<a href="/files/Paper-PairFair-ICML20.pdf">conference version</a>)
  </li>
    <li>
    <strong>Better Greedy Sequence Clustering with Fast Banded Alignment</strong>. with <a href="http://www.cbcb.umd.edu/~jayg/">Jay Ghurye</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and <a href="http://www.cbcb.umd.edu/~mpop/">Mihai Pop</a>. <i>Proc. Algorithms in Bioinformatics - 17th International Workshop</i> (WABI), 2017. (<a href="http://drops.dagstuhl.de/opus/volltexte/2017/7642/pdf/LIPIcs-WABI-2017-3.pdf">conference version</a>)
    </li>
    <li>
    <strong>Probabilistic Fair Clustering</strong>. with Seyed A. Esmaeili, Leonidas Tsepenekas, and <a href="http://jpdickerson.com/">John P. Dickerson</a>. (<em>under review</em>) (<a href="https://arxiv.org/abs/2006.10916">arxiv version</a>)
    </li>


  </ul>

<strong>Collaborators:</strong> Darshan Chakrabarti, <a href="http://jpdickerson.com/">John P. Dickerson</a>, Seyed A. Esmaeili, <a href="http://www.cbcb.umd.edu/~jayg/">Jay Ghurye</a>, Nathaniel Grammel, <a href="http://www.cs.umd.edu/users/samir/">Samir Khuller</a>, Tu Luan, <a href="http://www.cbcb.umd.edu/~mpop/">Mihai Pop</a>, and <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>.



<br>
<hr>
<br>



<h2>
Bias Feedback
</h2>

In this recently started project, we are using AI to give humans feedback on their implicit biases.

<strong>Collaborators:</strong> <a href="http://jpdickerson.com/">John P. Dickerson</a>, <a href="http://www.cs.umd.edu/~srin/">Aravind Srinivasan</a>, and Shawn Zhao.