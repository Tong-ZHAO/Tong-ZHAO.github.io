---
title: "Regularisation de formes 3D par dilation/erosion"
collection: teaching
type: "MAM4 Project"
permalink: /teaching/2020-winter-project
venue: "POLYTECH Nice-Sophia"
date: 2020-12-10
location: "France"
---

L’objectif de ce projet consiste à concevoir un algorithme d’évaluation d’une fonction implicite du double offset, à partir d’un maillage surfacique triangulaire. 

Plus précisément, on cherche à évaluer efficacement une fonction de R3 dans R permettant d’évaluer, en tous points de l’espace, la fonction distance signée à la surface du double offset. Le premier offset (positif) est simple à évaluer avec les structures accélératrices de la bibliothèque CGAL (http:// www.cgal.org). Le second offset, quant à lui, requiert de concevoir une discrétisation à l’aide de quadratures adaptatives, et de recourir à une interpolation numérique. On cherchera à concevoir une méthode frugale en mémoire et une mise en oeuvre en C++ comme un "oracle" implicite de l’algorithme de maillage 3D de CGAL. 

## Data

* [Box](../../../../assets/data/box.xy)
* [Stacked Box](../../../../assets/data/stacked_box.xy)