# CarPrice-Prediction

Модель, определяющая категорию цены подержанного автомобиля в зависимости от характеристик транспортного средства

## Model Accuracies:

| Model                             | Accuracy |
| --------------------------------- | -------- |
| Random Forest                     | 77.75    |
| Logistic Regression               | 77.53    |
| MultilLayer Perceptron Classifier | 79.10    |

## Стек:

- Python
- _Libraries_: Pandas, missingno, Scikit-learn, Matplotlib

## Описание датасета:

- `id`: идентификатор записи;
- `url`: URL записи о продаже;
- `region`: регион;
- `region_url`: URL региона;
- `price`: стоимость;
- `year`: год выпуска;
- `manufacturer`: производитель;
- `model`: модель;
- `condition`: состояние;
- `cylinders`: количество цилиндров;
- `fuel`: тип топлива;
- `odometer`: количество пройденных миль;
- `title_status`: статус;
- `transmission`: коробка передач;
- `VIN:` идентификационный номер;
- `drive`: тип привода;
- `size:` размер;
- `type`: кузов;
- `paint_color`: цвет;
- `image_url`: URL изображения;
- `description`: указанное описание;
- `county`: страна;
- `state`: штат;
- `lat`: широта;
- `long`: долгота;
- `posting_date`: дата размещения объявления о продаже;
- `price_category`: категория цены.
