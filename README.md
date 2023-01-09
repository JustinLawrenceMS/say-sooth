<h1>SaySooth quick console script</h1>

This script came about because curling the sooth from SoothSayerAPI
did pull a linebreak at the end, which on Linux, left the prompt
at the end of the sooth.  All this script does is pull the sooth
and enter a line break at the end.

<h3>To install:</h3>

```git clone https://github.com/JustinLawrenceMS/say-sooth.git```

Then make the script executable:

```chmod 755 say-sooth```

<h3>To use it:</h3>

```./sooth```

or with cowsay:

```./sooth | cowsay```
