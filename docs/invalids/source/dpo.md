# dpo

This document details the invalid local unique identifiers used in CURIEs
for node, synonym, and definition cross-references in `dpo`. See the [GitHub repository](https://github.com/FlyBase/drosophila-phenotype-ontology).


## `Reactome`: Reactome

Overall, there were 1 invalid
xrefs to external prefixed with `Reactome` (standardized to Bioregistry
prefix [`reactome`](https://bioregistry.io/reactome)) that
did not match the standard pattern `^R-[A-Z]{3}-\d+(-\d+)?(\.\d+)?$`.

| external_xref    |   usages_count | usages                                                      |
|------------------|----------------|-------------------------------------------------------------|
| `Reactome:69278` |              1 | [FBcv:0000432](http://purl.obolibrary.org/obo/FBcv_0000432) |

## `WB_REF`: Wormbase Gene ID

Overall, there were 1 invalid
xrefs to external prefixed with `WB_REF` (standardized to Bioregistry
prefix [`wormbase`](https://bioregistry.io/wormbase)) that
did not match the standard pattern `^WB[A-Z][a-z]+\d+$`.

| external_xref   |   usages_count | usages                                                      |
|-----------------|----------------|-------------------------------------------------------------|
| `WB_REF:cgc467` |              1 | [FBcv:0000002](http://purl.obolibrary.org/obo/FBcv_0000002) |

