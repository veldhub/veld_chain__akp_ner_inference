# ![veld chain](https://raw.githubusercontent.com/veldhub/.github/refs/heads/main/images/symbol_V_letter.png)
 veld_chain__akp_ner_inference

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

Clone this repo with all its submodules (important as they may contain necessary data and code)
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__akp_ner_inference.git
```

## how to reproduce

The following chain velds were used. Open the respective veld yaml file for more information.

**[./veld_infer.yaml](./veld_infer.yaml)** 

This will launch a jupyter notebook at http://localhost:8888/ where the inference can be executed.

```
docker compose -f veld_infer.yaml up
```

