# Выбор локации для скважины

<div>
  <img src="https://www.python.org/static/community_logos/python-logo.png" title="python" alt="python" width="120" height="40"/>&nbsp
  <img src="https://pandas.pydata.org/static/img/pandas.svg" title="pandas" alt="pandas" width="120" height="40"/>&nbsp
  <img src="https://seaborn.pydata.org/_images/logo-wide-lightbg.svg" title="seaborn" alt="seaborn" width="120" height="40"/>&nbsp
  <img src="https://matplotlib.org/3.1.0/_images/sphx_glr_logos2_003.png" title="matplotlib" alt="matplotlib" width="120" height="40"/>&nbsp
  <img src="https://github.com/scikit-learn/scikit-learn/blob/main/doc/logos/scikit-learn-logo-small.png" title="scikit-learn" alt="scikit-learn" width="120" height="40"/>&nbsp
</div>

Я работаю с добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.

Мне предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. 

**Задачи:**

1. **Постройте модель машинного обучения**, которая поможет определить регион, где добыча принесёт наибольшую прибыль. 
2. **Проанализируйте** возможную **прибыль** и **риски** техникой *Bootstrap.*

**Шаги для выбора локации:**

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

**Вывод:**

* Для разработки скважин предлагаю регион 2, так как риск убытков по условию меньше 2.5 % а также, потому что среняя ожидаемая прибыль самая высокая среди перечисленных регионов
* Регион 1 и 3 имеют риск превышающий допустимый
