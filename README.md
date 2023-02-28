# Learn Helix 
Learn Helix.

## Environments
- Preview: https://main--helix-test-website--stevja1.hlx.page/
- Live: https://main--helix-test-website--stevja1.hlx.live/

None of these appear to be working currently... not sure what's up with Helix bot. Following instructions here:
https://www.hlx.live/developer/tutorial

## Installation

```sh
npm i
```

## Tests

```sh
npm tst
```

## Local development

1. Create a new repository based on the `helix-project-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [helix-bot](https://github.com/apps/helix-bot) to the repository
1. Install the [Helix CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/helix-cli`
1. Start Franklin Proxy: `hlx up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
