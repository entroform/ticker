[@nekobird/ticker](../README.md) › [Globals](../globals.md) › ["config"](../modules/_config_.md) › [TickerConfig](_config_.tickerconfig.md)

# Interface: TickerConfig

## Hierarchy

* **TickerConfig**

## Index

### Properties

* [durationInSeconds](_config_.tickerconfig.md#durationinseconds)
* [loopForever](_config_.tickerconfig.md#loopforever)
* [onComplete](_config_.tickerconfig.md#oncomplete)
* [onStart](_config_.tickerconfig.md#onstart)
* [onTick](_config_.tickerconfig.md#ontick)
* [timingFunction](_config_.tickerconfig.md#timingfunction)

## Properties

###  durationInSeconds

• **durationInSeconds**: *number*

Defined in config.ts:5

___

###  loopForever

• **loopForever**: *boolean*

Defined in config.ts:4

___

###  onComplete

• **onComplete**: *function*

Defined in config.ts:11

#### Type declaration:

▸ (`ticker`: [Ticker](../classes/_config_.ticker.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`ticker` | [Ticker](../classes/_config_.ticker.md) |

___

###  onStart

• **onStart**: *function*

Defined in config.ts:9

#### Type declaration:

▸ (`ticker`: [Ticker](../classes/_config_.ticker.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`ticker` | [Ticker](../classes/_config_.ticker.md) |

___

###  onTick

• **onTick**: *function*

Defined in config.ts:10

#### Type declaration:

▸ (`tick`: [number, number, number], `ticker`: [Ticker](../classes/_config_.ticker.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`tick` | [number, number, number] |
`ticker` | [Ticker](../classes/_config_.ticker.md) |

___

###  timingFunction

• **timingFunction**: *function*

Defined in config.ts:7

#### Type declaration:

▸ (`t`: number): *number*

**Parameters:**

Name | Type |
------ | ------ |
`t` | number |
