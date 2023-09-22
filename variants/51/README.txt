This variant of the collection was pretty much only used in this paper:
    https://dl.acm.org/doi/pdf/10.1145/3209978.3210020

I was still using elasticsearch at the time, but only 51 of the 94 queries were able to be automatically converted into elasticsearch queries. It turns out that there are major differences between medline/pubmed and elasticsearch queries, so much so that elasticsearch can't support them all with the query language it has (at least at the time I did these experiments).