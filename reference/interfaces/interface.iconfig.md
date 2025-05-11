# IConfig

**`Interface`**

Signal.js configuration options

## Properties

### account

> **account**: `string`

The phone number that has been previously associated with signal-cli that signal.js will use.

`--account` in signal-cli

### cliLog

> **cliLog**?: `string`

A file signal-cli will save logs to

Note: Unless `scrubLog` is true, this will contain personal information, such as the exchanged messages.

`--log-file` in signal-cli

### configPath

> **configPath**?: `string`

An optional path to a custom config directory for signal-cli.

`--config` in signal-cli

### environment

> **environment**?: [`ConfigEnvironment`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.ConfigEnvironment.md)

The server environment to use with signal-cli. Leave the default if you don't know what you're doing.

`--service-environment` in signal-cli

### ignoreOldEvents

> **ignoreOldEvents**?: `boolean`

Whether old events (events sent while the client was offline) should be processed or ignored. true will ignore and false will process.

#### Default

```ts
true;
```

### logEvents

> **logEvents**?: `boolean`

Whether events should be shown to `console.log`, used mainly for debugging

### scrubLog

> **scrubLog**?: `boolean`

Only save technical information to the logs and remove any personal information.

`--scrub-log` in signal-cli

### signalCli

> **signalCli**?: `string`

An absolute or relative (to `process.cwd`) path to a custom signal-cli executable.

Leave this unset to use the bundled signal-cli executable. Using a custom incompatible executable may cause issues and unintended behavior, proceed with caution.

### system

> **system**?: [`ISystemConfig`](interface.isystemconfig.md)

Advanced parameters for the signal-cli process

### trustLevel

> **trustLevel**?: [`ConfigTrustLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.ConfigTrustLevel.md)

When to trust new identities.

`--trust-new-identities` in signal-cli
