# breast-cancer-segmentation
**Сегментация раковой опухоли молочной железы алгоритмами кластеризации и пороговой обработкой**

Одним из актуальных направлений развития информационных технологий в медицине является исследование и обработка цифровых изображений: улучшение качества изображения, распознавание отдельных элементов, группировка данных по схожим значениям признаков.  Важная задача обработки и анализа изображений в медицинской диагностике заболеваний – распознавание патологических процессов.

Финальный результат анализа изображений во многом определяется качеством сегментации. Сегментация предназначена для выделения на изображениях областей с одинаковыми характеристиками или свойствами. Такие области обычно соответствуют объектам или их частям, которые определяют исследователи. Сегментация является сложным моментом в обработке и анализе медицинских изображений биологической ткани, так как необходимо выделять области, соответствующие различным объектам или структурам.

Значимость данного исследования заключается в эффективности применения методов машинного обучения, а именно – таксономии, классификации «без учителя», в повседневной деятельности врача-маммолога, поскольку рак молочной железы в структуре онкологических заболеваний во многих странах занимает лидирующее место. Ранняя диагностика рака молочной железы позволяет существенно снизить частоту смертности женщин.
Задача таксономии не теряет своей актуальности на протяжении многих десятилетий. Универсальный алгоритм таксономии FRiS– Cluster, созданный при использовании функции конкурентного сходства (FRiS-функции), которая является эффективным инструментом для решения различных задач анализа данных, составляет реальную конкуренцию человеческой способности к обобщению. Для сегментации раковой опухоли в работе описываются этап предварительной обработки данных, пороговая сегментация, алгоритм кластеризации k-means и FRiS-Cluster, их эффективность, а также выбирается наилучший.


   **Цель данной работы** –  использовать полезные свойства функции конкурентного сходства, повышающие качество сегментации раковой области на маммографических снимках, путем реализации алгоритма FRiS-Cluster, а также сравнить его с классическим алгоритмом кластеризации k-means и методом пороговой обработки. Для поставленной цели сформулированы следующие задачи:
  - провести этап предобработки изображений;
  - осуществить систему тестирования на базе снимков молочной железы       путем пороговой сегментации, используя гистограмму яркостей;
  - сравнить полученную точность эксперимента с мнением человека-эксперта;
  - осуществить систему тестирования на базе снимков молочной железы        с помощью одного из стандартных алгоритмов кластеризации k-means;
  - сравнить полученную точность эксперимента с мнением человека-эксперта;
 - реализовать алгоритм FRiS-Cluster для сегментации медицинских изображений;
 - сравнить полученную точность эксперимента с мнением человека-эксперта;
 - сравнить рассматриваемые алгоритмы.

Базы данных: https://www.kaggle.com/kmader/mias-mammography
http://peipa.essex.ac.uk/info/mias.html

