# JS-ToDo

**Abbreviation:** `jstodo`

**Description:** Creates ToDo-comment and console.warn

**Template text:**
```javascript
console.warn('$FILE$, Line $LINE$ // TODO: $TODOTEXT$'); // TODO: $TODOTEXT$ $END$
```

**Edit variables:**

| Name     | Expression   | Default value | Skip if defined    |
|----------|--------------|---------------|--------------------|
| FILE     | fileName()   |               | :heavy_check_mark: |
| LINE     | lineNumber() |               | :heavy_check_mark: |
| TODOTEXT |              |               |                    |
