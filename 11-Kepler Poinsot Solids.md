up::[[0 - index]]

```dataview
TABLE vertices, edges, faces, faces-type, volume, dihedral-angle
FROM #polyhedra AND -"template"
WHERE contains(up, this.file.link)
```

