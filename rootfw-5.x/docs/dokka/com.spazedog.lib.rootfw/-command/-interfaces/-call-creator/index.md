[com.spazedog.lib.rootfw](../../../index.md) / [Command](../../index.md) / [Interfaces](../index.md) / [CallCreator](.)

# CallCreator

`interface CallCreator`

Can be used with [Command.addCall](../../add-call.md) to create custom [Call](../../-containers/-call/index.md) instances
for each registered all-in-one binary

### Functions

| Name | Summary |
|---|---|
| [onCreateCall](on-create-call.md) | `abstract fun onCreateCall(bin: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Call`](../../-containers/-call/index.md)`?`<br>Called by [Command.addCall](../../add-call.md) for each all-in-one binaries to create a call for |
