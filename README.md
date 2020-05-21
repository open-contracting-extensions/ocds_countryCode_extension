# Country code

Adds a countryCode property in Address.

## Guidance

## Legal context

In the European Union, this extension's fields correspond to [eForms BT-514 (Organisation Country Code), BT-5141 (Place Country Code)](https://github.com/eForms/eForms). See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example

```json
{
  "parties": [
    {
      "id": "GB-LAC-E09000003",
      "name": "London Borough of Barnet",
      "roles": [
        "buyer"
      ],
      "identifier": {
        "scheme": "GB-LAC",
        "id": "E09000003",
        "legalName": "London Borough of Barnet"
      },
      "address": {
        "streetAddress": "4, North London Business Park, Oakleigh Rd S",
        "locality": "London",
        "region": "London",
        "postalCode": "N11 1NP",
        "countryName": "United Kingdom",
        "countryCode": "GB"
      }
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues), [this issue](https://github.com/open-contracting/standard/issues/524) and in [pull requests](https://github.com/open-contracting-extensions/ocds_contractTerms_extension/pulls?q=is%3Apr+is%3Aclosed).
