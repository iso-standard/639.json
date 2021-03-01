# ISO Standard - 639 JSON
Those file represent the ISO 639 standard using JSON files

## Content
Each files contains:
* ISO 639-1 codes
* ISO 639-2 codes
* ISO 639-3 codes
* English language name
* Local language name 

## What's next?
It would be great to add countries which use officially, co-officially and unofficially the language by adding this structure:
```json5
{
  // ...
  "countries": {
    "officials": [],
    "co-officials": [],
    "unofficials": []
  }
}
```
Adding thse data will require a lot of time and is not currently required, but feel free to make PRs

## Structure
```json
{
  "639-1": "fr",
  "639-2": "fre/fra",
  "639-3": "fra",
  "name": {
    "en": "French",
    "fr": "Français"
    // ...
  }
}
```

## How to participate?
You can help by editing this repository files based on ISO 639 updates. Adding missing languages name translations in all locales, countries etc...

**Please do not create multi-purpose PR**

You can also support this project by becoming a sponsor, which will help me to spend more time on open source projects.