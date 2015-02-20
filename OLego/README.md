# OLego

OLego is a program specifically designed for de novo spliced mapping of mRNA-seq reads. OLego adopts a seeding and extension scheme, and does not rely on a separate external mapper. It achieves high sensitivity of junction detection by using very small seeds (12-14 nt), efficiently mapped using Burrows-Wheeler transform (BWT) and FM-index. This also makes it particularly sensitive for discovering small exons. It is implemented in C++ with full support of multiple threading, to allow fast processing of large-scale data.
