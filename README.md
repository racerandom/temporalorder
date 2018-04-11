# tempora order

Temporal order (TORDER) is a new proposal of encoding temporal information in news articles or other text domains with rich time expressions inside. There are several advantages of TORDER:
* annotation effort is linear with the number of mention (event, time expression and DCT).
* TODER can produce more flexible relation types based on you definition.
* label distribution is more balanced.

More detailed information, please refer to the paper "Inducing Temporal Relations from Time Anchor Annotation" in NAACL-HLT 2018

We released the temporal order relations of the exact same mention pairs in Timebank-Dense corpus, which are the complete graph of relations in adjacent sentences. Theoretically, based on our method, you can generate any relations with longer sentence distance in a text by yourself.

Some related temporal resources are listed:
* Timebank-Dense https://www.usna.edu/Users/cs/nchamber/caevo/#corpus
* Time anchor of events https://www.ukp.tu-darmstadt.de/data/timeline-generation/temporal-anchoring-of-events/
