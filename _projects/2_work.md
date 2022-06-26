---
layout: page
title: Voice of Customer
description: A case study aimed to analyze Amazon reviews on HasBro's products to provide existing feature updates and new product development opportunities using NLP
enable_hyperlink: true
img: assets/img/hasbro.png
importance: 2
category: work
github: https://github.com/zejiachen9912/VoiceofCustomer_HasBro

toc:
  - name: Problem Statement
  - name: Sentimental Analysis x Data Visualization
  - name: Result
---

### Problem Statement

This case's client is HasBro, a multinational conglomerate specializing in toys, board games, and media.

HasBro came to us asking a throughout analysis on the product reviews on *Amazon.com* to better help them to understand

  1. The reception of their various product lines (the quality, welcoming features, areas of improvements).
  2. New product opportunities to distinguish themselves from the diluted market.
  3. Competitor scenes and possible counterfeiting activities

---

### Sentimental Analysis x Data Visualization

To address the client's concerns,

we first conducted a sentimental analysis in python with respect to the customer review to extract the most extreme positive & negative reviews. (since they are most helpful for us to identify either the amazing product feature or pain point)

Base on what we already have, we then leverage some simple NLP techniques to rank the most frequently mentioned positive and negative product and keywords, and convert them into a wordclouds, demonstrating our findings visually to the senior level executives.

<div class="l-body">
  <div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hasbro_wc_neg.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hasbro_wc_pos.png" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>
  <div class="caption">
    The wordcloud generated from the negative and positive customer reviews we classified
  </div>
</div>

---

### [Result](https://docs.google.com/presentation/d/1P5PQzklI_NeJ5NtbrmkoEzlSuS6v3bqJuACRQhDoiro/edit?usp=sharing)

In our analysis of the negative reviews:

  - We identifies toys that have seen as hazardous by the customers, helping our clients to stop these defective items from hurting the royal customers.
  - We also pointed out a series of possible counterfeit products sold on Amazon that are currently hurting our client’s brand image.

Apropos of the positive side of customer reviews:

- We gave out a series of recommendation about the new product development, based on the most well-received toy’s features that were recognized in our textual analysis.
