# ICLIRequest

**`Interface`**

A request to be sent to signal-cli

## Properties

### id

> **id**: \`${string}-${string}-${string}-${string}-${string}\`

### jsonrpc

> **jsonrpc**: "2.0"

The version of JSON-RPC used by signal-cli

### method

> **method**: `string`

The method used for the request

A list of the available methods can be accessed using `signal-cli --help`

### params

> **params**: `any`

The parameters used with this method

All parameters use camelCase instead of the original hyphen-format shown in signal-cli
