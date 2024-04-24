# Лабораторная работа 6
## Данные

*Набор данных:* В датасете *default.csv* моего варианта (17), все порядковые признаки уже оказались перекодированы и не было номинальных, поэтому я взял другой популярный классический датасет, в котором присутствовали неперекодированные категориальные признаки: [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

*Независимые переменные:*
Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, </br> RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope,</br> HeartDisease</br>

*Зависимая переменная:* HeartDisease

*Методы снижения размерности:* KernelPCA, SelectKBest
*Альтернативный классификатор*: RandomForest

## Порядок выполнения работы

1. Данные были разделены на двe выборки: обучающую 85% и тестовую 15%. Предварительный анализ обнаружил примерно равные доли классов.

3-4. Accuracy лучшего SVC составила 81%, в то время как accuracy Random Forest составила 86%. 