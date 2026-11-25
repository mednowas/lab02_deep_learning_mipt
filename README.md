# lab02_deep_learning_mipt

Лабораторная работа 2 по курсу [girafe-ai/ml-course](https://github.com/girafe-ai/ml-course/tree/23f_basic).

- `main_notebook.ipynb` - часть 1, ноутбук из hw08 (MNIST на numpy и на PyTorch)
- `modules.ipynb`, `mnist.py` - файлы из hw08, нужны для части 1
- `lab02_part2_overfitting.ipynb` - часть 2, Fashion-MNIST, переобучение и регуляризация
- `lab02_part3_poetry.ipynb`, `sonnets.txt` - часть 3, RNN и LSTM на сонетах Шекспира
- `artifacts/poetry_lstm.pt` - сохранённая LSTM
- `lab02_parts_4_and_5_optional.ipynb` - части 4 и 5, HAR и породы собак
- `dogs_predictions.csv` - предсказания для теста собак, формат `имя,класс`
- `requirements.txt` - библиотеки

Результаты:

- MNIST: 0.9866 (numpy), 0.9867 (PyTorch)
- Fashion-MNIST: 0.8935 на тесте
- HAR: 0.9077 на тесте
- Собаки: 0.9575 на validation, меток для теста нет

Данные скачиваются при первом запуске в папку `data/`.
