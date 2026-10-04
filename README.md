# bioinf_hw1
https://colab.research.google.com/drive/1vRSE12h-hbK6lHKs4EVaXnjM_W916HvM?usp=sharing
Сборщик: Platanus
Схема работы: подвыборка (seqtk) -> QC (FastQC + MultiQC) -> тримминг (platanus_trim, platanus_internal_trim) → повторный QC → контиги (platanus assemble) -> скаффолды (platanus scaffold) -> закрытие гэпов (platanus gap_close) -> статистика (N50, число гэпов и тд.) -> бонусное задание.

Подвыборка:
Уменьшили PE и MP до 5 и 1,5 млн пар соответсвенно. В фаста-файле один рид занимает 4 строки, поэтому получили 20 и 6 млн строк. Для R1 и R2 использовался один и то же сид 412.
