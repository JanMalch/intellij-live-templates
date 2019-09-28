# Angular

* [Add dependency in constructor](#add-dependency)
* [Inject `document` reference`](#inject-document)

## Add dependency

**Abbreviation:** `a-dep`

**Description:** Adds a dependency in the constructor

**Template text:**
```typescript
private $VAR$: $CLASS$
```
**Edit variables:**

| Name  | Expression       | Default value | Skip if defined    |
|-------|------------------|---------------|--------------------|
| CLASS |                  |               |                    |
| VAR   | camelCase(CLASS) |               | :heavy_check_mark: |


## Inject `document`

**Abbreviation:** `a-doc`

**Description:** Inject document as dependency in the constructor

**Template text:**
```typescript
@Inject(DOCUMENT) private document: Document
```
