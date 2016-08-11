---
layout: post
title: What's Jekyll?
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

[Jekyll](http://jekyllrb.com) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes. From [the project's readme](https://github.com/mojombo/jekyll/blob/master/README.markdown)

La tarification en assurance non-vie consiste à concevoir une prime payée par l'assuré à l'assureur en échange d'un transfert du risque. La prime dépendant du risque, cela consiste ainsi à segmenter les différents contrats en sous-portefeuilles de risques homogènes. Ces classes et la tarification sont dites \textit{a priori} si elles sont constituées à partir d'information sur l'assuré ou le bien assuré disponibles \textit{a priori}\footnote{La tarification \textit{a posteriori} ne sera pas développée dans ce mémoire}. L'approche usuelle s'intéresse à la \textbf{prime pure}\footnote{La prime pure n'est pas la prime opréationnellement payée par l'assuré. Un chargement commercial qui dépasse les enjeux de ce mémoire est effectivement ajouté à la prime pure} comme produit de l'espérance du nombre de sinistres et de leur coût moyen. La prime pure majorée d'un chargement commerciale (dont la constitution dépassent le cadre de ce mémoire) constituera alors la prime finale payé par l'assuré. \\

Dans le modèle collectif, la sinistralité totale s'exprime de la façon suivante à l'aide de :
\begin{itemize}
    \item $S$: variable aléatoire du montant total des sinistres d'un risque au
cours d'une période \footnote{habituellement et dans la suite de ce mémoire : 1 an}
\item $N$: variable aléatoire du nombre de sinistres\footnote{$N$ porte aussi le nom de variable aléatoire de fréquence ou variable aléatoire de comptage}
\end{itemize}

$$
S = \sum\limits_{k=1}^N X_k
$$

Ainsi la prime pure se définit comme l'espérance de $S$ soit : 

$$
\mathbb{E}[S] = \mathbb{E}[\sum\limits_{k=1}^N X_] = \mathbb{E}[N] \mathbb{E}[X]
$$

La prime pure permet ainsi une modélisation distincte de la fréquence des sinistres et de leur coûts. Il est effectivement intuitif ne ne pas considérer que les facteurs explicatifs de ces deux quantités ne soient pas les mêmes. De plus, comme présenté dans la vie d'un sinistre, l'assureur connaît plus facilement la fréquence des sinistres (la donnée est disponible dès la déclaration) que son coût (connu au terme du développement final du sinistre)

It's an immensely useful tool and one we encourage you to use here with Lanyon.

Find out more by [visiting the project on GitHub](https://github.com/mojombo/jekyll).
