# Meerkat

Meerkat is designed to identify structure variations (SVs) from paired end high throughput sequencing
data. It predicts SVs from discordant read pairs (pairs that mapped to reference genome in unexpected
way). Then it looks for reads that cover the predicted breakpoints junctions (split read support), refines
breakpoints by local alignments and predicts mechanisms that SVs are formed. It is more sensitive,
with remapping of unmapped and partially mapped reads, especially when the insert size of sequencing
library is small (i.e. read lenght of 100bp and insert size is 200bp), since the SV breakpoint has to be
inbetween the paired end reads to form discordant read pair. With discordant read pair, split read
support and some filtering steps, it has low false positive rate. It can also take into account of reads
from repetitive regions (non-uniquely mapped), combine discordant read pair clusters to predict
complex events, and select the most supported and smallest events.
