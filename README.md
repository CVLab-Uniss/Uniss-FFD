# Uniss-FFD Facial Fixation Dataset 

This dataset contains 2398 files containing fixations calculated from human gazes over a selection of images from the Karolinska Directed Emotional Faces (KDEF) dataset.

Any work which uses Uniss-FFD must reference the paper: [Exploring attention on faces: similarities between humans and Transformers](https://ieeexplore.ieee.org/document/9959705) 

```
@inproceedings{cadoni2022exploring,
  title={Exploring attention on faces: similarities between humans and Transformers},
  author={Cadoni, Marinella and Nixon, Seth and Lagorio, Andrea and Fadda, Mauro},
  booktitle={2022 18th IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS)},
  pages={1--8},
  year={2022},
  organization={IEEE}
}
```

To view the KDEF images you will need to [obtain the KDEF dataset separately](https://www.kdef.se/).

## Naming convention 

{OBSERVER INDEX}\_{IMAGE INDEX}\_{MEDIA EXPRESSION}\_{MEDIA GENDER}\_{OBSERVER GENDER}.csv

## File Contents 

Each file contains a list of fixations where each row is a single fixation and the columns correspond to: Fixation Index, X, Y, Time Stamp

## Image Index Lookup 

The images have been indexed to preserve file-name length. The indicies with the corresponding images are found below.<br>  

| Index | File 	| Index | File 	| Index | File 	|
|--------------:	|:---	|--------------:	|:---	|--------------:	|:---	|
| 000 	| AF09SAS.JPG 	| 040 	| AF07NES.JPG 	| 080 	| AM25HAS.JPG 	|
| 001 	| AM14SAS.JPG 	| 041 	| AM14NES.JPG 	| 081 	| AM04SAS.JPG 	|
| 002 	| AM02SAS.JPG 	| 042 	| AF09HAS.JPG 	| 082 	| AM26HAS.JPG 	|
| 003 	| AM02HAS.JPG 	| 043 	| AM01HAS.JPG 	| 083 	| AF02HAS.JPG 	|
| 004 	| AM04HAS.JPG 	| 044 	| AM02NES.JPG 	| 084 	| AF16SAS.JPG 	|
| 005 	| AM21HAS.JPG 	| 045 	| AF12SAS.JPG 	| 085 	| AF19NES.JPG 	|
| 006 	| AM09HAS.JPG 	| 046 	| AM23HAS.JPG 	| 086 	| AF14HAS.JPG 	|
| 007 	| AF11NES.JPG 	| 047 	| AM11SAS.JPG 	| 087 	| AF05HAS.JPG 	|
| 008 	| AF16HAS.JPG 	| 048 	| AM06NES.JPG 	| 088 	| AM08HAS.JPG 	|
| 009 	| AF22NES.JPG 	| 049 	| AM17SAS.JPG 	| 089 	| AF02NES.JPG 	|
| 010 	| AM15SAS.JPG 	| 050 	| AF17SAS.JPG 	| 090 	| AF04SAS.JPG 	|
| 011 	| AM09NES.JPG 	| 051 	| AF03SAS.JPG 	| 091 	| AF19SAS.JPG 	|
| 012 	| AF01SAS.JPG 	| 052 	| AM05SAS.JPG 	| 092 	| AM05NES.JPG 	|
| 013 	| AF21HAS.JPG 	| 053 	| AF02SAS.JPG 	| 093 	| AF14NES.JPG 	|
| 014 	| AM09SAS.JPG 	| 054 	| AF15NES.JPG 	| 094 	| AF20HAS.JPG 	|
| 015 	| AF05SAS.JPG 	| 055 	| AF10SAS.JPG 	| 095 	| AM15HAS.JPG 	|
| 016 	| AM15NES.JPG 	| 056 	| AF16NES.JPG 	| 096 	| AM18SAS.JPG 	|
| 017 	| AF13SAS.JPG 	| 057 	| AM05HAS.JPG 	| 097 	| AF01NES.JPG 	|
| 018 	| AF01HAS.JPG 	| 058 	| AM13SAS.JPG 	| 098 	| AM18NES.JPG 	|
| 019 	| AF05NES.JPG 	| 059 	| AF20SAS.JPG 	| 099 	| AM13HAS.JPG 	|
| 020 	| AM17NES.JPG 	| 060 	| AM22NES.JPG 	| 100 	| AF06SAS.JPG 	|
| 021 	| AM26SAS.JPG 	| 061 	| AF04HAS.JPG 	| 101 	| AM07NES.JPG 	|
| 022 	| AF17NES.JPG 	| 062 	| AM07SAS.JPG 	| 102 	| AM08NES.JPG 	|
| 023 	| AF17HAS.JPG 	| 063 	| AM25SAS.JPG 	| 103 	| AM06HAS.JPG 	|
| 024 	| AF09NES.JPG 	| 064 	| AF06NES.JPG 	| 104 	| AM22SAS.JPG 	|
| 025 	| AF03HAS.JPG 	| 065 	| AF11HAS.JPG 	| 105 	| AM11HAS.JPG 	|
| 026 	| AF07SAS.JPG 	| 066 	| AM08SAS.JPG 	| 106 	| AM04NES.JPG 	|
| 027 	| AM14HAS.JPG 	| 067 	| AF15HAS.JPG 	| 107 	| AM01SAS.JPG 	|
| 028 	| AF22HAS.JPG 	| 068 	| AF04NES.JPG 	| 108 	| AF13NES.JPG 	|
| 029 	| AM21SAS.JPG 	| 069 	| AM10SAS.JPG 	| 109 	| AM13NES.JPG 	|
| 030 	| AF20NES.JPG 	| 070 	| AF22SAS.JPG 	| 110 	| AF21SAS.JPG 	|
| 031 	| AM01NES.JPG 	| 071 	| AM10NES.JPG 	| 111 	| AM23NES.JPG 	|
| 032 	| AF10NES.JPG 	| 072 	| AF11SAS.JPG 	| 112 	| AM22HAS.JPG 	|
| 033 	| AM10HAS.JPG 	| 073 	| AM07HAS.JPG 	| 113 	| AM18HAS.JPG 	|
| 034 	| AM23SAS.JPG 	| 074 	| AF06HAS.JPG 	| 114 	| AF12NES.JPG 	|
| 035 	| AM11NES.JPG 	| 075 	| AF15SAS.JPG 	| 115 	| AF19HAS.JPG 	|
| 036 	| AF03NES.JPG 	| 076 	| AF21NES.JPG 	| 116 	| AF13HAS.JPG 	|
| 037 	| AM17HAS.JPG 	| 077 	| AM25NES.JPG 	| 117 	| AF07HAS.JPG 	|
| 038 	| AM06SAS.JPG 	| 078 	| AM21NES.JPG 	| 118 	| AF10HAS.JPG 	|
| 039 	| AF14SAS.JPG 	| 079 	| AM26NES.JPG 	| 119 	| AF12HAS.JPG 	|
