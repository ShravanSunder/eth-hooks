---
id: "EthersAppContext.EthersModalConnector"
title: "Class: EthersModalConnector"
sidebar_label: "EthersModalConnector"
custom_edit_url: null
---

[EthersAppContext](../modules/EthersAppContext.md).EthersModalConnector

## Hierarchy

- `AbstractConnector`

  ↳ **`EthersModalConnector`**

## Implements

- [`ICommonModalConnector`](../interfaces/EthersAppContext.ICommonModalConnector.md)

## Properties

### \_options

• `Protected` **\_options**: `Partial`<`ICoreOptions`\>

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:72

___

### \_providerBase

• `Protected` `Optional` **\_providerBase**: `any`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:73

___

### \_ethersProvider

• `Protected` `Optional` **\_ethersProvider**: [`TEthersProvider`](../modules/Models.md#tethersprovider)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:74

___

### \_web3Modal

• `Protected` `Optional` **\_web3Modal**: `Core`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:75

___

### \_id

• `Protected` **\_id**: `undefined` \| `string`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:76

___

### \_debug

• `Protected` **\_debug**: `boolean` = `false`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:77

___

### \_config

• `Protected` **\_config**: `Readonly`<`TEthersModalConfig`\>

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:78

___

### \_signer

• `Protected` **\_signer**: `undefined` \| `Signer`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:79

___

### \_theme

• `Protected` **\_theme**: `TWeb3ModalTheme` \| `ThemeColors`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:80

___

### isModalOpening

▪ `Static` **isModalOpening**: `boolean` = `false`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:81

## Accessors

### config

• `get` **config**(): `Readonly`<`TEthersModalConfig`\>

#### Returns

`Readonly`<`TEthersModalConfig`\>

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:83

## Methods

### hasCachedProvider

▸ **hasCachedProvider**(): `boolean`

#### Returns

`boolean`

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[hasCachedProvider](../interfaces/EthersAppContext.ICommonModalConnector.md#hascachedprovider)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:87

___

### log

▸ `Protected` **log**(...`args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Returns

`void`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:117

___

### loadWeb3Modal

▸ **loadWeb3Modal**(): `void`

#### Returns

`void`

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[loadWeb3Modal](../interfaces/EthersAppContext.ICommonModalConnector.md#loadweb3modal)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:167

___

### activate

▸ **activate**(): `Promise`<`ConnectorUpdate`<`string` \| `number`\>\>

#### Returns

`Promise`<`ConnectorUpdate`<`string` \| `number`\>\>

#### Overrides

AbstractConnector.activate

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:189

___

### deactivate

▸ **deactivate**(): `void`

#### Returns

`void`

#### Overrides

AbstractConnector.deactivate

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:262

___

### getProvider

▸ **getProvider**(): `Promise`<`undefined` \| [`TEthersProvider`](../modules/Models.md#tethersprovider)\>

#### Returns

`Promise`<`undefined` \| [`TEthersProvider`](../modules/Models.md#tethersprovider)\>

#### Overrides

AbstractConnector.getProvider

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:282

___

### getChainId

▸ **getChainId**(): `Promise`<`string` \| `number`\>

#### Returns

`Promise`<`string` \| `number`\>

#### Overrides

AbstractConnector.getChainId

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:286

___

### getAccount

▸ **getAccount**(): `Promise`<``null`` \| `string`\>

#### Returns

`Promise`<``null`` \| `string`\>

#### Overrides

AbstractConnector.getAccount

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:296

___

### getSigner

▸ **getSigner**(): `undefined` \| `Signer`

#### Returns

`undefined` \| `Signer`

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[getSigner](../interfaces/EthersAppContext.ICommonModalConnector.md#getsigner)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:308

___

### getSignerFromAccount

▸ **getSignerFromAccount**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:312

___

### changeSigner

▸ **changeSigner**(`signer`): `Promise`<`void`\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `signer` | `Signer` |  |

#### Returns

`Promise`<`void`\>

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[changeSigner](../interfaces/EthersAppContext.ICommonModalConnector.md#changesigner)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:323

___

### validState

▸ `Protected` **validState**(): `boolean`

#### Returns

`boolean`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:334

___

### resetModal

▸ **resetModal**(): `void`

#### Returns

`void`

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[resetModal](../interfaces/EthersAppContext.ICommonModalConnector.md#resetmodal)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:342

___

### setModalTheme

▸ **setModalTheme**(`theme`): `void`

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `theme` | `TWeb3ModalTheme` \| `ThemeColors` |  |

#### Returns

`void`

#### Implementation of

[ICommonModalConnector](../interfaces/EthersAppContext.ICommonModalConnector.md).[setModalTheme](../interfaces/EthersAppContext.ICommonModalConnector.md#setmodaltheme)

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:357

___

### checkValidCachedProvider

▸ **checkValidCachedProvider**(): `boolean`

#### Returns

`boolean`

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:361

## Constructors

### constructor

• **new EthersModalConnector**(`web3modalOptions`, `config?`, `id?`, `debug?`)

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `web3modalOptions` | `Partial`<`ICoreOptions`\> | `undefined` |  |
| `config` | `TEthersModalConfig` | `undefined` |  |
| `id?` | `string` | `undefined` |  |
| `debug` | `boolean` | `false` |  |

#### Overrides

AbstractConnector.constructor

#### Defined in

context/ethers-app/connectors/EthersModalConnector.ts:97
