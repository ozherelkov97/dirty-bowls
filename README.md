# dirty-bowls

Ноутбук с описанием решения называется bowls.ipynb

Ссылка на скачивание весов ResNet50:

https://github.com/fchollet/deep-learning-models/releases/download/v0.1/resnet50_weights_tf_dim_ordering_tf_kernels_notop.h5


Архив original.rar следует распаковать в текущую директорию.

Получить папку с агументированными изображениями можно с помощью ноутбука augmentation.ipynb (запустить две незакомментированные ячейки, появится папка augmentation)

Если планируется запукать код на тестовой выборке, то тестовые изображения должны лежать в какой-нибудь папке, которая должна лежать в папке c названием test. Код создает таблицу out.csv в формате sample_submission.csv с предсказаниями классов на тестовой выборке.
