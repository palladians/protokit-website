---
title: TransitionMethodExecutionContext
---

[**@proto-kit/protocol**](../README.md)

***

[Documentation](../../../README.md) / [@proto-kit/protocol](../README.md) / TransitionMethodExecutionContext

# Interface: TransitionMethodExecutionContext

Defined in: [packages/protocol/src/state/context/TransitionMethodExecutionContext.ts:7](https://github.com/proto-kit/framework/blob/28efa802e3737fc3b77339148b307ef7246f3ef1/packages/protocol/src/state/context/TransitionMethodExecutionContext.ts#L7)

## Properties

### addStateTransition()

> **addStateTransition**: \<`Value`\>(`stateTransition`) => `void`

Defined in: [packages/protocol/src/state/context/TransitionMethodExecutionContext.ts:12](https://github.com/proto-kit/framework/blob/28efa802e3737fc3b77339148b307ef7246f3ef1/packages/protocol/src/state/context/TransitionMethodExecutionContext.ts#L12)

Adds an in-method generated state transition to the current context

#### Type Parameters

• **Value**

#### Parameters

##### stateTransition

[`StateTransition`](../classes/StateTransition.md)\<`Value`\>

State transition to add to the context

#### Returns

`void`

***

### clear()

> **clear**: () => `void`

Defined in: [packages/protocol/src/state/context/TransitionMethodExecutionContext.ts:17](https://github.com/proto-kit/framework/blob/28efa802e3737fc3b77339148b307ef7246f3ef1/packages/protocol/src/state/context/TransitionMethodExecutionContext.ts#L17)

Manually clears/resets the execution context

#### Returns

`void`

***

### current()

> **current**: () => `object`

Defined in: [packages/protocol/src/state/context/TransitionMethodExecutionContext.ts:23](https://github.com/proto-kit/framework/blob/28efa802e3737fc3b77339148b307ef7246f3ef1/packages/protocol/src/state/context/TransitionMethodExecutionContext.ts#L23)

Had to override current() otherwise it would not infer
the type of result correctly (parent type would be reused)

#### Returns

`object`

##### result

> **result**: [`TransitionMethodExecutionResult`](../classes/TransitionMethodExecutionResult.md)
