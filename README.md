# Spring Web MVC — миграция CRUD-сервера с сервлетов

## 📋 Описание задачи

Мигрировать In-Memory CRUD-сервер, написанный на **Servlet API**, на **Spring Web MVC** 
с использованием **Embed Tomcat**. Вся функциональность CRUD должна продолжать работать.

Дополнительно (задача со звёздочкой): реализовать **мягкое удаление** (soft delete) 
через флаг `removed`, чтобы данные не удалялись безвозвратно.

## 🎯 Цель

Отработать:
- Миграцию с Servlet API на Spring Web MVC;
- Работу с `@RestController`, `@RequestMapping`, `@GetMapping`, `@PostMapping`, 
  `@DeleteMapping`;
- Использование `@PathVariable`, `@RequestBody`;
- Настройку Embed Tomcat;
- Реализацию мягкого удаления и обработку исключений через `@ResponseStatus`.

## 🛠️ Используемые технологии

- Java 17+
- Spring Boot (Spring Web MVC)
- Embed Tomcat (входит в Spring Boot Starter Web)
- Maven
- `ConcurrentHashMap` / `AtomicLong` для потокобезопасности
