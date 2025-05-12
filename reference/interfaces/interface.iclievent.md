# ICLIEvent

**`Interface`**

An event received from signal-cli that is not associated with any earlier request

## Properties

### jsonrpc

> **jsonrpc**: "2.0"

### method

> **method**: `string`

The method used internally to receive this event (usually "receive")

### params

> **params**: `object`

The data received from the event

#### Type declaration (params)

> > **account**: `string`
>
> The phone number of the account that received the event
>
> > **envelope**: `any`
>
> The decrypted message
>
> > **subscription**: `number`
>
> Undocumented, but we suppose this has something to do with the account having a Signal badge or not.
>
> If you know what this does, feel free to edit this
