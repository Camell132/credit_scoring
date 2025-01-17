# Исследование надёжности заёмщиков

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели **кредитного скоринга** — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

**Цель исследования** — проверка четырех гипотез:
1. На факт погашения кредита в срок влияет семейное положение
2. На факт погашения кредита в срок влияет наличие детей 
3. На факт погашения кредита в срок влияет уровень дохода
4. Оценка влияния цели кредита на его возврат в срок

**Ход исследования**

Данные о клиентах, которым выдан кредит находятся в файле `data.csv`. О качестве данных ничего не известно. Поэтому перед проверкой гипотез понадобится обзор данных. 
