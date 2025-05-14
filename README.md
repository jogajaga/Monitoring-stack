    #DevOps Monitoring Stack

    ## Project:

    - Prometheus - сбор метрик контейнеров и сервисов.
    - Grafana - визуализация, дашборды и настройка алертов.
    - cAdvisor - сбор метрик контейнеров Docker.

    ## Capabillities:

    - Мониторинг контейнеров по CPU и RAM.
    - Настройка алертов по CPU и Memory Usage.
    - Уведомления о событиях в Телеграм через Grafana.
    - Быстрый запуск всей инфраструктуры через Docker-Compose.
    - Стресс тест для контейнеров.

    ## Launch of the project:

    1. Клонировать репозиторий:

    git clone https://github.com/jogajaga/Monitoring-stack.git
    cd Monitoring-stack
    docker-compose up -d

    2. Запуск стресс теста:
    
    docker-compose --profile stress-test up stress
