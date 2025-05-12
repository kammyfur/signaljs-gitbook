# Client

**`Class`**

The base Signal.js client interface

## Hierarchy

* `EventEmitter`.**`Client`**

## Constructors

### constructor()

> **new Client**(config: [`IConfig`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IConfig.md)): [`Client`](class.client.md)

#### Parameters

| Parameter | Type                                                                                                            | Description                              |
| --------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| config    | [`IConfig`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IConfig.md) | The configuration to use with signal-cli |

#### Returns

[`Client`](class.client.md)

## Properties

### process

> **process**: `ChildProcess`

The signal-cli process

### stickerPacks

> **stickerPacks**: [`ObjectCache`](class.objectcache.md) = `{}`

An [ObjectCache](class.objectcache.md) for the registered sticker packs

### verbose

> **verbose**: `boolean` = `false`

Whether verbose mode (logging events) should be enabled

## Events

### on()

> **on**(event: "cliEvent", listener: `Function`): [`Client`](class.client.md)

Emitted when a Signal event, even if unsupported, is received by signal-cli Client#cliEvent

#### Parameters

| Parameter | Type                                                                                                                                   |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| event     | "cliEvent"                                                                                                                             |
| listener  | (event: [`ICLIEvent`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.ICLIEvent.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "typingMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a typing message is received Client#typingMessage

#### Parameters

| Parameter | Type                                                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| event     | "typingMessage"                                                                                                           |
| listener  | (message: [`DMTypingMessage`](class.dmtypingmessage.md) \| [`GroupTypingMessage`](class.grouptypingmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "message", listener: `Function`): [`Client`](class.client.md)

Emitted when a data (text) message is received Client#message

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "message"                                                                                                         |
| listener  | (message: [`DMDataMessage`](class.dmdatamessage.md) \| [`GroupDataMessage`](class.groupdatamessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "editMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a message is edited Client#editMessage

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "editMessage"                                                                                                     |
| listener  | (message: [`DMEditMessage`](class.dmeditmessage.md) \| [`GroupEditMessage`](class.groupeditmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reaction", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is added or removed to/from a message Client#reaction

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reaction"                                                                                                                        |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionAdd", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is added to a message Client#reactionAdd

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionAdd"                                                                                                                     |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionRemove", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is removed from a message Client#reactionRemove

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionRemove"                                                                                                                  |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "sticker", listener: `Function`): [`Client`](class.client.md)

Emitted when a sticker message is received Client#sticker

#### Parameters

| Parameter | Type                                                                                                                          |
| --------- | ----------------------------------------------------------------------------------------------------------------------------- |
| event     | "sticker"                                                                                                                     |
| listener  | (message: [`GroupStickerMessage`](class.groupstickermessage.md) \| [`DMStickerMessage`](class.dmstickermessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "deleteMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a message in a channel gets deleted Client#deleteMessage

#### Parameters

| Parameter | Type                                                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| event     | "deleteMessage"                                                                                                           |
| listener  | (message: [`GroupDeleteMessage`](class.groupdeletemessage.md) \| [`DMDeleteMessage`](class.dmdeletemessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "groupUpdate", listener: `Function`): [`Client`](class.client.md)

Emitted when a group's information gets updated Client#groupUpdate

#### Parameters

| Parameter | Type                                         |
| --------- | -------------------------------------------- |
| event     | "groupUpdate"                                |
| listener  | (group: [`Group`](class.group.md)) => `void` |

#### Returns

[`Client`](class.client.md)
