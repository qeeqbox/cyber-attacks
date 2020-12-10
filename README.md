## CyberAttacks
A collection of attacks and vulnerabilities meta files that were used in my previous pentest tools

## Severity Table
![](https://raw.githubusercontent.com/qeeqbox/falcon/main/readme/cve_table_qeeqbox_falcon.png)

## Base meta info (Possible)
```json
{
  "cia": [],
  "depends on": [],
  "description": "",
  "examples": {},
  "id": "",
  "impact": "",
  "names": [],
  "redemption": [],
  "references": [],
  "related": [],
  "risk": [],
  "type": ""
}
```

## Example
```json
{
  "cia": [
    "confidentiality",
    "integrity",
    "availability"
  ],
  "depends on": [
    "adversary's skill",
    "victim’s browser",
    "victim’s interaction"
  ],
  "description": "an adversary may trick user into clicking on an invisible or disguised element",
  "examples": {
    "1": [
      "adversary constructs a harmless-looking page promises bob a free iphone with click button (click here to claim)",
      "the webpage loads an invisible page with facebook like button that lined up on top the click button",
      "bob clicks on the button for free trip but instead clicks on the invisible facebook like button"
    ]
  },
  "id": "b655c620-7ccd-4647-8d2d-c2cd22997944",
  "impact": "high",
  "names": [
    "clickjacking",
    "user interface redress attack",
    "ui redress attack",
    "ui redressing"
  ],
  "redemption": [
    "x-frame-options",
    "framebusting",
    "implement captcha",
    "samesite cookies",
    "element randomization"
  ],
  "references": [
    "https://en.wikipedia.org/wiki/clickjacking"
  ],
  "related": [],
  "risk": [
    "read & modify data",
    "execute commands"
  ],
  "type": "generic"
}
```

## Disclaimer\Notes
- Use these as an idea or example of what could happen
