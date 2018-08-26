# TypeScript

* [Adds nice import paths in tsconfig.json](#tsconfigjson-paths)

## tsconfig.json paths

**Abbreviation:** `a-tsc-paths`

**Description:** Adds nice import paths in tsconfig.json

**Template text:**
```json
"@$DIR$": ["./src/app/$DIR$"],
"@$DIR$/*": ["./src/app/$DIR$/*"]
```

> `./src/app/$DIR$` is for Angular projects.

**Edit variables:**

| Name     | Expression   | Default value | Skip if defined    |
|----------|--------------|---------------|--------------------|
| DIR      |              |               |                    |
