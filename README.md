# Отдельные функции для DataScience
## stratified_group_k_fold.ipynb:
Блокнот, в котором реализована функция для разделения DataFrame на тестовый и обучающие фолды, в которых:
- сохранена пропорция заданной целевой переменной
- в которых не пересекаются значения заданного столбца.

Такой функционал необходим, когда в одном ДФ несколько записей об одной и той же сущности и для исключения утечки данных необходимо предотвратить попадение этих записей одновременно и в обучающий и в тестовый фолды.

П.С. Реализованная в sclearn подобная функция доступна не во всех версиях.

##GridSearch_about.ipynb
Блок для визуализации принципов работы GridSearch


