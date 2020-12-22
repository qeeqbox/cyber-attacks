## CyberAttacks
A collection of attacks and vulnerabilities meta files that were used in my previous pentest tools

## List
```
├── authentication
│   ├── authentication-bypass.json
│   ├── brute-force
│   │   ├── credential-stuffing.json
│   │   ├── dictionary-attack.json
│   │   ├── hybrid-brute-force.json
│   │   ├── password-spraying.json
│   │   ├── reverse-brute-force.json
│   │   └── simple-brute-force.json
│   ├── captcha-bypass.json
│   ├── default-credential.json
│   ├── multi-factor-authentication-bypass.json
│   └── session
│       ├── cross-site-request-forgery.json
│       ├── cross-site-script-inclusion.json
│       ├── session-fixation.json
│       ├── session-hijacking.json
│       └── session-replay.json
├── authorization
│   ├── authorization-bypass.json
│   ├── horizontal-privilege-escalation.json
│   └── vertical-privilege-escalation.json
├── buffer-overflow
│   ├── heap-based-overflow.json
│   ├── seh-overflow.json
│   └── stack-based-overflow.json
├── clickjacking.json
├── client-side
│   └── cross-frame-scripting.json
├── cross-site-scripting
│   ├── cross-site-scripting.json
│   ├── dom-based-cross-site-scripting.json
│   ├── reflected-cross-site-scripting.json
│   └── stored-cross-site-scripting.json
├── file-inclusion
│   ├── local-file-inclusion.json
│   └── remote-file-inclusion.json
├── http-request-smuggling.json
├── information-disclosure
│   ├── directory-listing.json
│   ├── forced-browsing.json
│   ├── hardcoded-sensitive-data.json
│   ├── information-leakage.json
│   ├── insecure-direct-object-reference.json
│   └── path-traversal.json
├── injection
│   ├── client-template-injection.json
│   ├── formula-injection.json
│   ├── http-header-injection.json
│   ├── ldap-injection.json
│   ├── log-injection.json
│   ├── nosql-injection.json
│   ├── open-redirect.json
│   ├── os-command-injection.json
│   ├── reflection-injection.json
│   ├── server-side-template-injection.json
│   ├── sql-injection.json
│   ├── xpath-injection.json
│   ├── xslt-injection.json
│   └── xxe-injection.json
└── insecure-deserialization.json
```

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
