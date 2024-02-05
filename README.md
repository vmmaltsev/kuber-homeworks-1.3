# Домашнее задание к занятию «Запуск приложений в K8S» - `Мальцев Виктор`

---

Задание 1. Создать Deployment и обеспечить доступ к репликам приложения из другого Pod

    1. Создать Deployment приложения, состоящего из двух контейнеров — nginx и multitool. Решить возникшую ошибку.
    2. После запуска увеличить количество реплик работающего приложения до 2.
    3. Продемонстрировать количество подов до и после масштабирования.
    4. Создать Service, который обеспечит доступ до реплик приложений из п.1.
    5. Создать отдельный Pod с приложением multitool и убедиться с помощью curl, что из пода есть доступ до приложений из п.1.

Ответ:

Манифесты расположены в директории https://github.com/vmmaltsev/kuber-homeworks-1.3/tree/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201

Скриншоты

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_109.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_110.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_111.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_112.png)




---

Задание 2. Создать Deployment и обеспечить старт основного контейнера при выполнении условий

    1. Создать Deployment приложения nginx и обеспечить старт контейнера только после того, как будет запущен сервис этого приложения.
    2. Убедиться, что nginx не стартует. В качестве Init-контейнера взять busybox.
    3. Создать и запустить Service. Убедиться, что Init запустился.
    4. Продемонстрировать состояние пода до и после запуска сервиса.

Ответ:

Манифесты расположены в директории https://github.com/vmmaltsev/kuber-homeworks-1.3/tree/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%202

Скриншоты

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_113.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_114.png)

