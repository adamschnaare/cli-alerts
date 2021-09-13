# `cli-alerts`

> Cross-platform CLI alerts with colors & colored symbols for success, info, warning, error.

## Usage

Add to package with npm

```sh
npm i cli-alerts
```

Use in package (ES6)

```js
import alerts from 'cli-alerts'

alerts({
    type: 'success',
    msg: `This is a success message`,
})
```

## Options
- `type`: string - (success, warning, info, error)
- `msg`: string - message for alert
- `name`: string - name for alert
