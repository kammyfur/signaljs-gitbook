# ISystemConfig

**`Interface`**

Configuration options used to configure the process

## Properties

### args

> **args**?: `string`\[]

Additional command-line arguments to pass to the signal-cli command

### spawn

> **spawn**?: `SpawnOptionsWithoutStdio`

Custom options to pass to `child_process.spawn`, use only if you know what you're doing as this WILL break stuff
