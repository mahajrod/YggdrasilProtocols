# Table "ID relations"

| Field             | Type                      | Template                      | Description                                         |
|-------------------|---------------------------|-------------------------------|-----------------------------------------------------|
| YGG Project ID    | single line text          | **YGG**XXX                    | ID of the yggdrasil project                         |
| Latin name        | single line text          | Genus species                 | Latin name of the species                           |
| Common name       | single line text          | string                        | Common name of the species                          |
| YGG Individual ID | single line text          | **YGG**XXX<b>.IND</b>WW       | ID of the individual                                |
| ToLID             | single line text          | nGenSpiD OR nnGenSpiD         | Tree of Life ID of the individual                   |
| VGP Individual ID | single line text          | YGG-nGenSpiD OR YGG-nnGenSpiD | ID of the individual in VGP database. "YGG-"+ToLID  |
| YGG Sample ID     | single line text          |                               | ID of the sample                                    |
| YGG Product type  | single select<sup>*</sup> |                               | Type of the product                                 |
| YGG Product ID    | single line text          |                               | ID of the product                                   |

<sup>*</sup> "DNA extract" OR "RNA extract" OR "HiC crosslinking" OR "HiC reaction" OR "HIFI library" OR
"HiC library" OR "Illumina library" OR "Nanopore library" OR "RNA library"

