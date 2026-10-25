# Фотостудия «Кадр»

[![CI/CD kadr-landing](https://github.com/Miz3k1/kadr-landing/actions/workflows/deploy.yml/badge.svg)](https://github.com/Miz3k1/kadr-landing/actions/workflows/deploy.yml)

Лендинг фотостудии «Кадр» (Санкт-Петербург), созданный в лабораторной работе № 4
с помощью ИИ-ассистентов и доработанный в лабораторной работе № 5.

Сайт: https://miz3k1.github.io/kadr-landing/

## Структура проекта

- `index.html` — страница сайта (HTML, CSS и JavaScript в одном файле);
- `images/` — фотографии залов студии.

## Ветки репозитория

- `main` — основная ветка, из неё публикуется сайт (GitHub Pages);
- `photos` — замена фотографий-заглушек на снимки залов (изменения внесены агентом SourceCraft);
- `seo` — описание страницы, разметка Open Graph и иконка сайта;
- `docs` — описание проекта в README.

## CI/CD

При каждом push в `main` и в каждом pull request GitHub Actions запускает workflow `.github/workflows/deploy.yml`:

1. задание «Проверка HTML» — линтер HTMLHint проверяет разметку;
2. задание «Публикация на GitHub Pages» — выполняется только после успешной проверки и только для ветви `main`.

## Фотографии

Снимки интерьеров взяты с сайта Unsplash (https://unsplash.com) и используются
по лицензии Unsplash.
