# Стандартизация норм точности гладких цилиндрических соединений

## Основные понятия

1. **Годность детали**:
   - Деталь считается годной, если её действительный размер больше нижнего предельного размера, но не превосходит верхнего предельного размера.
   - Математическое выражение: D_min ≤ D_д ≤ D_max

2. **Условия годности**:
   - Для деталей типа "отверстие": d_min ≤ d_д ≤ d_max
   - Для деталей типа "вал": d_min ≤ d_д ≤ d_max

## Виды размеров и отклонений

1. **Верхнее предельное отклонение**:
   - Определение: алгебраическая разность между верхним предельным и номинальным размерами.
   - Для отверстия: ES = D_max - D
   - Для вала: es = d_max - d

2. **Нижнее предельное отклонение**:
   - Определение: алгебраическая разность между нижним предельным и номинальным размерами.
   - Для отверстия: EI = D_min - D
   - Для вала: ei = d_min - d

3. **Характеристики отклонений**:
   - Отклонения могут быть положительными, отрицательными и равными нулю.
   - Отклонения, равные нулю, в обозначении не указываются.

4. **Представление на чертежах**:
   - Номинальные и предельные линейные размеры, а также их отклонения указываются в миллиметрах без обозначения единицы измерения.

## Примечания

- На изображениях представлены схемы, иллюстрирующие различные случаи размеров деталей:
  1. Годный размер
  2. Негодный размер (брак исправимый)
  3. Негодный размер (брак неисправимый)

## Средние размеры и отклонения

При необходимости рассчитывают средние размеры отверстия и вала:

- Средний размер отверстия: D_c = (D_max + D_min) / 2
- Средний размер вала: d_c = (d_max + d_min) / 2

Средние отклонения отверстия и вала:

- Среднее отклонение отверстия: E_c = (ES + EI) / 2
- Среднее отклонение вала: e_c = (es + ei) / 2

## Допуск размера

Допуском размера называется разность между верхним и нижним предельными размерами или алгебраическая разность между верхним и нижним предельным отклонениями.

Допуск обозначают буквой "T" (от латинского Tolerance - допуск):

- Допуск размера отверстия: TD = D_max - D_min = ES - EI
- Допуск размера вала: Td = d_max - d_min = es - ei

Допуск всегда положительный.

## Примеры расчета допуска

1. TD = +0,015 - (+0,002) = 0,013
2. TD = -0,025 - (-0,050) = 0,025
3. TD = +0,007 - (-0,018) = 0,025
4. TD = +0,5 - (-0,5) = 1
5. TD = +0,027 - 0 = 0,027
6. TD = 0 - (-0,046) = 0,046

## Посадки

Характер соединения деталей, определяемый величиной получающихся в нем зазоров или натягов, называется посадкой.

Посадка (ГОСТ 25346-2013) – соединение наружного размерного элемента (вала) и внутреннего размерного элемента (отверстия), участвующих в сборке.

Различают три группы посадок:

1. С гарантированным зазором
2. Переходные
3. С гарантированным натягом

## Зазор

Если размеры отверстия больше размеров вала, то в соединении возникает зазор.

Зазор – это разность между размерами отверстия и вала, когда диаметр вала меньше диаметра отверстия. Обязательно положительное число.

S = D - d > 0, где:

- S - зазор
- D - диаметр отверстия
- d - диаметр вала
- Наибольший зазор: S_max = D_max - d_min
- Наименьший зазор: S_min = D_min - d_max
- Средний зазор: S_c = (S_max + S_min) / 2 = D_c - d_c = E_c - e_c

## Посадка с зазором

Посадка с зазором - это посадка, при которой в соединении отверстия и вала всегда образуется зазор, т.е. нижний предельный размер отверстия больше или равен верхнему предельному размеру вала.

## Натяг

Если до сборки размеры вала больше размеров отверстия, то в соединении возникает натяг.

Натяг – это разность размеров отверстия и вала до сборки, когда диаметр вала больше диаметра отверстия.

Натяг – отрицательное число.

N = D - d < 0, где:

- N - натяг
- D - диаметр отверстия
- d - диаметр вала
- Наибольший натяг: N_max = d_max - D_min
- Наименьший натяг: N_min = d_min - D_max
- Средний натяг: N_c = (N_max + N_min) / 2 = d_c - D_c = e_c - E_c

## Посадка с натягом

Посадка с натягом - это посадка, при которой в соединении отверстия и вала всегда образуется натяг, т.е. верхний предельный размер отверстия меньше или равен нижнему предельному размеру вала.

## Переходные посадки

В рассматриваемом соединении при одном сочетании предельных размеров отверстия и вала может получиться зазор, который меняется от 0,025 мм до нуля (S = 0 – 0,025), а при другом сочетании предельных размеров отверстия и вала может получиться натяг, который меняется от 0,015 мм до нуля (N = 0 – 0,015). То есть в данном соединении есть вероятность появления или зазора или натяга. Причем вероятность появления зазора немного выше, чем вероятность появления натяга.

Такие посадки называются переходными.

## Переходные посадки

Переходная посадка – посадка, при которой в соединении отверстия и вала возможно получение как зазора, так и натяга.

## Диапазоны посадок

1. **Диапазон посадки** – арифметическая сумма допусков размеров двух размерных элементов, образующих посадку, т.е. TD + Td
2. **Диапазон посадки с зазором** – разность между наибольшим и наименьшим зазорами: TS = S_max - S_min
3. **Диапазон посадки с натягом** – разность между наибольшим и наименьшим натягами: TN = N_max - N_min
4. **Диапазон переходной посадки** – сумма наибольшего зазора и наибольшего натяга: T(S,N) = S_max + N_max

Эти формулы позволяют определить возможный диапазон значений для различных типов посадок, что важно для правильного выбора и проектирования соединений деталей.