# hse_hw2_chip

[colab](https://colab.research.google.com/drive/1Ycsdk3-0EGhef3GgxZkByKvkMArD8lne?usp=sharing)

### FastQc

### Статистика по образцам
[fastqc отчеты можно найти здесь](https://github.com/adriadar/hse_hw2_chip/tree/main/fastqc)

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/table.png)

Почему процент выравниваний получился именно таким?

Мы выравниваем всего на одну хромосому, поэтому получается большой процент невыровненных. (подрезание не сильно улучшило результаты)
### Диаграммы

![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn1-1.png)
![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn2-1.png)
![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn3-1.png)
![](https://github.com/adriadar/hse_hw2_chip/blob/main/img/Intervene_venn4-1.png)

Различия в количестве пересечений можно объяснить количеством кусочков последовательности в риде. Например, если рид A состоит из 5 небольших частей, а последовательность B состоит из 1 части, которая полность перекрывает последовательность A, то получится что B пересекается с A 5 раз, а А пресекается с B всего один. То есть в нашем случае, NA peaks перекрываеют риды больше раз, а значит возможно, что риды состоят из более мелких частей, чем NA peaks.


### Бонус

<img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_fxu.png width="400"> <img src=https://github.com/adriadar/hse_hw2_chip/blob/main/img/result_qcm.png width="400">
