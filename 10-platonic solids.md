up::[[0 - index]]

```dataview
TABLE vertices, edges, faces, faces-type, volume
FROM #polyhedra AND -"template"
WHERE contains(up, this.file.link)
```


