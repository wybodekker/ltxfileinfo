# ltxfileinfo
|     key | description
|     ---:|:---
|  script | ltxfileinfo - print version information for a LaTeX file
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 2.05
| license | GNU General Public License

ltxfileinfo displays version information for LaTeX files. If no path
information is given, the file is searched using kpsewhich. As an extra,
for developers, the script will (use the --star or --color options)
check the valididity of the \Provides... statement in the files.
The script uses code from Uwe Lück's readprov.sty.
