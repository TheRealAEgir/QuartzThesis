Priming of TRM using a vaccination with peptide-Ab anti CLEC9A with CpG confered high liver TRM number than with poly(I:C) [[Fernandez-Ruiz_Immunity_2016]].
Dans les tumeurs HGSOC, les Trecirc co-localisent avec les DC CLEC9A, mais pas les TRM [[Anadon_CancerCell_2022]].
En triant et en transferant des lymphocytes T effecteurs de la rate, ou des mLN et iLN, il a été observé que les lymphocytes provenant des mLN sont recrutés plus facilement dans les intestins, en accord avec d'autres observations précédantes [[Masopust_JExpMed_2010]]. Ce résultat suggère que le lieu d'activation peut influencer la différenciation des TRM par rapport à leur localisation. Cependant, la majorité des TRM dans les intestins semblent provenir tout de même de la rate où le nombre de lymphocytes T effecteur est largement supérieur [[Masopust_JExpMed_2010]].
## List of used references
```dataview
LIST
FLATTEN file.outlinks AS outlink
WHERE file.link = this.file.link AND contains(outlink.file.outlinks, this.file.link)
GROUP BY outlink
```
## List of references still to be used
```dataview
LIST
FROM ""
WHERE contains(file.outlinks, this.file.link) AND !contains(this.file.outlinks, file.link)
```