# Effective Markdown expansions

A few radically effective Markdown snippets I use in [Espanso.org](https://espanso.org/).

## Installation

This is [an "external" package](https://espanso.org/docs/packages/external-packages/).

```plaintext
espanso install gitlab-support --external --git https://gitlab.com/gitlab-com/support/toolbox/espanso \
  --force  # to overwrite/upgrade already installed package
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
``` [) ``` | ``` [$\|$]({{clipboard}}) ```
``` ]() ``` | ``` ]({{clipboard}}) ```
``` -[ ``` | ``` - [ ]  ```
``` --[ ``` | ``` - [ ] $\|$\n- [ ]  ```
``` >>-- ``` | ``` > $\|$\n> -- {{clipboard}}\n\n ```
``` ``go`` ``` | ` ```go\n$\|$\n``` `
``` ``j`` ``` | ` ```java\n$\|$\n``` `
``` ``js`` ``` | ` ```javascript\n$\|$\n``` `
``` ``kt`` ``` | ` ```kotlin\n$\|$\n``` `
``` ``pt`` ``` | ` ```plaintext\n$\|$\n``` `
``` ``rb`` ``` | ` ```ruby\n$\|$\n``` `
``` ``rs`` ``` | ` ```rust\n$\|$\n``` `
``` ``sh`` ``` | ` ```shell\n$\|$\n``` `
``` ``ts`` ``` | ` ```typescript\n$\|$\n``` `
``` ``y`` ``` | ` ```yaml\n$\|$\n``` `
