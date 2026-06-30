# CHASER Cards

Official CHASER Cards repository for Project Artemis.

CHASER stands for:

- Context
- Hypothesis
- Analyze
- Strategize
- Execute
- Review

Each card has:

- a visual PNG in the repository root
- a machine-readable JSON file under `/json`
- a manifest entry in `cards.json`

The card structure groups Context and Hypothesis under Preparation, Analyze
and Strategize under Action, and Execute and Review under Response.

## Card Creation Notes

New card PNGs must keep the same visual system as the existing card set.
The RV logo and the Preparation, Action, and Response heading icons should
match the checked-in cards exactly; do not use fallback-drawn or redrawn
approximations for those shared visual assets.

## Repository Layout

```text
/
├── cards.json
├── chaser-card.schema.json
├── README.md
├── LICENSE
├── CHASER-0001-log4shell.png
├── json/
│   └── CHASER-0001-log4shell.json
├── docs/
└── archive/
```

## License

CHASER Cards are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).

Attribution: Richard Vallejo, https://richardvallejo.com
