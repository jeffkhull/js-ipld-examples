# js-ipld-examples

A collection of proof of concept use of available libraries to accomplish tasks in IPFS using linked data (IPLD).

## Install dependencies

`npm i`

## Run examples - pure ipfs


```sh
npm run watch
npm run end-to-end
```

## Run examples - ceramic

*Note: you must have a local ceramic daemon running on localhost:7007*

```sh
npm run watch
npm run ceramic-test
```

### Installing ceramic daemon

https://github.com/ceramicnetwork/js-ceramic/
https://developers.ceramic.network/build/cli/installation/

```sh
npm install -g @ceramicnetwork/cli
ceramic daemon
```

## Research on mutable data in IPLD

There is a need to mutate and keep track of mutations to entities in IPLD.

### Relevant links

1. Mutable links in IPLD - https://github.com/ipld/specs/issues/9
1. IPFS Mutable File System (MFS) docs - http://docs.ipfs.io.ipns.localhost:8080/concepts/file-systems/
1. http://docs.ipfs.io.ipns.localhost:8080/concepts/immutability/
    1. See pointers and IPNS
1. IPNS Docs - http://docs.ipfs.io.ipns.localhost:8080/concepts/ipns/
1. https://github.com/ipld/js-ipld/issues/295#issuecomment-788823497
1. Go IPFS http client docs - https://pkg.go.dev/github.com/ipfs/go-ipfs-http-client
