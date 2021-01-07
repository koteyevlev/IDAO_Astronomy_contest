# IDAO 2020 Contest

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/koteyevlev/Astronomy_contest/blob/master/Astronomy_contest_final.ipynb)

Здесь представлена реализация решения отборочного этапа соревнования по анализу данных IDAO 2020 от Яндекса. В задании нужно было запрогнозировать движение различных спутников на месяц вперед - конечное решение имеет точность 97% по метрике SMAPE, для большинства объектов получаются очень точные предсказания. 

Результаты контеста - Команда Snowflakes https://idao.world/results/ , 4 место в 1 треке 

При решении были использованы:
 * Кластеризация данных в спутнике и обработка почти дублированных данных
 * Частично идеи unsupervised learning
 * Стекинг 4 алгоритмов голосованием с использованием Catboost
