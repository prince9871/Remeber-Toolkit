# Remember-Toolkit

## Useful for changing the default React port by making changes in your `package.json` file.

```json
"scripts": {
  "start": "set PORT=5001 && react-scripts start",
  "build": "react-scripts build",
  "test": "react-scripts test",
  "eject": "react-scripts eject"
}
