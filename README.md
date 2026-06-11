# DevOps портфолио: Электронный справочник
[![CI](https://github.com/SHNIPPED/devops-practice/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/SHNIPPED/devops-practice/actions/workflows/ci.yml)
## Проект

Веб-приложение (React + Node.js + MySQL), контейнеризированное и развёрнутое в Kubernetes.

## Технологии

- Docker, Docker Compose
- GitHub Actions (CI/CD)
- Kubernetes (kind)
- GitHub Container Registry (ghcr.io)

## Что сделано

- [x] Контейнеризация приложения
- [x] Автоматическая сборка и публикация образов в GHCR при пуше в main
- [x] Развёртывание в Kubernetes с использованием Deployment, Service, Ingress
- [x] Доступ к приложению по адресу frontend.local

## Как запустить локально

```bash
docker-compose up -d
