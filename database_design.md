# Username Group by

Text block 1

```spl
// SPL code block 1
```

# File Extension Group by

Text block 1

```spl
index=mock | stats avg(fileSizeBytes) as avg_fileSizeBytes, count by fileExtension | outputcsv [| stats count | eval filename = "file_extensions_" . strftime(now(), "%s") . ".csv" | return $filename ]
```

# File Name Group by

Text block 1

```spl
// SPL code block 1
```

# Header 1

Text block 1

```spl
// SPL code block 1
```

# Big Join

Text block 1

```spl
// SPL code block 1
```

