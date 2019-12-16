$ cat auction-table.md
| PLACE | PERCENTAGE |
|:-----:|:----------:|
|  1st  |     50     |
|  2nd  |     25     |
|  3rd  |    12,5    |
|  4th  |    6,25    |
|  5th  |    3,125   |
$ cat custom.css
td, th {
    border: 1px solid grey
}
$ markdown-pdf --css-path='custom.css' auction-table.md

