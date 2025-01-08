# Applied NER inference on linkedcat data for PFP

In the context of the intavia project, spaCy NER models were trained. These are reused here for the
PFP project, and applied on linkedcat data.

## how to reproduce

requirements:
- git
- docker compose

run with
```
docker compose -f veld_infer.yaml up
```

This will launch a jupyter notebook at http://localhost:8888/ where the inference can be executed.

