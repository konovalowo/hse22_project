# hse22_project

Ссылка на колаб: https://colab.research.google.com/drive/15kIt3XCkuezVBY7Ht1MksTW0pClhRFQ2?usp=sharing

## Геномы
||Название          |длина генома|# последовательностей|общая длина|# генов|% генов            |# экзонов|% экзонов          |# zh-score>=500|общая длина zx-score>=500|
|------|------------------|------------|---------------------|-----------|-------|-------------------|---------|-------------------|---------------|-------------------------|
|0     |Alternaria atra   |40101358    |115196               |78177382.0 |12172  |0.2770644325810612 |33185    |0.31097989250139607|132920         |1309714                  |
|1     |Alternaria rosae  |34254606    |117321               |84993594.0 |12727  |0.29572966041413523|33784    |0.384979526548926  |139812         |1380160                  |
|2     |Ogataea angusta   |9015136     |34188                |30596185.0 |5442   |0.36854762923155016|6225     |0.41821598698011875|28353          |280678                   |
|3     |Ogataea haglerorum|8985079     |34064                |30377204.0 |5407   |0.3414852557222925 |6230     |0.3963512173905204 |28766          |284678                   |
|4     |Ogataea polymorpha|9086554     |32670                |37588682.0 |5233   |0.48286743247220015|6277     |0.5158526543726037 |21991          |217016   

## Кластеры

Всего 11778 кластеров. 

Гистограмма кластеров по кол-ву разных геномов в кластере:

![image](https://user-images.githubusercontent.com/20297250/173402296-76eea744-91ef-4411-a6ae-a71f98f11b6e.png)

Таблица с информацией о кластерах:

||кластер                      |геном |ген                                          |функция                                         |средний Z-DNA score|
|------|-----------------------------|------|---------------------------------------------|------------------------------------------------|-------------------|
|0     |0                            |Alternaria atra|ALTATR162_LOCUS649                           |uncharacterized protein                         |3781.221476666667  |
|1     |0                            |Alternaria rosae|BKA58DRAFT_407020                            |RNA methyltransferase                           |3852.482018367346  |
|2     |0                            |Ogataea angusta|KL928_000227                                 |uncharacterized protein                         |5875.221131250002  |
|3     |0                            |Ogataea haglerorum|KL911_005160                                 |uncharacterized protein                         |14294.410041379304 |
|4     |0                            |Ogataea polymorpha|OGAPODRAFT_83789                             |uncharacterized protein                         |1909.5564200000001 |
|5     |1                            |Alternaria atra|ALTATR162_LOCUS157                           |uncharacterized protein                         |9010.344796551724  |
|6     |1                            |Alternaria rosae|BKA58DRAFT_444733                            |uncharacterized protein                         |2040.730026415095  |
|7     |1                            |Ogataea angusta|KL928_000859                                 |uncharacterized protein                         |2823.300974074074  |
|8     |1                            |Ogataea haglerorum|KL911_000617                                 |uncharacterized protein                         |9387.109191666666  |
|9     |1                            |Ogataea polymorpha|OGAPODRAFT_23093                             |uncharacterized protein                         |5000.0563          |
|10    |2                            |Alternaria atra|ALTATR162_LOCUS8756                          |uncharacterized protein                         |1799.357008695652  |
|11    |2                            |Alternaria rosae|BKA58DRAFT_327004                            |major facilitator superfamily domain-containing |2983.3061604651166 |
|12    |2                            |Alternaria rosae|BKA58DRAFT_309974                            |major facilitator superfamily domain-containing |8914.826777272729  |
|13    |2                            |Ogataea angusta|KL928_001354                                 |uncharacterized protein                         |1633.1840499999998 |
|14    |2                            |Ogataea haglerorum|KL911_001104                                 |uncharacterized protein                         |9099.012533333333  |
|15    |2                            |Ogataea polymorpha|OGAPODRAFT_92829                             |uncharacterized protein                         |1531.0198363636364 |
|16    |3                            |Alternaria atra|ALTATR162_LOCUS1830                          |uncharacterized protein                         |1202.8271333333334 |
|17    |3                            |Alternaria rosae|BKA58DRAFT_439012                            |uncharacterized protein                         |6509.8649428571425 |
|18    |3                            |Ogataea angusta|KL928_002523                                 |uncharacterized protein                         |5618.46594         |
|19    |3                            |Ogataea haglerorum|KL911_004900                                 |uncharacterized protein                         |3049.0412241379317 |
|20    |3                            |Ogataea polymorpha|OGAPODRAFT_24140                             |uncharacterized protein                         |1257.10615         |
|21    |4                            |Alternaria atra|ALTATR162_LOCUS11881                         |uncharacterized protein                         |3094.59854375      |
|22    |4                            |Alternaria rosae|BKA58DRAFT_441672                            |PIG-X                                           |1294.0666958333336 |
|23    |4                            |Ogataea angusta|KL928_004655                                 |uncharacterized protein                         |4901.741257142858  |
|24    |4                            |Ogataea haglerorum|KL911_004053                                 |uncharacterized protein                         |3935.957921428571  |
|25    |4                            |Ogataea polymorpha|OGAPODRAFT_93788                             |uncharacterized protein                         |2070.569944444444  |
|26    |5                            |Alternaria atra|ALTATR162_LOCUS11753                         |uncharacterized protein                         |5576.405312903227  |
|27    |5                            |Alternaria rosae|BKA58DRAFT_319098                            |nucleoside phosphorylase domain-containing      |3116.8529166666667 |
|28    |5                            |Ogataea angusta|KL928_002765                                 |uncharacterized protein                         |1060.6132266666668 |
|29    |5                            |Ogataea haglerorum|KL911_001681                                 |uncharacterized protein                         |3310.0541086956528 |
|30    |5                            |Ogataea polymorpha|OGAPODRAFT_76560                             |uncharacterized protein                         |2962.211005263158  |

## Выравнивание

В папке alligned.

## Визуализация расположения участков Z-DNA для кластеров

![image](https://user-images.githubusercontent.com/20297250/173406932-c0a7caf0-0379-408d-bc35-94708b22a46a.png)
![image](https://user-images.githubusercontent.com/20297250/173406942-28a03385-dd50-4e8e-9dd5-90e99ff6a204.png)
![image](https://user-images.githubusercontent.com/20297250/173406952-4819e301-ba71-41cc-a211-bd034e014927.png)
![image](https://user-images.githubusercontent.com/20297250/173406968-a160225f-7283-4031-9444-cb29fd3f3d01.png)
![image](https://user-images.githubusercontent.com/20297250/173406974-7df1351a-8e6d-47eb-8d64-879f0c4f367c.png)
![image](https://user-images.githubusercontent.com/20297250/173406985-787c86b8-2c76-4d8a-b071-a482fb85ff8b.png)
