Русский <br>
Описание проекта <br>
Чтобы оптимизировать производственные расходы, металлургический комбинат «Стальная птица» решил уменьшить потребление электроэнергии на этапе обработки стали. Для этого комбинату нужно контролировать температуру сплава. Ваша задача — построить модель, которая будет её предсказывать. Заказчик хочет использовать разработанную модель для имитации технологического процесса. <br>

Сталь обрабатывают в металлическом ковше вместимостью около 100 тонн. Чтобы ковш выдерживал высокие температуры, изнутри его облицовывают огнеупорным кирпичом. Расплавленную сталь заливают в ковш и подогревают до нужной температуры графитовыми электродами. Они установлены в крышке ковша. Из сплава выводится сера (этот процесс — десульфурация), добавлением примесей корректируется химический состав и отбираются пробы. Сталь легируют — изменяют её состав — подавая куски сплава из бункера для сыпучих материалов или проволоку через специальный трайб-аппарат (от англ. tribe — «масса»). Перед тем как первый раз ввести легирующие добавки, измеряют температуру стали и производят её химический анализ. Потом температуру на несколько минут повышают, добавляют легирующие материалы и продувают сплав инертным газом. Затем его перемешивают и снова проводят измерения. Такой цикл повторяется до достижения целевого химического состава и оптимальной температуры плавки. Тогда расплавленная сталь отправляется на доводку металла или поступает в машину непрерывной разливки. Оттуда готовый продукт выходит в виде заготовок-слябов (от англ. slab — «плита»). <br>

Описание данных <br>
Данные состоят из нескольких файлов, полученных из разных источников: <br>
data_arc_new.csv — данные об электродах; <br>
data_bulk_new.csv — данные о подаче сыпучих материалов (объём); <br>
data_bulk_time_new.csv — данные о подаче сыпучих материалов (время); <br>
data_gas_new.csv — данные о продувке сплава газом; <br>
data_temp_new.csv — результаты измерения температуры; <br>
data_wire_new.csv — данные о проволочных материалах (объём); <br>
data_wire_time_new.csv — данные о проволочных материалах (время). <br>

key — номер партии; <br>
Начало нагрева дугой — время начала нагрева; <br>
Конец нагрева дугой — время окончания нагрева; <br>
Активная мощность — значение активной мощности; <br>
Реактивная мощность — значение реактивной мощности. <br>

key — номер партии; <br>
Bulk 1 … Bulk 15 — объём подаваемого материала. <br>

key — номер партии; <br>
Bulk 1 … Bulk 15 — время подачи материала. <br>

key — номер партии; <br>
Газ 1 — объём подаваемого газа. <br>

key — номер партии; <br>
Время замера — время замера; <br>
Температура — значение температуры. <br>

key — номер партии; <br>
Wire 1 … Wire 15 — объём подаваемых проволочных материалов. <br>

key — номер партии; <br>
Wire 1 … Wire 15 — время подачи проволочных материалов. <br>
Во всех файлах столбец key содержит номер партии. В файлах может быть несколько строк с одинаковым значением key: они соответствуют разным итерациям обработки. <br>


<br>
<br>
<br>

English <br>
Description of the project <br>
To optimize production costs, the metallurgical plant "Steel Bird" has decided to reduce electricity consumption during the steel processing stage. To achieve this, the plant needs to monitor the temperature of the alloy. Your task is to build a model that will predict it.
The client wants to use the developed model to simulate the technological process. Below we will discuss the details of this process. It is important to know them before generating new features. <br>

Steel is processed in a metal ladle with a capacity of about 100 tons. To withstand high temperatures, the ladle is lined with refractory bricks on the inside. The molten steel is poured into the ladle and heated to the required temperature by graphite electrodes installed in the ladle's lid.
Sulfur is removed from the alloy (this process is called desulfurization), the chemical composition is adjusted by adding additives, and samples are taken. Alloying is performed by changing its composition, either by feeding pieces of the alloy from a bulk material hopper or wire through a special tribe apparatus (from English "tribe" - "mass").
Before introducing the alloying additives for the first time, the temperature of the steel is measured, and its chemical analysis is performed. Then the temperature is raised for several minutes, alloying materials are added, and the alloy is blown with inert gas. Then it is stirred, and measurements are taken again. This cycle is repeated until the target chemical composition and optimal melting temperature are reached.
The molten steel is then sent for metal refinement or enters the continuous casting machine. From there, the finished product emerges in the form of slabs. <br>

Data descriptions <br>
The data consists of several files obtained from different sources: <br>
data_arc_new.csv — data on electrodes; <br>
data_bulk_new.csv — data on the delivery of bulk materials (volume); <br>
data_bulk_time_new.csv — data on the delivery of bulk materials (time); <br>
data_gas_new.csv — data on blowing gas into the alloy; <br>
data_temp_new.csv — temperature measurement results; <br>
data_wire_new.csv — data on wire materials (volume); <br>
data_wire_time_new.csv — data on wire materials (time). <br>
key — batch number; <br>
Start heating by arc — start heating time; <br>
End heating by arc — end heating time; <br>
Active power — active power value; <br>
Reactive power — reactive power value. <br>

key — batch number; <br>
Bulk 1 … Bulk 15 — volume of material delivered. <br>

key — batch number; <br>
Bulk 1 … Bulk 15 — material delivery time. <br>

key — batch number; <br>
Gas 1 — volume of gas delivered. <br>

key — batch number; <br>
Measurement time — measurement time; <br>
Temperature — temperature value. <br>

key — batch number; <br>
Wire 1 … Wire 15 — volume of wire material delivered. <br>

key — batch number; <br>
Wire 1 … Wire 15 — wire material delivery time. <br>
In all files, the "key" column contains the batch number. There may be several rows with the same "key" value in the files: they correspond to different processing iterations. <br>


