---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /ICML26/
title: LM4Plan @ ICML 2026 
layout: home
---
ICML’26 Workshop,  
Seoul, South Korea,  
Date: July 10 or 11, 2026  

### Overview
Language Models (LMs) are a disruptive force, changing how research was done in many subareas of AI. Planning is one
of the last bastions that remain standing. The focus of this workshop is on the questions in the intersection of these areas. Some of the specific areas we would like to gain a better understanding in include: what LMs can contribute to planning, how LMs can/should be used, what are the pitfalls of using LMs, what are the guarantees that can be obtained.


### Topics of Interest
We invite paper submissions on the following (not exhaustive) list of topics:

* Planning directly with pre-trained or fine-tuned LMs.
* Planning for LMs.
* LMs for (partial) model elicitation.
* LMs for generating structured planning problem descriptions.
* LMs for search guidance or search pruning.
* LMs for validation and verification of plans, policies, or models.
* LMs for generalization in planning and generalized planning.
* Using LMs as a proxy for user preferences.
* Using LMs to develop interfaces for planning-based systems or planning-related problems.
* Other applications of LMs in planning.



### Important Dates
<!-- Paper submission deadline: **April 24th, 2026, AoE**   -->

<p>Paper submission deadline: April 24th, 2026 at 23:59 Anywhere on Earth: <span id="countdown"></span></p>

<script>
  // Set the date we're counting down to
  var countDownDate = new Date("April 25, 2026 11:59:59 UTC").getTime();

  // Update the count down every 1 second
  var x = setInterval(function() {

    // Get today's date and time
    var now = new Date().getTime();

    // Find the distance between now and the count down date
    var distance = countDownDate - now;

    // Time calculations for days, hours, minutes and seconds
    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);

    // Display the result in the element with id="countdown"
    var countdown = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

    // If the countdown is finished, write some text 
    if (distance < 0) {
      clearInterval(x);
      countdown = "";  // optional message if countdown expired
    }

    document.getElementById("countdown").innerHTML = countdown

  }, 1000);
</script>

Paper acceptance notification: **May 15th, 2026, AoE**


### Submission Details
Paper submissions should be made through [OpenReview](https://openreview.net/group?id=ICML.cc/2026/Workshop/LM4Plan).

**Format**<br>
All submissions must be a single PDF file and follow one of the formats below:

**Long papers** – up to 8 pages + unlimited references / appendices  
**Short papers** – up to 4 pages + unlimited references / appendices  

Please format submissions in ICML style (see instructions in the [Author Kit](https://media.icml.cc/Conferences/ICML2026/Styles/icml2026.zip) ). 

**Dual-submission and non-archival policy**<br>
Authors submitting papers rejected from other conferences, please ensure you do your utmost to address the comments given by the reviewers. The workshop is a non-archival venue and will not have official proceedings. Workshop submissions can be subsequently or concurrently submitted to other venues.

**Double-blind Reviewing policy**<br>
All submissions must be anonymized and may not contain any identifying information that may violate the double-blind reviewing policy. Submissions and reviews will not be public. Only accepted papers will be made public.

**Reciprocal reviewing**<br>
Depending on the number of submissions, we may adopt a reciprocal reviewing process. For each submission, one reciprocal reviewer needs to be nominated who agrees to serve as a reviewer if reciprocal reviewing is implemented. Each nominated reviewer must have at least one relevant publication at a top venue and cannot be nominated as a reviewer for more than one submission. 


### Program Committee
To be announced.

### Organizing Committee
 * Michael Katz, IBM 
 <!-- [contact](mailto:michael.katz1@ibm.com)  -->
 * Augusto B. Corrêa, University of Oxford 
 <!-- [contact](mailto:augusto.blaascorrea@chch.ox.ac.uk) -->
 * Nir Lipovetzky, University of Melbourne
 * Sarath Sreedharan, Colorado State University
 * Katharina Stein, Saarland University
 * Luckeciano C. Melo, University of Oxford
 * Elliot Gestrin, Linköping University


Please send your inquiries to [llmforplanning@gmail.com](mailto:llmforplanning@gmail.com)
