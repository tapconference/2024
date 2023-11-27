---
layout: page
title: Submission
permalink: /submission.html
---

TAP 2024 accepts papers of two kinds:

**Regular papers:** full submissions describing

- original research results,
- tools, and
- case studies

of up to 16 pages. For tools and case studies, the tool, framework, or
case study described in a tool paper should be available for public use.

**Short papers:** submissions describing preliminary findings, proofs of
concepts, and exploratory studies, of up to 6 pages.

All page limits exclude the references. Appendices may be included,
but they will only be read by a reviewer at their discretion.

Regular and short papers must be original, unpublished, and not submitted
for publication elsewhere.
Papers
have to adhere to Springer’s LNCS format and must be submitted in PDF
format at the EasyChair submission site:

- [https://easychair.org/my/conference?conf=tap24](https://easychair.org/my/conference?conf=tap24)

### Review Process

Papers will undergo a thorough review process. The review process is
single blind. Submissions will be judged on the basis of significance,
relevance, correctness, originality, and clarity. The submissions will
be reviewed and selected for publication based on the above-mentioned
criteria as well as suitability to the conference’s technical program.

### Proceedings

Accepted submissions will be published in Springer’s LNCS series. 

<p align="center"><img src="/2024/assets/images/LNCS-Logo.jpeg" width="200"/></p>

### Artifact Evaluation

After notification, all artifacts of accepted papers will be reviewed
with respect to their availability, consistency with and replicability
of results in the paper, completeness, documentation, and ease of use.
Papers accompanied by a companion artifact should clearly indicate the 
DOI link to the publicly available artifact in the paper. 
The papers with publicly *available* artifacts will receive 
corresponding [EAPLS badges](https://eapls.org/pages/artifact_badges/).

We suggest authors follow [TACAS 2024 instructions for Artifact submission](https://tacas.info/artifacts-24.php) (expected to be usable with the TACAS 2023 VM).
The instructions explain where to publish, in which form and what is expected 
to be provided and documented. Additionally:

- In case the VM requires Internet access for installation of your tool dependencies, 
  an unattended upgrade can be launched by the  system at any moment, 
  take a lock and block the normal artifact installation process. 
  It is hard to foresee all such situations because it can happen 
  at any moment. We recommend to deactivate unattended upgrades by typing in 
  a terminal:

  ```
  $ sudo dpkg-reconfigure unattended-upgrades
  ```

  and choosing NO. We recommend to mention this step as the first installation step 
  in the README of the artifact if you rely on Internet access to install dependencies
  of your tool (recall that  your tool itself should be included in the artifact and should not
  be downloaded by the VM via Internet).
- In case you submit your artifact on zenodo, please DO NOT choose a community:
  a request for community review and approval can strongly delay the publication. 

