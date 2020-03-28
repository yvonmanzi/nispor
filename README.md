<!-- vim-markdown-toc GFM -->

* [Usage](#usage)
    * [Varlink service](#varlink-service)
    * [Varlink client](#varlink-client)
* [Goal](#goal)
* [TODO:](#todo)

<!-- vim-markdown-toc -->

## Usage

### Varlink service

```bash
make srv
```

### Varlink client

```bash
# Please install `libvarlink-util` pacakge beforehand
make cli
```


## Goal

 * Provide C/Python/Rust binding to query linux network status
 * Provide netlink interface for querying linux networks status

## TODO:
 * Varlink interface
    * Query
 * Iface plugin design
 * Bond, bridge
