# Client

**`Class`**

The base signal.js client

## Hierarchy

* `EventEmitter`.**`Client`**

## Constructors

### constructor()

> **new Client**(config: [`IConfig`](../interfaces/interface.iconfig.md)): [`Client`](class.client.md)

#### Parameters

| Parameter | Type                                            |
| --------- | ----------------------------------------------- |
| config    | [`IConfig`](../interfaces/interface.iconfig.md) |

#### Returns

[`Client`](class.client.md)

## Properties

### process

> **process**: `ChildProcess`

### stickerPacks

> **stickerPacks**: [`ObjectCache`](broken-reference) = `{}`

### verbose

> **verbose**: `boolean` = `false`

## Events

### on()

> **on**(event: "cliEvent", listener: `Function`): [`Client`](class.client.md)

Client#cliEvent

#### Parameters

| Parameter | Type                                                                   |
| --------- | ---------------------------------------------------------------------- |
| event     | "cliEvent"                                                             |
| listener  | (event: [`ICLIEvent`](../interfaces/interface.iclievent.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "typingMessage", listener: `Function`): [`Client`](class.client.md)

Client#typingMessage

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "typingMessage"                                                                                                   |
| listener  | (message: [`DMTypingMessage`](broken-reference) \| [`GroupTypingMessage`](class.grouptypingmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "message", listener: `Function`): [`Client`](class.client.md)

Client#message

#### Parameters

| Parameter | Type                                                                                               |
| --------- | -------------------------------------------------------------------------------------------------- |
| event     | "message"                                                                                          |
| listener  | (message: [`DMDataMessage`](broken-reference) \| [`GroupDataMessage`](broken-reference)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "editMessage", listener: `Function`): [`Client`](class.client.md)

Client#editMessage

#### Parameters

| Parameter | Type                                                                                                        |
| --------- | ----------------------------------------------------------------------------------------------------------- |
| event     | "editMessage"                                                                                               |
| listener  | (message: [`DMEditMessage`](broken-reference) \| [`GroupEditMessage`](class.groupeditmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reaction", listener: `Function`): [`Client`](class.client.md)

Client#reaction

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reaction"                                                                                                                        |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionAdd", listener: `Function`): [`Client`](class.client.md)

Client#reactionAdd

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionAdd"                                                                                                                     |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionRemove", listener: `Function`): [`Client`](class.client.md)

Client#reactionRemove

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionRemove"                                                                                                                  |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "sticker", listener: `Function`): [`Client`](class.client.md)

Client#sticker

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "sticker"                                                                                                         |
| listener  | (message: [`GroupStickerMessage`](broken-reference) \| [`DMStickerMessage`](class.dmstickermessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "deleteMessage", listener: `Function`): [`Client`](class.client.md)

Client#deleteMessage

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "deleteMessage"                                                                                                   |
| listener  | (message: [`GroupDeleteMessage`](class.groupdeletemessage.md) \| [`DMDeleteMessage`](broken-reference)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "groupUpdate", listener: `Function`): [`Client`](class.client.md)

Client#groupUpdate

#### Parameters

| Parameter | Type                                         |
| --------- | -------------------------------------------- |
| event     | "groupUpdate"                                |
| listener  | (group: [`Group`](class.group.md)) => `void` |

#### Returns

[`Client`](class.client.md)
