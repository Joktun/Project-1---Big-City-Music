Русский <br>
Описание проекта <br>
Допустим, я работаю в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. Шаги для выбора локации обычно такие: В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов; Строят модель для предсказания объёма запасов в новых скважинах; Выбирают скважины с самыми высокими оценками значений; Определяют регион с максимальной суммарной прибылью отобранных скважин. Мне предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Я построил модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализировал возможную прибыль и риски техникой Bootstrap. <br>

Описание данных <br>
id — уникальный идентификатор скважины; <br>
f0, f1, f2 — три признака точек (неважно, что они означают, но сами признаки значимы); <br>
product — объём запасов в скважине (тыс. баррелей). <br>

Условия задачи <br>
Для обучения модели подходит только линейная регрессия (остальные — недостаточно предсказуемые). <br>
При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки. <br>
Бюджет на разработку скважин в регионе — 10 млрд рублей. <br>
При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей. <br>
После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью. <br>
Данные синтетические: детали контрактов и характеристики месторождений не разглашаются. <br>

<br>
<br>
<br>

English <br>
Description of the project <br>
Suppose you work for the mining company "GlavRosGosNeft". You need to decide where to drill a new well.
The steps for choosing a location are usually as follows:
In the selected region, collect characteristics for wells: oil quality and volume of its reserves;
Build a model to predict the volume of reserves in new wells;
Select wells with the highest value estimates;
Determine the region with the maximum total profit from the selected wells.
You are provided with oil samples in three regions. The characteristics for each well in the region are already known. Build a model to determine the region where extraction will bring the greatest profit. Analyze the possible profit and risks using the Bootstrap technique. <br>

Data descriptions <br>
id — unique well identifier; <br>
f0, f1, f2 — three significant features of points (irrelevant what they mean, but the features themselves are significant); <br>
product — volume of reserves in the well (thousands of barrels). <br>

Task Conditions <br>
Only linear regression is suitable for training the model (the rest are not predictable enough). <br>
When exploring a region, 500 points are studied, out of which 200 best are selected for development using machine learning. <br>
The budget for developing wells in the region is 10 billion rubles. <br>
With the current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of product is 450 thousand rubles, as the volume is indicated in thousands of barrels. <br>
After assessing the risks, only those regions where the probability of losses is less than 2.5% should be left. Among them, choose the region with the highest average profit. <br>
The data is synthetic: contract details and deposit characteristics are not disclosed. <br>

