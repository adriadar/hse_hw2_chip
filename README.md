# hse_hw2_chip

[Colab-notebook](https://colab.research.google.com/drive/1Ycsdk3-0EGhef3GgxZkByKvkMArD8lne?usp=sharing)

### FastQc
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo1.png> 
ENCFF002AWO
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv1.png> 
ENCFF002AWV
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad1.png> 
ENCFF849RAD
Per sequence quality scores: Все три реплики хорошего качества, так как большинство ридов находятся в зеленой зоне.

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo2.png> 
ENCFF002AWO
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv2.png> 
ENCFF002AWV
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad2.png> 
ENCFF849RAD
Per sequence quality scores: тоже все хорошо, большинство ридов имеют высокое качество.

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo3.png>
ENCFF002AWO
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv3.png>
ENCFF002AWV
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad3.png>
ENCFF849RAD
Per base sequence content: у реплики ENCFF002AWO странное распределение, возможно какая-нибудь ошибка при севенировании. У остальных же все хорошо.

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo4.png> 
ENCFF002AWO
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv4.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad4.png> 
Sequence Duplication Levels: процент дупликации невысокий у всех трех реплик.

### Статистика по образцам
[fastqc отчеты можно найти здесь](https://github.com/adriadar/hse_hw2_chip/tree/main/fastqc)

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/table.png)

Почему процент выравниваний получился именно таким?

Мы выравниваем всего на одну хромосому, поэтому получается большой процент невыровненных. (подрезание не сильно улучшило результаты, поэтому дальши использовались неподрезанные риды)
### Диаграммы

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn1-1.png>
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn2-1.png>

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn3-1.png)
![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn4-1.png)

Различия в количестве пересечений можно объяснить количеством и длиной ридов последовательности в реплике. Например, если реплика A состоит из 5 коротких ридов, а последовательность B состоит из 1 рида, который полность перекрывает последовательность A, то получится что B пересекается с A 5 раз, а А пресекается с B всего один. То есть в нашем случае, NA peaks перекрываеют риды реплик больше раз, а значит возможно, что реплики состоят из более ридов частей, чем NA peaks.


### Бонус

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_fxu.png width="400"> <img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_qcm.png width="400">
