---

layout:     documentation
title:      "Documentation | eris:cli | eris services ports"

---

# eris services ports

Print port mappings

## Synopsis

Print port mappings.

The [eris services ports] command displays published service ports.

```bash
eris services ports NAME [PORT]...
```

## Examples

```bash
$ eris services ports ipfs -- will display all IPFS ports
$ eris services ports ipfs 4001 5001 -- will display specific IPFS ports
```

## Options inherited from parent commands

```
  -d, --debug            debug level output
  -m, --machine string   machine name for docker-machine that is running VM (default "eris")
  -v, --verbose          verbose output
```

## See Also

* [eris services](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/eris_services/)	 - Start, stop, and manage services required for your application

## Specifications

* [Actions Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/actions_specification/)
* [Chains Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/chains_specification/)
* [Contracts Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/contracts_specification/)
* [Motivation](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/motivation/)
* [Services Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.4/services_specification/)

