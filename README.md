D1
==

If you want a quick way to filter out columns - 
Look at the LMG-table.heading file check what row number the attributes you are 
interested in are - e.g 3,45 ( gene_name_GM3, longest_hmr_len_NT_LMG ) then open 
up the terminal/console and use the command:

```
 cut -f 3,45 LMG-table.tsv > LMR-table-cols.3.45.tsv
```

Now you have just those columns in a table ( LMR-table-rows.3.45.tsv )
