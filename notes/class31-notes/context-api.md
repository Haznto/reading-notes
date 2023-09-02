# Context-API

## Choosing the State Structure

***Summarize the five principles for structuring state.***

**Group related state.**
 >=> if two indicators are changing at the same process time, don't make two states, just make one that will update both

**Avoid contradictions in state.**
 >=> if there is two states which are linked together aren't handled correctly in calling their set functions, they will affect each state of each others resulting in unexpected outputs.(focus on the ordering of calls).

**Avoid redundant state.**
 >=> if you have x state and y state, that could be used to come up with c state, don't make a new c state but rely on the existant states already.

**Avoid duplication in state.**
 >=> duplication in using states could lead you to fail updating the targeted values or overwrite the updated value you want to change with the previous state.

**Avoid deeply nested state.**
 >=> nesting states in each others will make the process harder on you to update these states since to access nested states you have to access the whole parent structure than contains these states to update it whole.

**What problem do Contexts aim to solve?**

> "Prop drilling"  due to "lifting state up".

**What is one technique to try before useContext?**

 >"Prop drilling" but it's verbose and takes time, so that's why contexts came up, to avoid fixing the issue with such long method.

**What hook complements useContext for complex applications?**
> useReducer() , others also could be used.
