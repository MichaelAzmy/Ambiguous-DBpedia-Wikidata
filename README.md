# ambiguous-dbwd
- Dataset for ambiguous entity mapping across DBpedia and Wikidata.
- Each query has a list of candidates such that all the candidates have the exact label of the query.

## Dataset Format
- There are two datasets:
  - dbpedia_to_wikidata: 
    - the query is a DBpedia URI and the candidates are Wikidata URIs.
  - wikidata_to_dbpeida: 
    - the query is a Wikidata URI and the candidates are DBpedia URIs.
    
 # Citation
 - If you used the dataset, please cite our work:
 
 ```@article{azmy2019matching,
  title={Matching Entities Across Different Knowledge Graphs with Graph Embeddings},
  author={Azmy, Michael and Shi, Peng and Lin, Jimmy and Ilyas, Ihab F},
  journal={arXiv preprint arXiv:1903.06607},
  year={2019}
}
```
