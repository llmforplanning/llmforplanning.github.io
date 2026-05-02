---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /ICML26/
title: LM4Plan @ ICML 2026 
layout: home
---
ICML’26 Workshop,  
Seoul, South Korea,  
Date: July 10, 2026

### Invited Speakers
We are excited to announce our invited speakers for LM4Plan @ ICML 2026. [View full speaker details](/icml_speakers/).

* **Samy Bengio** - Apple
* **Subbarao Kambhampati** - Arizona State University
* **Yarin Gal** - University of Oxford
* **Elias Bareinboim** - Columbia University
* **Noam Brown** - OpenAI

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


### ​Rejected ICML Submissions Track
We would like to offer authors of relevant submissions rejected from the main ICML 2026 track the opportunity to submit their papers to our workshop.

Submission Instructions
In addition to the regular submission requirements described below, authors must include a single PDF containing both:

1. the ICML 2026 reviews and rebuttal materials, as well as  
2. a short cover letter of no more than one page in which they may provide a final response to those reviews and describe the changes made to the paper.  

Because relevance is a primary criterion for this track, we reserve the right to desk reject, without review, submissions that fall outside the topics of interest listed below.


### Important Dates
<!-- Paper submission deadline: **April 24th, 2026, AoE**   -->

<!-- <p>Paper submission deadline: April 24th, 2026 at 23:59 Anywhere on Earth: <span id="countdown1"></span></p>
<p>Paper acceptance notification: May 15th, 2026 at 23:59 Anywhere on Earth: <span id="countdown2"></span></p> -->

<p>Paper submission deadline: April 24th, 2026 at 23:59 Anywhere on Earth:
<div class="countdown" id="countdown1"></div>
</p>

<p>Rejected ICML Submissions Track Paper submission deadline: May 6th, 2026 at 23:59 Anywhere on Earth:
<div class="countdown" id="countdown3"></div>
</p>

<p>Paper acceptance notification: May 22nd, 2026 at 23:59 Anywhere on Earth:
<div class="countdown" id="countdown2"></div>
</p>

<script>
function aoeDeadline(year, month, day, hour=23, min=59, sec=59) {
  return Date.UTC(year, month - 1, day, hour + 12, min, sec);
}

function startCountdown(elementId, targetDateUTC) {
  function pad(n) {
    return n.toString().padStart(2, '0');
  }

  var el = document.getElementById(elementId);

  var x = setInterval(function() {
    var now = Date.now();
    var distance = targetDateUTC - now;

    if (distance < 0) {
      clearInterval(x);
      el.innerHTML = "";
      return;
    }

    var totalSeconds = Math.floor(distance / 1000);

    var weeks = Math.floor(totalSeconds / (7 * 24 * 3600));
    var days = Math.floor((totalSeconds % (7 * 24 * 3600)) / (24 * 3600));
    var hours = Math.floor((totalSeconds % (24 * 3600)) / 3600);
    var minutes = Math.floor((totalSeconds % 3600) / 60);
    var seconds = totalSeconds % 60;

    el.innerHTML = `
    <div style="display:flex; gap:10px; font-family:sans-serif;">
        ${box(pad(weeks), "weeks")}
        ${box(pad(days), "days")}
        ${box(pad(hours), "hours")}
        ${box(pad(minutes), "minutes")}
        ${box(pad(seconds), "seconds")}
    </div>
    `;

    function box(value, label) {
    return `
        <div style="background:#f3f3f3; border-radius:6px; padding:10px 12px; text-align:center; min-width:60px;">
        <div style="font-size:20px; font-weight:bold;">${value}</div>
        <div style="font-size:11px; color:#666; margin-top:4px;">${label}</div>
        </div>
    `;
    }

  }, 1000);
}

startCountdown("countdown1", aoeDeadline(2026, 4, 24));
startCountdown("countdown2", aoeDeadline(2026, 5, 22));
startCountdown("countdown3", aoeDeadline(2026, 5, 6));
</script>

<!-- Paper acceptance notification: **May 15th, 2026, AoE** -->


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
