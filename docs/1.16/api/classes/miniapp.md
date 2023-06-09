**[js-miniapp-sdk](../README.md)**

> [Globals](../README.md) / MiniApp

# Class: MiniApp

## Hierarchy

* **MiniApp**

## Implements

* [MiniAppFeatures](../interfaces/miniappfeatures.md)
* [Ad](../interfaces/ad.md)
* Platform

## Index

### Properties

* [chatService](miniapp.md#chatservice)
* [miniappUtils](miniapp.md#miniapputils)
* [secureStorageService](miniapp.md#securestorageservice)
* [universalBridge](miniapp.md#universalbridge)
* [user](miniapp.md#user)

### Methods

* [downloadFile](miniapp.md#downloadfile)
* [getHostEnvironmentInfo](miniapp.md#gethostenvironmentinfo)
* [getMauid](miniapp.md#getmauid)
* [getMessagingUniqueId](miniapp.md#getmessaginguniqueid)
* [getPlatform](miniapp.md#getplatform)
* [getPoints](miniapp.md#getpoints)
* [getUniqueId](miniapp.md#getuniqueid)
* [loadInterstitialAd](miniapp.md#loadinterstitialad)
* [loadRewardedAd](miniapp.md#loadrewardedad)
* [requestCustomPermissions](miniapp.md#requestcustompermissions)
* [requestLocationPermission](miniapp.md#requestlocationpermission)
* [setCloseAlert](miniapp.md#setclosealert)
* [setScreenOrientation](miniapp.md#setscreenorientation)
* [shareInfo](miniapp.md#shareinfo)
* [showInterstitialAd](miniapp.md#showinterstitialad)
* [showRewardedAd](miniapp.md#showrewardedad)

## Properties

### chatService

•  **chatService**: ChatService = new ChatService()

*Defined in [js-miniapp-sdk/src/miniapp.ts:164](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L164)*

___

### miniappUtils

•  **miniappUtils**: MiniAppUtils = new MiniAppUtils()

*Defined in [js-miniapp-sdk/src/miniapp.ts:167](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L167)*

___

### secureStorageService

•  **secureStorageService**: SecureStorageService = new SecureStorageService()

*Defined in [js-miniapp-sdk/src/miniapp.ts:165](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L165)*

___

### universalBridge

•  **universalBridge**: UniversalBridge = new UniversalBridge()

*Defined in [js-miniapp-sdk/src/miniapp.ts:166](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L166)*

___

### user

•  **user**: [UserInfoProvider](../interfaces/userinfoprovider.md) = new UserInfo()

*Defined in [js-miniapp-sdk/src/miniapp.ts:163](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L163)*

## Methods

### downloadFile

▸ **downloadFile**(`filename`: string, `url`: string, `headers?`: [DownloadFileHeaders](../interfaces/downloadfileheaders.md)): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:272](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L272)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`filename` | string | - |
`url` | string | - |
`headers` | [DownloadFileHeaders](../interfaces/downloadfileheaders.md) | {} |

**Returns:** Promise\<string>

___

### getHostEnvironmentInfo

▸ **getHostEnvironmentInfo**(): Promise\<[HostEnvironmentInfo](../interfaces/hostenvironmentinfo.md)>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:263](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L263)*

**Returns:** Promise\<[HostEnvironmentInfo](../interfaces/hostenvironmentinfo.md)>

___

### getMauid

▸ **getMauid**(): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:184](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L184)*

**Returns:** Promise\<string>

___

### getMessagingUniqueId

▸ **getMessagingUniqueId**(): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:180](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L180)*

**Returns:** Promise\<string>

___

### getPlatform

▸ **getPlatform**(): string

*Defined in [js-miniapp-sdk/src/miniapp.ts:247](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L247)*

**Returns:** string

___

### getPoints

▸ **getPoints**(): Promise\<[Points](../interfaces/points.md)>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:259](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L259)*

**Returns:** Promise\<[Points](../interfaces/points.md)>

___

### getUniqueId

▸ **getUniqueId**(): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:176](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L176)*

**`deprecated`** Deprecated method for getting the uniqueId use `getMessagingUniqueId` or `getMauid` instead

**Returns:** Promise\<string>

___

### loadInterstitialAd

▸ **loadInterstitialAd**(`id`: string): Promise\<string>

*Implementation of [Ad](../interfaces/ad.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:227](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L227)*

#### Parameters:

Name | Type |
------ | ------ |
`id` | string |

**Returns:** Promise\<string>

___

### loadRewardedAd

▸ **loadRewardedAd**(`id`: string): Promise\<string>

*Implementation of [Ad](../interfaces/ad.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:231](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L231)*

#### Parameters:

Name | Type |
------ | ------ |
`id` | string |

**Returns:** Promise\<string>

___

### requestCustomPermissions

▸ **requestCustomPermissions**(`permissions`: [CustomPermission](../interfaces/custompermission.md)[]): Promise\<[CustomPermissionResult](../interfaces/custompermissionresult.md)[]>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:219](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L219)*

#### Parameters:

Name | Type |
------ | ------ |
`permissions` | [CustomPermission](../interfaces/custompermission.md)[] |

**Returns:** Promise\<[CustomPermissionResult](../interfaces/custompermissionresult.md)[]>

___

### requestLocationPermission

▸ **requestLocationPermission**(`permissionDescription?`: string): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:188](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L188)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`permissionDescription` | string | "" |

**Returns:** Promise\<string>

___

### setCloseAlert

▸ **setCloseAlert**(`alertInfo`: [CloseAlertInfo](../interfaces/closealertinfo.md)): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:283](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L283)*

**`deprecated`** Deprecated method for getting the uniqueId use `getMessagingUniqueId` or `getMauid` instead

#### Parameters:

Name | Type |
------ | ------ |
`alertInfo` | [CloseAlertInfo](../interfaces/closealertinfo.md) |

**Returns:** Promise\<string>

___

### setScreenOrientation

▸ **setScreenOrientation**(`screenOrientation`: [ScreenOrientation](../enums/screenorientation.md)): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:255](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L255)*

#### Parameters:

Name | Type |
------ | ------ |
`screenOrientation` | [ScreenOrientation](../enums/screenorientation.md) |

**Returns:** Promise\<string>

___

### shareInfo

▸ **shareInfo**(`info`: [ShareInfoType](../interfaces/shareinfotype.md)): Promise\<string>

*Implementation of [MiniAppFeatures](../interfaces/miniappfeatures.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:243](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L243)*

#### Parameters:

Name | Type |
------ | ------ |
`info` | [ShareInfoType](../interfaces/shareinfotype.md) |

**Returns:** Promise\<string>

___

### showInterstitialAd

▸ **showInterstitialAd**(`id`: string): Promise\<string>

*Implementation of [Ad](../interfaces/ad.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:235](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L235)*

#### Parameters:

Name | Type |
------ | ------ |
`id` | string |

**Returns:** Promise\<string>

___

### showRewardedAd

▸ **showRewardedAd**(`id`: string): Promise\<[Reward](../interfaces/reward.md)>

*Implementation of [Ad](../interfaces/ad.md)*

*Defined in [js-miniapp-sdk/src/miniapp.ts:239](https://github.com/rakutentech/js-miniapp/blob/d3d09f7/js-miniapp-sdk/src/miniapp.ts#L239)*

#### Parameters:

Name | Type |
------ | ------ |
`id` | string |

**Returns:** Promise\<[Reward](../interfaces/reward.md)>