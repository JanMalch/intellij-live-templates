# console.log

**Abbreviation:** `cl`

**Description:** inserts console.log("") with current position

**Template text:**
```javascript
console.log('Class: $CLASS$, Function: $FUNCTION$, Line $LINE$ $PARAM_TEXT$($EXPECTED$): '
, $PARAM$);$END$
```

**Edit variables:**

| Name       | Expression     | Default value | Skip if defined    |
|------------|----------------|---------------|--------------------|
| CLASS      | jsClassName()  |               | :heavy_check_mark: |
| FUNCTION   | jsMethodName() |               | :heavy_check_mark: |
| LINE       | lineNumber()   |               | :heavy_check_mark: |
| PARAM      |                |               |                    |
| PARAM_TEXT |                | PARAM         |                    |
| EXPECTED   |                |               |                    |
