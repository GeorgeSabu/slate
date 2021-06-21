---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - python

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true
---

# Polly API's

This is the collection of API/library functions that is available for Polly account holder to interact with the Polly offerings. Polly API has the ability to interact with
1. Omixatlas
2. Workspaces

More API will get added to this soon. Happy Coding


# Authentication

Authentication of Polly API is taken care by a token that is give to the user from the user interface. This token can be got from the below interface. This token will get expired in 30 days. ![Drag Racing](https://elucidatainc.github.io/PublicAssets/documentation-images/token_screen.png)




# Omixatlas

Every year, vast amounts of biological multi-omics data are being generated and deposited on public repositories by academic labs and organizations worldwide. These data hold tremendous potential for reuse and discovery but are scattered across multiple, disparate sources and lack standardization. Thus, the availability of data does not equate to its easy usability. This makes the need for an efficient means of exploring molecular data an immediate necessity. 
Additionally, no single type of data, be it metabolomic, proteomic or genomic, will be sufficient to capture the complexity of biological phenomena. Adopting an integrated approach could significantly aid the ability to gain a more 
holistic and accurate understanding of human physiology and disease pathology at the molecular level. 
OmixAtlas aims to address these issues by providing access to ML-ready biology-centric data from public repositories.


## get_all_omixatlas

```python
import requests


requests.get("https://v2.api.polly.elucidata.io/v1/omixatlases")

```

```shell
curl "https://v2.api.polly.elucidata.io/v1/omixatlases"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:





### HTTP Request

`GET https://v2.api.polly.elucidata.io/v1/omixatlases`





## get_omixatlas_details

```python
import requests


requests.get("https://v2.api.polly.elucidata.io/v1/omixatlases/")

```

```shell
curl "https://v2.api.polly.elucidata.io/v1/omixatlases/"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:





### HTTP Request

`GET https://v2.api.polly.elucidata.io/v1/omixatlases/`





## query_with_sql

```python
import requests


requests.post("https://v2.api.polly.elucidata.io/v1/omixatlases/_query")

```

```shell
curl "https://v2.api.polly.elucidata.io/v1/omixatlases/_query"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:





### HTTP Request

`POST https://v2.api.polly.elucidata.io/v1/omixatlases/_query`





## query_with_elasticsearch

```python
import requests


requests.post("https://v2.api.polly.elucidata.io/v1/omixatlases/_search")

```

```shell
curl "https://v2.api.polly.elucidata.io/v1/omixatlases/_search"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:





### HTTP Request

`POST https://v2.api.polly.elucidata.io/v1/omixatlases/_search`





## get_dataset_signed_url

```python
import requests


requests.get("https://v2.api.polly.elucidata.io/v1/omixatlases/repo.name/download/")

```

```shell
curl "https://v2.api.polly.elucidata.io/v1/omixatlases/repo.name/download/"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:





### HTTP Request

`GET https://v2.api.polly.elucidata.io/v1/omixatlases/repo.name/download/`


