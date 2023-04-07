# Installation

`yarn`

# Build smart contracts

```bash
# options: -d: build debug, -s: schema, -w: watch mode
yarn build contracts/package1 contracts/package2 contracts/package3 [-d] [-s] [-w]
```

The optimized contracts are generated in the artifacts/ directory.

# Generate typescript code

```bash
# if no --output is given, the default output is current directory
yarn gents contracts/package1 contracts/package2 contracts/package3 [--output build_folder] [--react-query]

```
