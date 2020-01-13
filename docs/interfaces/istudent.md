[koa-base-template](../README.md) › [Globals](../globals.md) › [IStudent](istudent.md)

# Interface: IStudent

## Hierarchy

* Document

  ↳ **IStudent**

## Index

### Properties

* [__v](istudent.md#optional-__v)
* [base](istudent.md#base)
* [baseModelName](istudent.md#basemodelname)
* [collection](istudent.md#collection)
* [db](istudent.md#db)
* [discriminators](istudent.md#discriminators)
* [gender](istudent.md#gender)
* [id](istudent.md#optional-id)
* [modelName](istudent.md#modelname)
* [name](istudent.md#name)
* [schema](istudent.md#schema)
* [serial](istudent.md#serial)
* [status](istudent.md#status)

### Methods

* [$isDeleted](istudent.md#$isdeleted)
* [addListener](istudent.md#addlistener)
* [emit](istudent.md#emit)
* [eventNames](istudent.md#eventnames)
* [getMaxListeners](istudent.md#getmaxlisteners)
* [increment](istudent.md#increment)
* [listenerCount](istudent.md#listenercount)
* [listeners](istudent.md#listeners)
* [model](istudent.md#model)
* [off](istudent.md#off)
* [on](istudent.md#on)
* [once](istudent.md#once)
* [prependListener](istudent.md#prependlistener)
* [prependOnceListener](istudent.md#prependoncelistener)
* [rawListeners](istudent.md#rawlisteners)
* [remove](istudent.md#remove)
* [removeAllListeners](istudent.md#removealllisteners)
* [removeListener](istudent.md#removelistener)
* [save](istudent.md#save)
* [setMaxListeners](istudent.md#setmaxlisteners)

## Properties

### `Optional` __v

• **__v**? : *number*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3360

Version using default version key. See http://mongoosejs.com/docs/guide.html#versionKey
If you're using another key, you will have to access it using []: doc[_myVersionKey]

___

###  base

• **base**: *"mongoose"*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3381

Base Mongoose instance the model uses.

___

###  baseModelName

• **baseModelName**: *string | undefined*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3387

If this is a discriminator model, baseModelName is the
name of the base model.

___

###  collection

• **collection**: *Collection*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3390

Collection the model uses.

___

###  db

• **db**: *Connection*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3393

Connection the model uses.

___

###  discriminators

• **discriminators**: *any*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3396

Registered discriminators for this model.

___

###  gender

• **gender**: *string*

Defined in src/api/student/models/interface.ts:6

___

### `Optional` id

• **id**? : *any*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:1444

Virtual getter that by default returns the document's _id field cast to a string,
or in the case of ObjectIds, its hexString. This id getter may be disabled by
passing the option { id: false } at schema construction time. If disabled, id
behaves like any other field on a document and can be assigned any value.

___

###  modelName

• **modelName**: *string*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3399

The name of the model

___

###  name

• **name**: *string*

Defined in src/api/student/models/interface.ts:5

___

###  schema

• **schema**: *Schema*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3402

Schema the model uses.

___

###  serial

• **serial**: *number*

Defined in src/api/student/models/interface.ts:4

___

###  status

• **status**: *string*

Defined in src/api/student/models/interface.ts:7

## Methods

###  $isDeleted

▸ **$isDeleted**(`isDeleted`: boolean): *void*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3336

Override whether mongoose thinks this doc is deleted or not

**Parameters:**

Name | Type |
------ | ------ |
`isDeleted` | boolean |

**Returns:** *void*

▸ **$isDeleted**(): *boolean*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3338

whether mongoose thinks this doc is deleted.

**Returns:** *boolean*

___

###  addListener

▸ **addListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:612

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): *boolean*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:622

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |
`...args` | any[] |

**Returns:** *boolean*

___

###  eventNames

▸ **eventNames**(): *Array‹string | symbol›*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:627

**Returns:** *Array‹string | symbol›*

___

###  getMaxListeners

▸ **getMaxListeners**(): *number*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:619

**Returns:** *number*

___

###  increment

▸ **increment**(): *this*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3327

Signal that we desire an increment of this documents version.

**Returns:** *this*

___

###  listenerCount

▸ **listenerCount**(`type`: string | symbol): *number*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:623

**Parameters:**

Name | Type |
------ | ------ |
`type` | string &#124; symbol |

**Returns:** *number*

___

###  listeners

▸ **listeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:620

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  model

▸ **model**<**T**>(`name`: string): *Model‹T›*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3333

Returns another Model instance.

**Type parameters:**

▪ **T**: *Document*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`name` | string | model name  |

**Returns:** *Model‹T›*

___

###  off

▸ **off**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:616

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  on

▸ **on**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:613

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  once

▸ **once**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:614

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:625

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:626

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  rawListeners

▸ **rawListeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:621

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  remove

▸ **remove**(`fn?`: function): *Promise‹this›*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3344

Removes this document from the db.

**Parameters:**

▪`Optional`  **fn**: *function*

optional callback

▸ (`err`: any, `product`: this): *void*

**Parameters:**

Name | Type |
------ | ------ |
`err` | any |
`product` | this |

**Returns:** *Promise‹this›*

___

###  removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:617

**Parameters:**

Name | Type |
------ | ------ |
`event?` | string &#124; symbol |

**Returns:** *this*

___

###  removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:615

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  save

▸ **save**(`options?`: SaveOptions, `fn?`: function): *Promise‹this›*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3353

Saves this document.

**Parameters:**

▪`Optional`  **options**: *SaveOptions*

options optional options

▪`Optional`  **fn**: *function*

optional callback

▸ (`err`: any, `product`: this): *void*

**Parameters:**

Name | Type |
------ | ------ |
`err` | any |
`product` | this |

**Returns:** *Promise‹this›*

▸ **save**(`fn?`: function): *Promise‹this›*

*Inherited from void*

Defined in node_modules/@types/mongoose/index.d.ts:3354

**Parameters:**

▪`Optional`  **fn**: *function*

▸ (`err`: any, `product`: this): *void*

**Parameters:**

Name | Type |
------ | ------ |
`err` | any |
`product` | this |

**Returns:** *Promise‹this›*

___

###  setMaxListeners

▸ **setMaxListeners**(`n`: number): *this*

*Inherited from void*

Defined in node_modules/@types/node/globals.d.ts:618

**Parameters:**

Name | Type |
------ | ------ |
`n` | number |

**Returns:** *this*
