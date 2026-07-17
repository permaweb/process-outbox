# `process-outbox@1.0`

HyperBEAM Forge package for AO process outbox and subscription behavior.

The package root device is `process-outbox@1.0`. It appends outbound messages to
`results/outbox`, forwards `x-` request keys into notices, and can fan out
notifications to subscribers registered by action and target.

## published package

```bash
Published device: process-outbox@1.0; 

Specification ID: iVu-4BJxuR8h-FNmYv3ycVV9Y18lfCpgPea6iNt9unc; 

Implementation ID: BmBut-zW00154C4deJSkwCbr8FTTv4Oj4SzYnNhLL4c; 

Signer: vZY2XY1RD9HIfWi8ift-1_DnHLDadZMWrufSh-_rKF0.
```

## build

```sh
rebar3 compile
rebar3 device verify
rebar3 device package
```


## test

```sh
HB_PORT=0 rebar3 device test
rebar3 eunit-all
```

## license
this package is licensed under the [MIT License](./LICENSE)