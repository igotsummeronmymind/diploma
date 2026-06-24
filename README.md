# Определение характеристик транспортного средства по видеоизображениям

ВКР бакалавриат, МФТИ, 2026.

**Автор:** Клименко В. Е. 

**Научный руководитель:** Назаров А. Н., д-р техн. наук, проф.

**Направление:** 03.03.01 Прикладные математика и физика (профиль «Радиотехника и компьютерные технологии»).

## Ноутбуки

1. [`01_detection_runned.ipynb`](https://colab.research.google.com/drive/1HyW5SCKzXjwlX0wnVkqZ1rVCWWsVg3v5#scrollTo=5937829f): детекция ТС и номерных знаков (YOLO26n) + распознавание номеров EasyOCR.
2. [`02_color_classifier_runned.ipynb`](https://colab.research.google.com/drive/1FZtvp-BXFtyNuW2DHVtbh_dL-7xH-j1a?usp=sharing): классификатор цвета кузова, ResNet18 (датасет VCoR, 9 классов).
3. [`03_body_classifier_runned.ipynb`](https://colab.research.google.com/drive/1f0CH8pOYu-WN2ao2KnbBzqkT6u1HHScU?usp=sharing): классификатор типа кузова, ResNet18 (датасет CompCars, 6 классов).
4. [`04_pipeline_final.ipynb`](https://colab.research.google.com/drive/1wS2O6RzNTtozZe-9e8_XuUNlT0qhazCk?usp=sharing): финальный конвейер и видеоинференс с трекингом ByteTrack.
