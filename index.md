---
layout: default
title: Home
has_children: true
nav_order: 1
description: "Homepage of the Decameron Web"
permalink: /
---

# Decameron Web

---

## Texts

### Decameron

- The Italian text of the *Decameron* is based on V. Branca's Einaudi edition (1992).
- The English translation of the *Decameron* (J. M. Rigg, 1903), while somewhat dated in its language and style, has a highly literal approach to translation which gives readers a reliable crib for exploring the original Italian text and is easily readable on its own. Read English translation

## This is a sample XML page
<script src="/_includes/CETEI.js"></script>
<script>
      var CETEIcean = new CETEI();
      CETEIcean.getHTML5('/files/italian/itDay01Intro.xml', function(data) {
        document.getElementById("TEI").innerHTML = "";
        document.getElementById("TEI").appendChild(data);
        CETEIcean.addStyle(document, data);
      });</script>
      
  <div id="TEI"></div>
  
  That should have worked.
