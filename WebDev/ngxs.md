# [@ngxs/store](https://github.com/ngxs/store)

* [Action Class](https://github.com/JanMalch/intellij-live-templates/blob/master/WebDev/ngxs.md#action-class)
* [Action Method in Store](https://github.com/JanMalch/intellij-live-templates/blob/master/WebDev/ngxs.md#action-method-in-store)

## Action Class

**Abbreviation:** `ngxsa`

**Description:** Adds a @ngxs Action

**Template text:**
```typescript
export class $ACTION_NAME$ {
  static type = "[$PREFIX$] $ACTION_NAME$";
  constructor(public readonly payload: $PAYLOAD$) {}
}$END$
```
**Edit variables:**

| Name        | Expression | Default value | Skip if defined |
|-------------|------------|---------------|-----------------|
| ACTION_NAME |            |               |                 |
| PREFIX      |            |               |                 |
| PAYLOAD     |            |               |                 |

## Action Method in Store

**Abbreviation:** `ngxsam`

**Description:** Adds a @ngxs Action method for a Store

**Template text:**
```typescript
@Action($ACTION_TYPE$)
$FUN_NAME$({getState, patchState}: StateContext<$STATE_MODEL$>, {payload}: $ACTION_TYPE$) {
    const state = getState();

	
    patchState({
    
    });
}$END$
```

**Edit variables:**

| Name        | Expression             | Default value | Skip if defined    |
|-------------|------------------------|---------------|--------------------|
| ACTION_NAME |                        |               |                    |
| FUN_NAME    | camelCase(ACTION_TYPE) |               | :heavy_check_mark: |
| STATE_MODEL |                        |               |                    |
