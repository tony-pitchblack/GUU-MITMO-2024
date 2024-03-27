## Лабораторная работа 1
*Файл* lab-01.ipynb
### Задание 1
Наилучшее количество степеней свободы равно6, так как именно при нём впервые `MSE_train` и `MSE_test` становятся достаточно близки,
т.е. отсутствует переобучение, а при последующем увеличении степеней свободы как `MSE_train`, так и `MSE_test`
уменьшаются несущественно.

![alt text](https://github.com/tony-pitchblack/GUU-MITMO-2024/blob/class/images/MSE_n_all_60.jpg)

### Задание 2
Если построить регрессию `MSE` на объем выборки `n_all`, то оказывается, что
`MSE_train` увеличивается с количеством `n_all`, а `MSE_test` - уменьшается

![alt text](https://github.com/tony-pitchblack/GUU-MITMO-2024/blob/class/images/MSE_vs_n.png)
