# Deno lab

First steps using deno

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
```
deno help
```

Fetch a webpage

### Prerequisites

What things you need to install the software and how to install them

### Samples 

Welcome
```
deno run https://deno.land/std@0.97.0/examples/welcome.ts
cat welcome.ts | deno run -
```

Fetch a webpage
```
deno run --allow-net=example.com https://deno.land/std@0.98.0/examples/curl.ts https://example.com
```

Read a file
```
deno run --allow-read .\src\cat.ts O:\tmp\clip.md
```

TCP server
```
deno run --allow-net https://deno.land/std@0.99.0/examples/echo_server.ts
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/tankred/deno-lab/tags).

## Authors

Tankred

## License

[GPL v3](GPL_license.txt)

## Acknowledgments

* Hat tip to anyone whose code was used
* [Deno manual](https://deno.land/manual/getting_started/first_steps)
