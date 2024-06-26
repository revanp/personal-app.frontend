# Development Environment

## Prerequisite

- mise:
  - purpose: a polyglot tool version manager
  - website: <https://mise.jdx.dev>
- pnpm:
  - purpose: package manager for NodeJS ecosystem
  - website: <https://pnpm.io/>

All tools needed to develop this app SHOULD be listed inside the `.mise.toml` file on the root of the repo.

## Running in Local

After cloning the repo, and entering to the directory. Run following command to setup your local development env:

```shell
cp .env.example .env.local

# do your edit, as needed

mise trust      // this will trust the .env.local file and load the contents into your session.
mise install    // this will install plugins and tools defined in .mise.toml file.

pnpm run dev    // run the local version on your machine.
```