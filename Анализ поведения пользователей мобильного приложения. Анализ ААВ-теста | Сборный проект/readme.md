# 7. Анализ поведения пользователей мобильного приложения. Анализ ААВ-теста | Сборный проект 2
Используемые библиотеки: pandas, numpy, math, scipy, matplotlib, seaborn
Также: Анализ А/А/В-теста, анализ воронки продаж

Задача: Исследовал поведение пользователей мобильного приложения по продаже питания. Изучил воронку продаж: как пользователи доходят до покупки, сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах, на каких именно. Проанализировал результаты A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Дизайнеры захотели поменять шрифты во всём приложении и необходимо было по результатам A/A/B-теста сделать выводы и принять решение, дать рекомендации.

# 7. Analysis of mobile application user behavior. AAB test analysis | Collecting project 2
Libraries: pandas, numpy, math, scipy, matplotlib, seaborn
Also: A/A/B test analysis, sales funnel analysis

Problem: Researched the behavior of users of a mobile application for the sale of food. I studied the sales funnel: how users reach the purchase, how many users reach the purchase, and how many get stuck on the previous steps, on which ones. Analyzed the results of the A/A/B experiment. Users were divided into 3 groups: 2 control groups with old fonts and one experimental group with new ones. The designers wanted to change the fonts throughout the application and it was necessary to draw conclusions based on the results of the A/A/B experiment and make a decision, give recommendations.

# Вывод

Кумулятивная выручка в обеих группах росла равномерно, однако с середины теста группа В значительно превзошла группу А и до конца теста имела более успешные показатели

Среднее количество заказов в группе В также превосходит этот показатель в группе А

Более 95 % пользователей не делают более 3 заказов. Максимальное количество заказов пользователем = 11

Более 95 % пользователей не тратят на заказы более 33000. Максимальная трата на заказы пользователем = 1294500

Выявлены статистичестки значимые раличия в среднем количестве заказов на посетителя как по"сырым", так и по "очищенным" данным. Относительные различия в среднем чеке не имело статистической значимости как по "сырым" так и по "очищенным" данным.
