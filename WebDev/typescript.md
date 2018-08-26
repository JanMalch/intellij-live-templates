# TypeScript

* [Add top level directory to tsconfig paths](https://github.com/JanMalch/intellij-live-templates/blob/master/WebDev/ngxs.md#action-class)

## tsconfig.json paths

**Abbreviation:** `a-tsc-paths`

**Description:** Adds nice import paths in tsconfig.json

**Template text:**
```json
"@$DIR$": ["./src/app/$DIR$"],
"@$DIR$/*": ["./src/app/$DIR$/*"]
```

**Edit variables:**

| Name     | Expression   | Default value | Skip if defined    |
|----------|--------------|---------------|--------------------|
| DIR      |              |               |                    |

> `./src/app/$DIR$` is for Angular projects.