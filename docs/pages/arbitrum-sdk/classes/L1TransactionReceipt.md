---
id: "L1TransactionReceipt"
title: "Class L1TransactionReceipt"
sidebar_label: "L1TransactionReceipt"
sidebar_position: 0
custom_edit_url: null
---

## Implements

- `TransactionReceipt`

## Constructors

### constructor

• **new L1TransactionReceipt**(`tx`): [`L1TransactionReceipt`](L1TransactionReceipt.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `TransactionReceipt` |

#### Returns

[`L1TransactionReceipt`](L1TransactionReceipt.md)

#### Defined in

[src/lib/message/L1Transaction.ts:81](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L81)

## Properties

### blockHash

• `Readonly` **blockHash**: `string`

#### Implementation of

TransactionReceipt.blockHash

#### Defined in

[src/lib/message/L1Transaction.ts:70](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L70)

___

### blockNumber

• `Readonly` **blockNumber**: `number`

#### Implementation of

TransactionReceipt.blockNumber

#### Defined in

[src/lib/message/L1Transaction.ts:73](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L73)

___

### byzantium

• `Readonly` **byzantium**: `boolean`

#### Implementation of

TransactionReceipt.byzantium

#### Defined in

[src/lib/message/L1Transaction.ts:77](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L77)

___

### confirmations

• `Readonly` **confirmations**: `number`

#### Implementation of

TransactionReceipt.confirmations

#### Defined in

[src/lib/message/L1Transaction.ts:74](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L74)

___

### contractAddress

• `Readonly` **contractAddress**: `string`

#### Implementation of

TransactionReceipt.contractAddress

#### Defined in

[src/lib/message/L1Transaction.ts:65](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L65)

___

### cumulativeGasUsed

• `Readonly` **cumulativeGasUsed**: `BigNumber`

#### Implementation of

TransactionReceipt.cumulativeGasUsed

#### Defined in

[src/lib/message/L1Transaction.ts:75](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L75)

___

### effectiveGasPrice

• `Readonly` **effectiveGasPrice**: `BigNumber`

#### Implementation of

TransactionReceipt.effectiveGasPrice

#### Defined in

[src/lib/message/L1Transaction.ts:76](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L76)

___

### from

• `Readonly` **from**: `string`

#### Implementation of

TransactionReceipt.from

#### Defined in

[src/lib/message/L1Transaction.ts:64](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L64)

___

### gasUsed

• `Readonly` **gasUsed**: `BigNumber`

#### Implementation of

TransactionReceipt.gasUsed

#### Defined in

[src/lib/message/L1Transaction.ts:68](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L68)

___

### logs

• `Readonly` **logs**: `Log`[]

#### Implementation of

TransactionReceipt.logs

#### Defined in

[src/lib/message/L1Transaction.ts:72](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L72)

___

### logsBloom

• `Readonly` **logsBloom**: `string`

#### Implementation of

TransactionReceipt.logsBloom

#### Defined in

[src/lib/message/L1Transaction.ts:69](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L69)

___

### root

• `Optional` `Readonly` **root**: `string`

#### Implementation of

TransactionReceipt.root

#### Defined in

[src/lib/message/L1Transaction.ts:67](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L67)

___

### status

• `Optional` `Readonly` **status**: `number`

#### Implementation of

TransactionReceipt.status

#### Defined in

[src/lib/message/L1Transaction.ts:79](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L79)

___

### to

• `Readonly` **to**: `string`

#### Implementation of

TransactionReceipt.to

#### Defined in

[src/lib/message/L1Transaction.ts:63](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L63)

___

### transactionHash

• `Readonly` **transactionHash**: `string`

#### Implementation of

TransactionReceipt.transactionHash

#### Defined in

[src/lib/message/L1Transaction.ts:71](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L71)

___

### transactionIndex

• `Readonly` **transactionIndex**: `number`

#### Implementation of

TransactionReceipt.transactionIndex

#### Defined in

[src/lib/message/L1Transaction.ts:66](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L66)

___

### type

• `Readonly` **type**: `number`

#### Implementation of

TransactionReceipt.type

#### Defined in

[src/lib/message/L1Transaction.ts:78](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L78)

## Methods

### getEthDeposits

▸ **getEthDeposits**(`l2Provider`): `Promise`\<`EthDepositMessage`[]\>

Get any eth deposit messages created by this transaction

#### Parameters

| Name | Type |
| :------ | :------ |
| `l2Provider` | `Provider` |

#### Returns

`Promise`\<`EthDepositMessage`[]\>

#### Defined in

[src/lib/message/L1Transaction.ts:182](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L182)

___

### getInboxMessageDeliveredEvents

▸ **getInboxMessageDeliveredEvents**(): \{ `data`: `string` ; `messageNum`: `BigNumber`  }[]

Get any InboxMessageDelivered events that were emitted during this transaction

#### Returns

\{ `data`: `string` ; `messageNum`: `BigNumber`  }[]

#### Defined in

[src/lib/message/L1Transaction.ts:125](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L125)

___

### getL1ToL2Messages

▸ **getL1ToL2Messages**\<`T`\>(`l2SignerOrProvider`): `Promise`\<`L1ToL2MessageReaderOrWriter`\<`T`\>[]\>

Get any l1tol2 messages created by this transaction

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `SignerOrProvider` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `l2SignerOrProvider` | `T` |

#### Returns

`Promise`\<`L1ToL2MessageReaderOrWriter`\<`T`\>[]\>

#### Defined in

[src/lib/message/L1Transaction.ts:239](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L239)

___

### getL1ToL2MessagesClassic

▸ **getL1ToL2MessagesClassic**(`l2Provider`): `Promise`\<[`L1ToL2MessageReaderClassic`](L1ToL2MessageReaderClassic.md)[]\>

Get classic l1tol2 messages created by this transaction

#### Parameters

| Name | Type |
| :------ | :------ |
| `l2Provider` | `Provider` |

#### Returns

`Promise`\<[`L1ToL2MessageReaderClassic`](L1ToL2MessageReaderClassic.md)[]\>

#### Defined in

[src/lib/message/L1Transaction.ts:207](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L207)

___

### getMessageDeliveredEvents

▸ **getMessageDeliveredEvents**(): \{ `baseFeeL1`: `BigNumber` ; `beforeInboxAcc`: `string` ; `inbox`: `string` ; `kind`: `number` ; `messageDataHash`: `string` ; `messageIndex`: `BigNumber` ; `sender`: `string` ; `timestamp`: `BigNumber`  }[]

Get any MessageDelivered events that were emitted during this transaction

#### Returns

\{ `baseFeeL1`: `BigNumber` ; `beforeInboxAcc`: `string` ; `inbox`: `string` ; `kind`: `number` ; `messageDataHash`: `string` ; `messageIndex`: `BigNumber` ; `sender`: `string` ; `timestamp`: `BigNumber`  }[]

#### Defined in

[src/lib/message/L1Transaction.ts:117](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L117)

___

### getMessageEvents

▸ **getMessageEvents**(): \{ `bridgeMessageEvent`: \{ `baseFeeL1`: `BigNumber` ; `beforeInboxAcc`: `string` ; `inbox`: `string` ; `kind`: `number` ; `messageDataHash`: `string` ; `messageIndex`: `BigNumber` ; `sender`: `string` ; `timestamp`: `BigNumber`  } ; `inboxMessageEvent`: \{ `data`: `string` ; `messageNum`: `BigNumber`  }  }[]

Get combined data for any InboxMessageDelivered and MessageDelivered events
emitted during this transaction

#### Returns

\{ `bridgeMessageEvent`: \{ `baseFeeL1`: `BigNumber` ; `beforeInboxAcc`: `string` ; `inbox`: `string` ; `kind`: `number` ; `messageDataHash`: `string` ; `messageIndex`: `BigNumber` ; `sender`: `string` ; `timestamp`: `BigNumber`  } ; `inboxMessageEvent`: \{ `data`: `string` ; `messageNum`: `BigNumber`  }  }[]

#### Defined in

[src/lib/message/L1Transaction.ts:138](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L138)

___

### getTokenDepositEvents

▸ **getTokenDepositEvents**(): \{ `_amount`: `BigNumber` ; `_from`: `string` ; `_sequenceNumber`: `BigNumber` ; `_to`: `string` ; `l1Token`: `string`  }[]

Get any token deposit events created by this transaction

#### Returns

\{ `_amount`: `BigNumber` ; `_from`: `string` ; `_sequenceNumber`: `BigNumber` ; `_to`: `string` ; `l1Token`: `string`  }[]

#### Defined in

[src/lib/message/L1Transaction.ts:287](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L287)

___

### isClassic

▸ **isClassic**\<`T`\>(`l2SignerOrProvider`): `Promise`\<`boolean`\>

Check if is a classic transaction

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `SignerOrProvider` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `l2SignerOrProvider` | `T` |

#### Returns

`Promise`\<`boolean`\>

#### Defined in

[src/lib/message/L1Transaction.ts:105](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L105)

___

### monkeyPatchContractCallWait

▸ **monkeyPatchContractCallWait**(`contractTransaction`): `L1ContractCallTransaction`

Replaces the wait function with one that returns an L1ContractCallTransactionReceipt

#### Parameters

| Name | Type |
| :------ | :------ |
| `contractTransaction` | `ContractTransaction` |

#### Returns

`L1ContractCallTransaction`

#### Defined in

[src/lib/message/L1Transaction.ts:332](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L332)

___

### monkeyPatchEthDepositWait

▸ **monkeyPatchEthDepositWait**(`contractTransaction`): `L1EthDepositTransaction`

Replaces the wait function with one that returns an L1EthDepositTransactionReceipt

#### Parameters

| Name | Type |
| :------ | :------ |
| `contractTransaction` | `ContractTransaction` |

#### Returns

`L1EthDepositTransaction`

#### Defined in

[src/lib/message/L1Transaction.ts:316](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L316)

___

### monkeyPatchWait

▸ **monkeyPatchWait**(`contractTransaction`): [`L1ContractTransaction`](../interfaces/L1ContractTransaction.md)\<[`L1TransactionReceipt`](L1TransactionReceipt.md)\>

Replaces the wait function with one that returns an L1TransactionReceipt

#### Parameters

| Name | Type |
| :------ | :------ |
| `contractTransaction` | `ContractTransaction` |

#### Returns

[`L1ContractTransaction`](../interfaces/L1ContractTransaction.md)\<[`L1TransactionReceipt`](L1TransactionReceipt.md)\>

#### Defined in

[src/lib/message/L1Transaction.ts:300](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/message/L1Transaction.ts#L300)