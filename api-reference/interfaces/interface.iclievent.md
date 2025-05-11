# ICLIEvent

**`Interface`**

An event received from signal-cli that is not associated with any earlier request

## Properties

### jsonrpc

> **jsonrpc**: "2.0"

The version of JSON-RPC used by signal-cli

### method

> **method**: `string`

The method used internally to receive this event (usually "receive")

### params

> **params**: `object`

The data received from the event

#### Type declaration (params)

> > **result**: `object`
>
> Starting with signal-cli 0.12.0, the envelope is wrapped in 'result'.
>
> **Type declaration (result)**
>
> > > **account**: `string`
> >
> > The phone number of the account that received the event
> >
> > > **envelope**: `any`
> >
> > The decrypted message
>
> > **subscription**: `number`
>
> Undocumented, but we suppose this has something to do with the account having a Signal badge or not.
>
> If you know what this does, feel free to edit this
