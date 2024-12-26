sourmash sig cat --picklist SRR606249.1k.gather.csv.gz:match_name:ident /group/ctbrowngrp/sourmash-db/gtdb-rs220/gtdb-rs220-k31.zip -o SRR606249.1k.matches.zip
sourmash scripts fastgather -s 100_000 -k 31 SRR606249.trim.sig.zip SRR606249.1k.matches.zip -o SRR606249.100k.gather.csv.gz --threshold=0
