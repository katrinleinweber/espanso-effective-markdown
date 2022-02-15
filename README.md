# Effective Markdown expansions

A few radically effective Markdown snippets I use in [Espanso.org](https://espanso.org/).

## Installation

Not yet possible [directly](https://espanso.org/docs/packages/#from-a-repository),
but this works:

```shell
# espanso uninstall effective-markdown # In case you want to upgrade
espanso install effective-markdown --external  \
    https://github.com/katrinleinweber/espanso-effective-markdown
```

## Contributing

MRs are welcome! For major changes, please open an issue first to discuss what you would like to change.

### Development dependencies

Appending the up-to-date list of triggers and espansions requires:

- awk
- Make
- perl
- [jq](https://stedolan.github.io/jq/)
  & [yq](https://mikefarah.gitbook.io/yq/)
  via `asdf install`

## Other useful/noteworthy Espanso packages

- [greetings-english](https://github.com/katrinleinweber/espanso-greetings-english)
- [greetings-german](https://github.com/katrinleinweber/espanso-greetings-german)
- [Shruggie](https://hub.espanso.org/packages/shruggie/)

## List of included espansions

Trigger | Espansion
------- | ---------
`[)` | `[$\|$]({{clipboard}})`
`](` | `]({{clipboard}})`
`-[` | `- [ ] `
`--[` | `- [ ] $\|$\n- [ ] `
`>>--` | `> $\|$\n> -- {{clipboard}}\n\n`
