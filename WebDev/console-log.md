# `console.log`

* [`console.log` with param as text](#consolelog-with-param-as-text)
* [`console.log` with position in file](#consolelog-with-position-in-file)

## `console.log` with param as text

**Abbreviation:** `cl`

**Description:** inserts console.log("") with param as text

**Template text:**
```javascript
console.log('$PARAM_TEXT$:', $PARAM$);$END$
```

**Edit variables:**

| Name       | Expression     | Default value | Skip if defined    |
|------------|----------------|---------------|--------------------|
| PARAM      |                |               |                    |
| PARAM_TEXT |                | PARAM         | :heavy_check_mark: |


## `console.log` with position in file

**Abbreviation:** `cll`

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
| PARAM_TEXT |                | PARAM         | :heavy_check_mark: |
| EXPECTED   |                |               |                    |

**Credit:** [Intellij Live template for console.log(‘’) that will improve your daily development life!](https://medium.com/netscape/intellij-live-template-for-console-log-that-will-improve-your-daily-development-life-ef1320a8fe81)
