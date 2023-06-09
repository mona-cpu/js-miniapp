**[js-miniapp-sdk](../README.md)**

> [Globals](../README.md) / SecureStorageBusyError

# Class: SecureStorageBusyError

## Hierarchy

* [MiniAppError](miniapperror.md)

  ↳ **SecureStorageBusyError**

## Index

### Constructors

* [constructor](securestoragebusyerror.md#constructor)

### Properties

* [errorInput](securestoragebusyerror.md#errorinput)
* [message](securestoragebusyerror.md#message)
* [name](securestoragebusyerror.md#name)
* [stack](securestoragebusyerror.md#stack)

## Constructors

### constructor

\+ **new SecureStorageBusyError**(`errorInput`: [MiniAppJson](../interfaces/miniappjson.md)): [SecureStorageBusyError](securestoragebusyerror.md)

*Overrides [MiniAppError](miniapperror.md).[constructor](miniapperror.md#constructor)*

*Defined in [js-miniapp-bridge/src/types/error-types/secure-storage-errors.ts:18](https://github.com/rakutentech/js-miniapp/blob/c06869b/js-miniapp-bridge/src/types/error-types/secure-storage-errors.ts#L18)*

#### Parameters:

Name | Type |
------ | ------ |
`errorInput` | [MiniAppJson](../interfaces/miniappjson.md) |

**Returns:** [SecureStorageBusyError](securestoragebusyerror.md)

## Properties

### errorInput

•  **errorInput**: [MiniAppJson](../interfaces/miniappjson.md)

*Overrides [MiniAppError](miniapperror.md).[errorInput](miniapperror.md#errorinput)*

*Defined in [js-miniapp-bridge/src/types/error-types/secure-storage-errors.ts:19](https://github.com/rakutentech/js-miniapp/blob/c06869b/js-miniapp-bridge/src/types/error-types/secure-storage-errors.ts#L19)*

___

### message

•  **message**: string

*Inherited from [MiniAppError](miniapperror.md).[message](miniapperror.md#message)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:974*

___

### name

•  **name**: string

*Inherited from [MiniAppError](miniapperror.md).[name](miniapperror.md#name)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:973*

___

### stack

• `Optional` **stack**: string

*Inherited from [MiniAppError](miniapperror.md).[stack](miniapperror.md#stack)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:975*