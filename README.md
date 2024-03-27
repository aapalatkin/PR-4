# PR-4 Сбор логов 

Создание 2 виртуальных машин на базе Debian 12 в одной подсети
![Снимок экрана 2024-03-26 234619](https://github.com/aapalatkin/PR-4/assets/72595297/2a507107-3e74-441b-8b10-b7cbc83876ae)


Обновление пакетов
![Снимок экрана 2024-03-26 234841](https://github.com/aapalatkin/PR-4/assets/72595297/72494df5-f219-4c7f-a70d-bd5972f053c6)


Установка syslog
![Снимок экрана 2024-03-26 235034](https://github.com/aapalatkin/PR-4/assets/72595297/5c4b477e-3047-4445-a58d-96b07eeef6c4)


Правка конфигурации
![Снимок экрана 2024-03-26 235559](https://github.com/aapalatkin/PR-4/assets/72595297/f1f8de8a-d737-4972-a047-1df23171c0fb)
![Снимок экрана 2024-03-27 011348](https://github.com/aapalatkin/PR-4/assets/72595297/4912925e-40ac-488e-b517-e1a7f1dab4fc)


Добавляем правила в брандмауэре и перезапускаем службу syslog
![Снимок экрана 2024-03-27 000115](https://github.com/aapalatkin/PR-4/assets/72595297/8a299c2f-ea0e-4c5c-88f0-dff4d13f0290)


Проверяем созданные по шаблону директории двух машин
![Снимок экрана 2024-03-27 005118](https://github.com/aapalatkin/PR-4/assets/72595297/6a3d2b9f-0ecd-44c5-bbde-bc9f0709f581)


Устанавливаем docker-compose
![Снимок экрана 2024-03-27 005334](https://github.com/aapalatkin/PR-4/assets/72595297/93d95c92-75c5-4fd2-b726-e89279223d40)


Скачиваем серверную часть Loki
![Снимок экрана 2024-03-27 005416](https://github.com/aapalatkin/PR-4/assets/72595297/79c47bb7-a5a3-4798-9055-36c80f3f5bc6)


Запускаем docker-compose 
![Снимок экрана 2024-03-27 011320](https://github.com/aapalatkin/PR-4/assets/72595297/b38dc797-d593-4038-a4ef-c04e9b8f483f)


Устанавливаем клиентскую часть Promtail через docker-compose
![Снимок экрана 2024-03-27 014106](https://github.com/aapalatkin/PR-4/assets/72595297/3fa233de-7cf6-4719-a672-2f339dc8d618)



Docker-compose
![Снимок экрана 2024-03-27 014253](https://github.com/aapalatkin/PR-4/assets/72595297/087856dd-0f44-4d0f-b4a0-c1beba7cebc1)


Заходим в браузер и проверяем логи по фильтру
![Снимок экрана 2024-03-27 014648](https://github.com/aapalatkin/PR-4/assets/72595297/6d0498e2-397b-4ec0-b515-4032bb163dab)



Логи обеих машин
![Снимок экрана 2024-03-27 014808](https://github.com/aapalatkin/PR-4/assets/72595297/21b0113a-2b23-4419-926b-93bb055075d2)


Клонирование репозитория Signoz
![Снимок экрана 2024-03-27 075454](https://github.com/aapalatkin/PR-4/assets/72595297/a6ea8b29-7c49-4792-a91f-cfdcf464b2cf)


Запускаем установочный скрипт
![Снимок экрана 2024-03-27 075548](https://github.com/aapalatkin/PR-4/assets/72595297/1d4e5fc2-7912-4c15-b5b9-bfcab4c07093)
![Снимок экрана 2024-03-27 075603](https://github.com/aapalatkin/PR-4/assets/72595297/354f0c49-b419-4151-b6f9-aedbf98305ae)


Проверка работоспособности
![Снимок экрана 2024-03-27 075617](https://github.com/aapalatkin/PR-4/assets/72595297/e2d252d7-3a5a-493d-a5ca-6686f6c2be30)
![Снимок экрана 2024-03-27 075813](https://github.com/aapalatkin/PR-4/assets/72595297/9577265c-2d1b-4cb5-b198-e9f9a5befec8)
![Снимок экрана 2024-03-27 075758](https://github.com/aapalatkin/PR-4/assets/72595297/85f0cc3e-c46a-410b-89a4-9a2138688a2f)



