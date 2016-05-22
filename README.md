# client-side-csv-download

downloads csv string as file on the client-side

## install

```bash
npm i --save client-side-csv-download
```

## usage

```js
import downloadCSV from 'client-side-csv-download'
import toCSV from 'array-to-csv'

var csvString = toCSV(
  ['words', 'count'],
  ['aut', 2],
  ['fugit', 3]
)

downloadCSV({
  csvString: csvString,
  filename: 'histogram' // downloads histogram.csv
})
```
