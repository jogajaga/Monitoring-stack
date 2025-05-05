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
    
    ## List of changes:
    
    docker-compose содержит полностью готовое решение мониторинга контейнеров и системы, если это нужно. 
    Были удалены тестовые контейнеры (Nginx, PSQL, Adminer, jenkins). 

    ## Launch of the project:

    1. Клонировать репозиторий:

    git clone https://github.com/jogajaga/Monitoring-stack.git
    docker-compose up -d

    2. Запуск стресс теста:
    
    docker-compose --profile stress-test up stress
    
    
