# E-commerce Platform

## Описание
E-commerce Platform — это платформа для интернет-магазина, которая позволяет управлять каталогом товаров, корзинами пользователей и заказами.  
Цель проекта — изучение микросервисной архитектуры, реализация REST API и внедрение современных технологий.  

## Функционал
- Управление товарами (добавление, редактирование, удаление).
- Корзина покупателя с возможностью добавлять и удалять товары.
- Создание заказов и управление их статусами.
- Интеграция с платёжной системой.
- Отправка уведомлений пользователям.

## Технологии
- **Язык:** Java 17
- **Фреймворк:** Spring Boot (REST, Data, Security)
- **База данных:** PostgreSQL
- **Мессенджинг:** Apache Kafka
- **Кэш:** Redis
- **Контейнеризация:** Docker
- **Мониторинг:** Prometheus, Grafana  

## Установка и запуск
1. Клонируйте репозиторий:
   ```bash
   git clone <URL>

2. Запустите приложение:
   ```bash
   ./mvnw spring-boot:run
3. Проверьте работу API:
   ```bash
   GET /health — проверка статуса приложения.


---

## Цели проекта
- Изучение микросервисной архитектуры.  
- Практика работы с Spring Boot, REST API, базами данных.  
- Применение DevOps-инструментов: Docker, Kubernetes.  
- Создание готового проекта для портфолио и использования на собеседовании.  
