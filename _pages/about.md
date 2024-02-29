---
layout: about
title: about
permalink: /
subtitle: PhD student at <a href='https://www.univ-rennes1.fr/en'>Rennes 1 University</a>, CNRS, IRISA within <a href ='https://www-spicy.irisa.fr/'>SPICY team</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  address: >
    <p>Building 12</p>
    <p>Office F412</p>
    <p>IRISA, Rennes (France)</p>

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

My PhD started in October 2022 under the supervision of [Pierre-Alain Fouque](https://www.di.ens.fr/~fouque/) and [Mohamed Sabt](https://people.irisa.fr/Mohamed.Sabt/).

My thesis is focusing on static analysis of cryptographic code in order to detect a subclass of vulnerabilities, appearing whenever a cryptographic code does not respect constant time programming principles.
A single violation of those principles make the code vulnerable to side-channel attack. 

I am currently working on a out-of-tree plugin within [GCC's Static Analyzer](https://gcc.gnu.org/onlinedocs/gcc/Static-Analyzer-Options.html#index-fanalyzer) to detect those kind of vulnerabilities.
Source code is available [here](https://gitlab.inria.fr/pphilipp/gcc-plugin-ct).