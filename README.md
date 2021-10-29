# CPP_questionnaires

<!-- https://www.repronim.org/reproschema-ui/#/?url=url-to-your-protocol_schema
https://www.repronim.org/reproschema-ui/#/activities/0?url=url-to-activity-schema -->

Protocol: (does not work yet)
https://www.repronim.org/reproschema-ui/#/?url=https://raw.githubusercontent.com/cpp-lln-lab/CPP_questionnaires/main/protocols/questionaires.jsonld

Demographics:
https://www.repronim.org/reproschema-ui/#/activities/0?url=https://raw.githubusercontent.com/cpp-lln-lab/CPP_questionnaires/main/activities/demographics/demographics.jsonld

EHI-short:
https://www.repronim.org/reproschema-ui/#/activities/0?url=https://raw.githubusercontent.com/Remi-Gau/reproschema-library/EHI/activities/EHI/edinburgh_handedness_inventory_short

EHI:
https://www.repronim.org/reproschema-ui/#/activities/0?url=https://raw.githubusercontent.com/Remi-Gau/reproschema-library/EHI/activities/EHI/edinburgh_handedness_inventory

## Validation

```
python -m pip install --upgrade pip setuptools
pip install reproschema requests_cache
reproschema -l DEBUG validate activities
reproschema -l DEBUG validate protocols
```

## TODO

Weight:

Contact number:

Date of experiment:

Signature of participant with date:
