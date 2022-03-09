# hse_hw2_chip

[colab](https://colab.research.google.com/drive/1Ycsdk3-0EGhef3GgxZkByKvkMArD8lne?usp=sharing)

### FastQc
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo1.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv1.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad1.png> 

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo2.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv2.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad2.png> 

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo3.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv3.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad3.png> 

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awo4.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/awv4.png> 
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/rad4.png> 

### Статистика по образцам
[fastqc отчеты можно найти здесь](https://github.com/adriadar/hse_hw2_chip/tree/main/fastqc)

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/table.png)

Почему процент выравниваний получился именно таким?

Мы выравниваем всего на одну хромосому, поэтому получается большой процент невыровненных. (подрезание не сильно улучшило результаты)
### Диаграммы

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn1-1.png>
<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn2-1.png>

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn3-1.png)
![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn4-1.png)

Различия в количестве пересечений можно объяснить количеством кусочков последовательности в риде. Например, если рид A состоит из 5 небольших частей, а последовательность B состоит из 1 части, которая полность перекрывает последовательность A, то получится что B пересекается с A 5 раз, а А пресекается с B всего один. То есть в нашем случае, NA peaks перекрываеют риды больше раз, а значит возможно, что риды состоят из более мелких частей, чем NA peaks.


### Бонус

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_fxu.png width="500"> <img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_qcm.png width="500">
