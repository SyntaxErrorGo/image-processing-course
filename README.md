<div align="center">

# 🖼️ Image Processing Course
### Домашние задания

**Курс:** Обработка изображений
**Студент:** Юнкин Илья Викторович
**Год:** 2026

---

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![scikit-image](https://img.shields.io/badge/scikit--image-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-image.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

</div>

---

## 📖 О репозитории

Здесь собраны домашние задания по курсу **«Обработка изображений»**.
Каждое ДЗ живёт **в отдельной ветке**.

> 🌿 Ветка `main` содержит только эту инструкцию и вспомогательные файлы.
> 📦 Сами решения — в ветках `hw01`, `hw02`, `hw03`, ...

---

## 🗂️ Структура веток

| Ветка  | Тема                                                        | Статус           |
|:-------|:------------------------------------------------------------|:----------------:|
| `main` | Инструкция, `.gitignore`, `requirements.txt`                | ⚙️ Основа        |
| `hw01` | Гистограммы, гамма-коррекция, MSE/SSIM, пороговая обработка | 🕓 Ждёт проверки |
| `hw02` | _<тема>_                                                     | ⏳ Запланировано |
| `hw03` | _<тема>_                                                     | ⏳ Запланировано |

<div align="center">

**Легенда статусов**

✅ Сдано · 🕓 Ждёт проверки · 🚧 В работе · ⏳ Запланировано · ⚙️ Основа

</div>

---

## 🚀 Как запустить

```bash
# 1. переключиться на нужное ДЗ
git checkout hw01

# 2. окружение
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3. открыть ноутбук
jupyter lab homework_01/DE_IP_2024_Task_1.ipynb
```

---

## 📐 Соглашения

* один ДЗ — одна ветка `hwNN`, внутри папка `homework_NN/`;
* ноутбук сохраняется **вместе с выводами**, чтобы решение было видно без перезапуска;
* алгоритмы, которые требуется реализовать самостоятельно, пишутся вручную,
  а библиотечные аналоги (`cv2`, `skimage`) используются только для сверки результата;
* исходные изображения лежат рядом с ноутбуком — пути в коде относительные.
