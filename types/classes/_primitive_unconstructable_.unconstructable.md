[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["primitive/Unconstructable"](../modules/_primitive_unconstructable_.md) › [Unconstructable](_primitive_unconstructable_.unconstructable.md)

# Class: Unconstructable

**`name`** Unconstructable

**`description`** 
An unknown type theat fails on constrction with the type info

## Hierarchy

* [Null](_primitive_null_.null.md)

  ↳ **Unconstructable**

## Implements

* [Codec](../interfaces/_types_codec_.codec.md)

## Index

### Constructors

* [constructor](_primitive_unconstructable_.unconstructable.md#constructor)

### Properties

* [registry](_primitive_unconstructable_.unconstructable.md#registry)

### Accessors

* [encodedLength](_primitive_unconstructable_.unconstructable.md#encodedlength)
* [hash](_primitive_unconstructable_.unconstructable.md#hash)
* [isEmpty](_primitive_unconstructable_.unconstructable.md#isempty)

### Methods

* [eq](_primitive_unconstructable_.unconstructable.md#eq)
* [toHex](_primitive_unconstructable_.unconstructable.md#tohex)
* [toHuman](_primitive_unconstructable_.unconstructable.md#tohuman)
* [toJSON](_primitive_unconstructable_.unconstructable.md#tojson)
* [toRawType](_primitive_unconstructable_.unconstructable.md#torawtype)
* [toString](_primitive_unconstructable_.unconstructable.md#tostring)
* [toU8a](_primitive_unconstructable_.unconstructable.md#tou8a)
* [with](_primitive_unconstructable_.unconstructable.md#static-with)

## Constructors

###  constructor

\+ **new Unconstructable**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `typeName`: string): *[Unconstructable](_primitive_unconstructable_.unconstructable.md)*

*Overrides [Null](_primitive_null_.null.md).[constructor](_primitive_null_.null.md#constructor)*

*Defined in [packages/types/src/primitive/Unconstructable.ts:14](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Unconstructable.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) |
`typeName` | string |

**Returns:** *[Unconstructable](_primitive_unconstructable_.unconstructable.md)*

## Properties

###  registry

• **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md).[registry](../interfaces/_types_codec_.codec.md#registry)*

*Inherited from [Null](_primitive_null_.null.md).[registry](_primitive_null_.null.md#registry)*

*Defined in [packages/types/src/primitive/Null.ts:16](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L16)*

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [Null](_primitive_null_.null.md).[encodedLength](_primitive_null_.null.md#encodedlength)*

*Defined in [packages/types/src/primitive/Null.ts:25](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L25)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [Null](_primitive_null_.null.md).[hash](_primitive_null_.null.md#hash)*

*Defined in [packages/types/src/primitive/Null.ts:32](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L32)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [Null](_primitive_null_.null.md).[isEmpty](_primitive_null_.null.md#isempty)*

*Defined in [packages/types/src/primitive/Null.ts:39](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L39)*

**`description`** Checks if the value is an empty value (always true)

**Returns:** *boolean*

## Methods

###  eq

▸ **eq**(`other?`: any): *boolean*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [Null](_primitive_null_.null.md).[eq](_primitive_null_.null.md#eq)*

*Defined in [packages/types/src/primitive/Null.ts:46](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L46)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | any |

**Returns:** *boolean*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [Null](_primitive_null_.null.md).[toHex](_primitive_null_.null.md#tohex)*

*Defined in [packages/types/src/primitive/Null.ts:53](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L53)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(): *null*

*Inherited from [Null](_primitive_null_.null.md).[toHuman](_primitive_null_.null.md#tohuman)*

*Defined in [packages/types/src/primitive/Null.ts:60](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L60)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Returns:** *null*

___

###  toJSON

▸ **toJSON**(): *null*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [Null](_primitive_null_.null.md).[toJSON](_primitive_null_.null.md#tojson)*

*Defined in [packages/types/src/primitive/Null.ts:67](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L67)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *null*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [Null](_primitive_null_.null.md).[toRawType](_primitive_null_.null.md#torawtype)*

*Defined in [packages/types/src/primitive/Null.ts:74](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L74)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [Null](_primitive_null_.null.md).[toString](_primitive_null_.null.md#tostring)*

*Defined in [packages/types/src/primitive/Null.ts:81](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L81)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Inherited from [Null](_primitive_null_.null.md).[toU8a](_primitive_null_.null.md#tou8a)*

*Defined in [packages/types/src/primitive/Null.ts:90](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Null.ts#L90)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

___

### `Static` with

▸ **with**(`typeName`: string): *[Constructor](../interfaces/_types_codec_.constructor.md)*

*Defined in [packages/types/src/primitive/Unconstructable.ts:21](https://github.com/polkadot-js/api/blob/a4f56d3d3/packages/types/src/primitive/Unconstructable.ts#L21)*

**Parameters:**

Name | Type |
------ | ------ |
`typeName` | string |

**Returns:** *[Constructor](../interfaces/_types_codec_.constructor.md)*