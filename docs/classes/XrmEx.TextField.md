[xrm-ex](../README.md) / [Exports](../modules.md) / [XrmEx](../modules/XrmEx.md) / TextField

# Class: TextField

[XrmEx](../modules/XrmEx.md).TextField

Used to execute methods related to a single Attribute

## Hierarchy

- [`Field`](XrmEx.Field.md)

  ↳ **`TextField`**

## Implements

- `StringAttribute`

## Table of contents

### Constructors

- [constructor](XrmEx.TextField.md#constructor)

### Properties

- [Name](XrmEx.TextField.md#name)
- [\_attribute](XrmEx.TextField.md#_attribute)
- [allFields](XrmEx.TextField.md#allfields)

### Accessors

- [Attribute](XrmEx.TextField.md#attribute)
- [Value](XrmEx.TextField.md#value)
- [controls](XrmEx.TextField.md#controls)

### Methods

- [addNotification](XrmEx.TextField.md#addnotification)
- [addOnChange](XrmEx.TextField.md#addonchange)
- [fireOnChange](XrmEx.TextField.md#fireonchange)
- [getAttributeType](XrmEx.TextField.md#getattributetype)
- [getFormat](XrmEx.TextField.md#getformat)
- [getIsDirty](XrmEx.TextField.md#getisdirty)
- [getMaxLength](XrmEx.TextField.md#getmaxlength)
- [getName](XrmEx.TextField.md#getname)
- [getParent](XrmEx.TextField.md#getparent)
- [getRequiredLevel](XrmEx.TextField.md#getrequiredlevel)
- [getSubmitMode](XrmEx.TextField.md#getsubmitmode)
- [getUserPrivilege](XrmEx.TextField.md#getuserprivilege)
- [getValue](XrmEx.TextField.md#getvalue)
- [removeNotification](XrmEx.TextField.md#removenotification)
- [removeOnChange](XrmEx.TextField.md#removeonchange)
- [setDisabled](XrmEx.TextField.md#setdisabled)
- [setIsValid](XrmEx.TextField.md#setisvalid)
- [setNotification](XrmEx.TextField.md#setnotification)
- [setRequired](XrmEx.TextField.md#setrequired)
- [setRequiredLevel](XrmEx.TextField.md#setrequiredlevel)
- [setSubmitMode](XrmEx.TextField.md#setsubmitmode)
- [setValue](XrmEx.TextField.md#setvalue)
- [setVisible](XrmEx.TextField.md#setvisible)

## Constructors

### constructor

• **new TextField**(`attribute`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |

#### Overrides

[Field](XrmEx.Field.md).[constructor](XrmEx.Field.md#constructor)

#### Defined in

[XrmEx.ts:825](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L825)

## Properties

### Name

• `Readonly` **Name**: `string`

#### Inherited from

[Field](XrmEx.Field.md).[Name](XrmEx.Field.md#name)

#### Defined in

[XrmEx.ts:584](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L584)

___

### \_attribute

• `Protected` **\_attribute**: `StringAttribute`

#### Overrides

[Field](XrmEx.Field.md).[_attribute](XrmEx.Field.md#_attribute)

#### Defined in

[XrmEx.ts:824](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L824)

___

### allFields

▪ `Static` **allFields**: [`Field`](XrmEx.Field.md)[] = `[]`

#### Inherited from

[Field](XrmEx.Field.md).[allFields](XrmEx.Field.md#allfields)

#### Defined in

[XrmEx.ts:582](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L582)

## Accessors

### Attribute

• `get` **Attribute**(): `StringAttribute`

#### Returns

`StringAttribute`

#### Overrides

Field.Attribute

#### Defined in

[XrmEx.ts:834](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L834)

___

### Value

• `get` **Value**(): `string`

Gets the value.

#### Returns

`string`

The value.

#### Overrides

Field.Value

#### Defined in

[XrmEx.ts:842](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L842)

• `set` **Value**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`void`

#### Overrides

Field.Value

#### Defined in

[XrmEx.ts:845](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L845)

___

### controls

• `get` **controls**(): `ItemCollection`<`StringControl`\>

#### Returns

`ItemCollection`<`StringControl`\>

#### Implementation of

Xrm.Attributes.StringAttribute.controls

#### Overrides

Field.controls

#### Defined in

[XrmEx.ts:839](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L839)

## Methods

### addNotification

▸ **addNotification**(`message`, `notificationLevel`, `uniqueId`, `actions?`): [`TextField`](XrmEx.TextField.md)

Displays an error or recommendation notification for a control, and lets you specify actions to execute based on the notification.

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `notificationLevel` | ``"ERROR"`` \| ``"RECOMMENDATION"`` |
| `uniqueId` | `string` |
| `actions?` | `ControlNotificationAction`[] |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Inherited from

[Field](XrmEx.Field.md).[addNotification](XrmEx.Field.md#addnotification)

#### Defined in

[XrmEx.ts:778](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L778)

___

### addOnChange

▸ **addOnChange**(`handlers`): [`TextField`](XrmEx.TextField.md)

Adds a handler or an array of handlers to be called when the attribute's value is changed.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `handlers` | `ContextSensitiveHandler` \| `ContextSensitiveHandler`[] | The function reference or an array of function references. |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Implementation of

Xrm.Attributes.StringAttribute.addOnChange

#### Inherited from

[Field](XrmEx.Field.md).[addOnChange](XrmEx.Field.md#addonchange)

#### Defined in

[XrmEx.ts:750](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L750)

___

### fireOnChange

▸ **fireOnChange**(): [`TextField`](XrmEx.TextField.md)

Fire all "on change" event handlers.

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Implementation of

Xrm.Attributes.StringAttribute.fireOnChange

#### Inherited from

[Field](XrmEx.Field.md).[fireOnChange](XrmEx.Field.md#fireonchange)

#### Defined in

[XrmEx.ts:737](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L737)

___

### getAttributeType

▸ **getAttributeType**(): `AttributeType`

#### Returns

`AttributeType`

#### Implementation of

Xrm.Attributes.StringAttribute.getAttributeType

#### Inherited from

[Field](XrmEx.Field.md).[getAttributeType](XrmEx.Field.md#getattributetype)

#### Defined in

[XrmEx.ts:600](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L600)

___

### getFormat

▸ **getFormat**(): `StringAttributeFormat`

#### Returns

`StringAttributeFormat`

#### Implementation of

Xrm.Attributes.StringAttribute.getFormat

#### Overrides

[Field](XrmEx.Field.md).[getFormat](XrmEx.Field.md#getformat)

#### Defined in

[XrmEx.ts:831](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L831)

___

### getIsDirty

▸ **getIsDirty**(): `boolean`

#### Returns

`boolean`

#### Implementation of

Xrm.Attributes.StringAttribute.getIsDirty

#### Inherited from

[Field](XrmEx.Field.md).[getIsDirty](XrmEx.Field.md#getisdirty)

#### Defined in

[XrmEx.ts:606](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L606)

___

### getMaxLength

▸ **getMaxLength**(): `number`

#### Returns

`number`

#### Implementation of

Xrm.Attributes.StringAttribute.getMaxLength

#### Defined in

[XrmEx.ts:828](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L828)

___

### getName

▸ **getName**(): `string`

#### Returns

`string`

#### Implementation of

Xrm.Attributes.StringAttribute.getName

#### Inherited from

[Field](XrmEx.Field.md).[getName](XrmEx.Field.md#getname)

#### Defined in

[XrmEx.ts:609](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L609)

___

### getParent

▸ **getParent**(): `Entity`

#### Returns

`Entity`

#### Implementation of

Xrm.Attributes.StringAttribute.getParent

#### Inherited from

[Field](XrmEx.Field.md).[getParent](XrmEx.Field.md#getparent)

#### Defined in

[XrmEx.ts:612](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L612)

___

### getRequiredLevel

▸ **getRequiredLevel**(): `RequirementLevel`

#### Returns

`RequirementLevel`

#### Implementation of

Xrm.Attributes.StringAttribute.getRequiredLevel

#### Inherited from

[Field](XrmEx.Field.md).[getRequiredLevel](XrmEx.Field.md#getrequiredlevel)

#### Defined in

[XrmEx.ts:615](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L615)

___

### getSubmitMode

▸ **getSubmitMode**(): `SubmitMode`

#### Returns

`SubmitMode`

#### Implementation of

Xrm.Attributes.StringAttribute.getSubmitMode

#### Inherited from

[Field](XrmEx.Field.md).[getSubmitMode](XrmEx.Field.md#getsubmitmode)

#### Defined in

[XrmEx.ts:618](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L618)

___

### getUserPrivilege

▸ **getUserPrivilege**(): `Privilege`

#### Returns

`Privilege`

#### Implementation of

Xrm.Attributes.StringAttribute.getUserPrivilege

#### Inherited from

[Field](XrmEx.Field.md).[getUserPrivilege](XrmEx.Field.md#getuserprivilege)

#### Defined in

[XrmEx.ts:621](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L621)

___

### getValue

▸ **getValue**(): `any`

#### Returns

`any`

#### Implementation of

Xrm.Attributes.StringAttribute.getValue

#### Inherited from

[Field](XrmEx.Field.md).[getValue](XrmEx.Field.md#getvalue)

#### Defined in

[XrmEx.ts:630](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L630)

___

### removeNotification

▸ **removeNotification**(`uniqueId`): [`TextField`](XrmEx.TextField.md)

Clears the notification identified by uniqueId.

**`Remarks`**

If the uniqueId parameter is not used, the current notification shown will be removed.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `uniqueId` | `string` | (Optional) Unique identifier. |

#### Returns

[`TextField`](XrmEx.TextField.md)

true if it succeeds, false if it fails.

#### Inherited from

[Field](XrmEx.Field.md).[removeNotification](XrmEx.Field.md#removenotification)

#### Defined in

[XrmEx.ts:809](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L809)

___

### removeOnChange

▸ **removeOnChange**(`handler`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | `ChangeEventHandler` |

#### Returns

`void`

#### Implementation of

Xrm.Attributes.StringAttribute.removeOnChange

#### Inherited from

[Field](XrmEx.Field.md).[removeOnChange](XrmEx.Field.md#removeonchange)

#### Defined in

[XrmEx.ts:624](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L624)

___

### setDisabled

▸ **setDisabled**(`disabled`): [`TextField`](XrmEx.TextField.md)

Sets the state of the control to either enabled, or disabled.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `disabled` | `boolean` | true to disable, false to enable. |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Inherited from

[Field](XrmEx.Field.md).[setDisabled](XrmEx.Field.md#setdisabled)

#### Defined in

[XrmEx.ts:699](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L699)

___

### setIsValid

▸ **setIsValid**(`isValid`, `message?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `isValid` | `boolean` |
| `message?` | `string` |

#### Returns

`void`

#### Implementation of

Xrm.Attributes.StringAttribute.setIsValid

#### Inherited from

[Field](XrmEx.Field.md).[setIsValid](XrmEx.Field.md#setisvalid)

#### Defined in

[XrmEx.ts:633](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L633)

___

### setNotification

▸ **setNotification**(`message`, `uniqueId`): [`TextField`](XrmEx.TextField.md)

Sets a control-local notification message.

**`Remarks`**

When this method is used on Microsoft Dynamics CRM for tablets a red "X" icon
             appears next to the control. Tapping on the icon will display the message.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message. |
| `uniqueId` | `string` | Unique identifier. |

#### Returns

[`TextField`](XrmEx.TextField.md)

true if it succeeds, false if it fails.

#### Inherited from

[Field](XrmEx.Field.md).[setNotification](XrmEx.Field.md#setnotification)

#### Defined in

[XrmEx.ts:669](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L669)

___

### setRequired

▸ **setRequired**(`required`): [`TextField`](XrmEx.TextField.md)

Sets the required level.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `required` | `boolean` | The requirement level, as either false for "none" or true for "required" |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Inherited from

[Field](XrmEx.Field.md).[setRequired](XrmEx.Field.md#setrequired)

#### Defined in

[XrmEx.ts:727](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L727)

___

### setRequiredLevel

▸ **setRequiredLevel**(`requirementLevel`): [`TextField`](XrmEx.TextField.md)

Sets the required level.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `requirementLevel` | `RequirementLevel` | The requirement level, as either "none", "required", or "recommended" |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Implementation of

Xrm.Attributes.StringAttribute.setRequiredLevel

#### Inherited from

[Field](XrmEx.Field.md).[setRequiredLevel](XrmEx.Field.md#setrequiredlevel)

#### Defined in

[XrmEx.ts:712](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L712)

___

### setSubmitMode

▸ **setSubmitMode**(`submitMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `submitMode` | `SubmitMode` |

#### Returns

`void`

#### Implementation of

Xrm.Attributes.StringAttribute.setSubmitMode

#### Inherited from

[Field](XrmEx.Field.md).[setSubmitMode](XrmEx.Field.md#setsubmitmode)

#### Defined in

[XrmEx.ts:627](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L627)

___

### setValue

▸ **setValue**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`void`

#### Implementation of

Xrm.Attributes.StringAttribute.setValue

#### Inherited from

[Field](XrmEx.Field.md).[setValue](XrmEx.Field.md#setvalue)

#### Defined in

[XrmEx.ts:597](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L597)

___

### setVisible

▸ **setVisible**(`visible`): [`TextField`](XrmEx.TextField.md)

Sets the visibility state.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `visible` | `boolean` | true to show, false to hide. |

#### Returns

[`TextField`](XrmEx.TextField.md)

#### Inherited from

[Field](XrmEx.Field.md).[setVisible](XrmEx.Field.md#setvisible)

#### Defined in

[XrmEx.ts:686](https://github.com/AhashSritharan/Xrm-Ex/blob/d65bc4b/src/XrmEx.ts#L686)
