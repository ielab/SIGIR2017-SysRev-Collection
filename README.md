# SIGIR2017 PICO Query Collection

This repository contains the collection of queries for the paper "A Test Collection for Evaluating Retrieval of Studies for Inclusion in Systematic Reviews".

The following files have been made available:

 - `systematic_reviews.json`: A list of urls pointing to the systematic reviews used in this collection.
 - `citations.json`: A list of citations that correspond to the systematic reviews. The `document_id` refers to the `id` in `systematic_reviews.json`. The `included` field is true if the study was included in the review.
 - `queries_unannotated.json`: A list of queries as they appear in their respective systematic reviews. The `document_id` refers to the `id` in `systematic_reviews.json`. The `annotator_id` refers to who collected the query.
 - `queries_annotated.json`: A list of queries that have been manually transformed. The `document_id` refers to the `id` in `systematic_reviews.json`. The `annotator_id` refers to who annotated the query with PICO.
 - `queries_elastic_bool.json` and `queries_elastic_pico.json`: Both files are lists of Elasticsearch queries in the same format as `queries_annotated.json`.

If you use this collection in your own work, please cite it as:

```
@inproceedings{scells2017collection,
	Author = {Scells, Harrisen and Zuccon, Guido and Koopman, Bevan and Deacon, Anthony and Geva, Shlomo and Azzopardi, Leif},
	Booktitle = {Proceedings of the 40th international ACM SIGIR conference on Research and development in Information Retrieval},
	Organization = {ACM},
	Title = {A Test Collection for Evaluating Retrieval of Studies for Inclusion in Systematic Reviews},
	Year = {2017}
}
```