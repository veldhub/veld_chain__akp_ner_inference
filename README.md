# veld_chain__akp_ner_inference

This repo contains [chain velds](https://zenodo.org/records/13322913) encapsulating NER inference
chains.

In the context of the [intavia project](https://intavia.eu/), spaCy NER models were trained. These
are reused here for the
[PFP project](https://www.oeaw.ac.at/acdh/research/dh-research-infrastructure/activities/modelling-humanities-data/pfp-prosopographical-research-platform-austria) 
, and applied on linkedcat data.

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

## how to reproduce

**[./veld_infer.yaml](./veld_infer.yaml)** 

This will launch a jupyter notebook at http://localhost:8888/ where the inference can be executed.

```
docker compose -f veld_infer.yaml up
```

