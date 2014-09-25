D1
==

If you want a quick way to filter out columns - look at the LMG-table.heading file
check what row number the attributes you are interested in is e.g 3,45 ( gene_name_GM3,
 longest_hmr_len_NT_LMG ) then open up the terminal/console and use the command:

```
 cut -f 3,45 LMG-table.headings > LMR-table-rows.12.15.tsv
```

Now you have just those columns in a table ( LMR-table-rows.12.15.tsv )
