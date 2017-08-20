# huge-sort
Sorting utility for huge text files

Usage for trivial sort case:
<pre>$ hsort inputfile.csv outputfile.csv</pre>

Usage for extremally-quick disk space configuration:
<pre>$ hsort inputfile.csv outputfile.csv -d1 /mnt/vol1:/mnt/vol2:/mnt/vol3</pre>

Usage for advanced encoding features:
<pre>$ hsort inputfile.csv outputfile.csv -ienc win1251 -oenc utf-8</pre>
