# Code Block
## inline
`<h1>This is heading one</h1>`
## block
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>

```
## Highlight
### Html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>

```
### Javascript
```javascript
export const errFormatter =  (message) => {
  let errors = {}
  const allErr = message.substring(message.indexOf(':') + 1).trim()
  const errArray = allErr.split(',').map(e => e.trim())
  errArray.forEach(e => {
    const [key,value] = e.split(':').map(e => e.trim())
    errors [key] = value
  })
  return errors
}

```
