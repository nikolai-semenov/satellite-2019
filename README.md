# Проблема

Спутники двигаются по траекториям. Точки траекторий называют эфемеридами. Прогнозировать эфемериды сложно -- ошибка прогнозирования ощутима.

# Данные

Данные представляют собой .csv файл, содержащий (в скобках указаны соответствующие столбцы):
* Настоящие эфемериды (x,y,z,Vx,Vy,Vz -- координаты и скорости по xyz) для большого количества спутников (sat_id) во времени (time)
* Спрогнозированные эфемерид (x_sim,y_sim,z_sim,Vx_sim,Vy_sim,Vz_sim) для большого количества спутников (sat_id) во времени (time);
* Часть (“будущая”) настоящих эфемерид пропущена.

# Задача

Уточнить прогноз эфемерид (заполнить пропущенные x,y,z,Vx,Vy,Vz).
