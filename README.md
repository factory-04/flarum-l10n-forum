# Информация

[![Tag](https://img.shields.io/github/tag/factory-04/flarum-l10n-forum.svg?style=flat-square)](https://github.com/factory-04/flarum-l10n-forum/releases)
[![Packagist](https://img.shields.io/packagist/v/metastore/flarum-ext-russian.svg?style=flat-square)](https://packagist.org/packages/metastore/flarum-l10n-forum)
[![](https://img.shields.io/packagist/dt/metastore/flarum-ext-russian.svg?style=flat-square)](https://packagist.org/packages/metastore/flarum-l10n-forum)
[![License](https://img.shields.io/github/license/factory-04/flarum-l10n-forum.svg?style=flat-square)](LICENSE)
[![Liberapay](https://img.shields.io/badge/liberapay-donate-red.svg?style=flat-square)](https://liberapay.com/metadata/donate)
[![Patreon](https://img.shields.io/badge/patreon-donate-red.svg?style=flat-square)](https://patreon.com/metadata)

Пакет русской локализации движка [**Flarum**](https://flarum.org/) - программного обеспечения нового поколения для создания сообществ. Реализована поддержка единичных и множественных чисел (переменных). Все фразы взяты в двойные кавычки для предотвращения конфликтов со знаками препинания, потому что их в русском языке используется большее количество, по сравнению с английским.

## Установка

**Flarum** использует [**Composer**](https://getcomposer.org/) для управления зависимостями и расширениями.

Русский пакет локализации доступен в [**Packagist**](https://packagist.org/packages/metastore/flarum-ext-russian) и может быть установлен при помощи **Composer**.

Убедитесь, что **Composer** установлен на вашем компьютере, и введите следующую команду в терминале, находясь в корневой директории **Flarum**:

```
composer require metastore/flarum-ext-russian
```

Так же, данная команда может быть использована для обновления языкового пакета, без обновления сторонних компонентов.

Обратите внимание, что пакет локализации будет добавлен в качестве зависимости **Flarum**, и он также будет автоматически обновляться при обновлении движка форума.

## Обновление

Для обновления локализации необходимо выполнить следующие команды:

```
composer update metastore/flarum-ext-russian
php flarum cache:clear
```

## Авторы

- [Kitsune Solar](https://kitsune.solar/) - редактор.

## Ссылки

- [Поддержка](https://webmasters.community/)
- [Документация](https://flarum.webmasters.wiki/)
- [Исходный код](https://github.com/factory-04/flarum-l10n-forum)
- [Журнал изменений](CHANGELOG.md)
- [Кодекс поведения (EN)](CODE_OF_CONDUCT.en.md)
- [Кодекс поведения (RU)](CODE_OF_CONDUCT.ru.md)
- [Правила участия в разработке](CONTRIBUTING.md)
- [Сообщить о проблеме](https://github.com/factory-04/flarum-l10n-forum/issues)
- [Скачать через Packagist](https://packagist.org/packages/metastore/flarum-ext-russian)

## Платформа

- [**METADATA / FOUNDATION**](https://metadata.foundation/) - поддержка и разработка открытых проектов.
- [**METASTORE**](https://metastore.pro/) - хранилище открытых проектов [**METADATA**](https://metadata.foundation/).
