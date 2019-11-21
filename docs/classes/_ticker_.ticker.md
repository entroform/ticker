[@nekobird/ticker](../README.md) › [Globals](../globals.md) › ["ticker"](../modules/_ticker_.md) › [Ticker](_ticker_.ticker.md)

# Class: Ticker

## Hierarchy

* **Ticker**

## Index

### Constructors

* [constructor](_ticker_.ticker.md#constructor)

### Properties

* [callback](_ticker_.ticker.md#optional-callback)
* [config](_ticker_.ticker.md#config)
* [isActive](_ticker_.ticker.md#isactive)
* [progress](_ticker_.ticker.md#progress)
* [progressIterationCount](_ticker_.ticker.md#progressiterationcount)
* [progressTimeStart](_ticker_.ticker.md#private-progresstimestart)
* [requestAnimationFrameId](_ticker_.ticker.md#private-requestanimationframeid)
* [tickCount](_ticker_.ticker.md#tickcount)
* [timeEnd](_ticker_.ticker.md#timeend)
* [timeStart](_ticker_.ticker.md#timestart)

### Methods

* [continueLoop](_ticker_.ticker.md#private-continueloop)
* [loop](_ticker_.ticker.md#private-loop)
* [setConfig](_ticker_.ticker.md#setconfig)
* [start](_ticker_.ticker.md#start)
* [stop](_ticker_.ticker.md#stop)
* [updateProgress](_ticker_.ticker.md#private-updateprogress)

## Constructors

###  constructor

\+ **new Ticker**(`config`: Partial‹[TickerConfig](../interfaces/_config_.tickerconfig.md)›): *[Ticker](_ticker_.ticker.md)*

Defined in ticker.ts:20

**Parameters:**

Name | Type |
------ | ------ |
`config` | Partial‹[TickerConfig](../interfaces/_config_.tickerconfig.md)› |

**Returns:** *[Ticker](_ticker_.ticker.md)*

## Properties

### `Optional` callback

• **callback**? : *Function*

Defined in ticker.ts:19

___

###  config

• **config**: *[TickerConfig](../interfaces/_config_.tickerconfig.md)*

Defined in ticker.ts:7

___

###  isActive

• **isActive**: *boolean* = false

Defined in ticker.ts:9

___

###  progress

• **progress**: *number* = 0

Defined in ticker.ts:14

___

###  progressIterationCount

• **progressIterationCount**: *number* = 0

Defined in ticker.ts:16

___

### `Private` progressTimeStart

• **progressTimeStart**: *number* = 0

Defined in ticker.ts:13

___

### `Private` requestAnimationFrameId

• **requestAnimationFrameId**: *number | null* =  null

Defined in ticker.ts:20

___

###  tickCount

• **tickCount**: *number* = 0

Defined in ticker.ts:17

___

###  timeEnd

• **timeEnd**: *number* = 0

Defined in ticker.ts:11

___

###  timeStart

• **timeStart**: *number* = 0

Defined in ticker.ts:10

## Methods

### `Private` continueLoop

▸ **continueLoop**(): *void*

Defined in ticker.ts:96

**Returns:** *void*

___

### `Private` loop

▸ **loop**(): *void*

Defined in ticker.ts:68

**Returns:** *void*

___

###  setConfig

▸ **setConfig**(`config`: Partial‹[TickerConfig](../interfaces/_config_.tickerconfig.md)›): *this*

Defined in ticker.ts:28

**Parameters:**

Name | Type |
------ | ------ |
`config` | Partial‹[TickerConfig](../interfaces/_config_.tickerconfig.md)› |

**Returns:** *this*

___

###  start

▸ **start**(): *void*

Defined in ticker.ts:36

**Returns:** *void*

___

###  stop

▸ **stop**(): *void*

Defined in ticker.ts:49

**Returns:** *void*

___

### `Private` updateProgress

▸ **updateProgress**(): *void*

Defined in ticker.ts:106

**Returns:** *void*
