# Awesome Django with stars

> A curated list of awesome things related to Django. Maintained by [Will Vincent](https://github.com/wsvincent) and [Jeff Triplett](https://github.com/jefftriplett).

<br>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/django-logo-negative.svg">
  <img alt="Dark and Light mode version of the Django logo" src="./assets/django-logo-positive.svg">
</picture>
</div>

<br>

Please consider supporting Django by making a donation to the <a rel="sponsored" href="https://www.djangoproject.com/fundraising/">Django Software Foundation</a>,
sponsoring via [GitHub Sponsors](https://github.com/sponsors/django),
or buying <a rel="sponsored" href="https://django.threadless.com/">official merchandise</a>.

## Contents

<!--lint disable awesome-toc-->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Third-Party Packages](#third-party-packages)
  * [Admin](#admin)
  * [Admin Themes](#admin-themes)
  * [APIs](#apis)
  * [Async](#async)
  * [Caching](#caching)
  * [Commands](#commands)
  * [Configuration](#configuration)
  * [Content Management Systems](#content-management-systems)
  * [Database Connectors](#database-connectors)
  * [Dependency Injection](#dependency-injection)
  * [ECommerce](#ecommerce)
  * [Editors](#editors)
  * [Files/Images](#filesimages)
  * [Forms](#forms)
  * [Full-stack frameworks](#full-stack-frameworks)
  * [General](#general)
  * [Internationalisation (i18n)](#internationalisation-i18n)
  * [Logging](#logging)
  * [Monitoring](#monitoring)
  * [Mailing](#mailing)
  * [Model Fields](#model-fields)
  * [Models](#models)
  * [Performance](#performance)
  * [Permissions](#permissions)
  * [Search](#search)
  * [Search Engine Optimisation](#search-engine-optimisation)
  * [Security](#security)
  * [Static Assets](#static-assets)
  * [Task Queues](#task-queues)
  * [Templates](#templates)
  * [Testing](#testing)
  * [URLs](#urls)
  * [Users](#users)
  * [Views](#views)
* [Python Packages](#python-packages)
* [Resources](#resources)
  * [Official Resources](#official-resources)
  * [Educational](#educational)
  * [Community](#community)
  * [Conferences](#conferences)
  * [Job Boards](#job-boards)
  * [Newsletters](#newsletters)
  * [Podcasts](#podcasts)
  * [Videos](#videos)
  * [Books](#books)
* [Hosting](#hosting)
  * [PaaS (Platforms-as-a-Service)](#paas-platforms-as-a-service)
  * [IaaS (Infrastructure-as-a-Service)](#iaas-infrastructure-as-a-service)
* [Projects](#projects)
  * [Boilerplate](#boilerplate)
  * [Open Source Projects](#open-source-projects)
* [Django REST Framework](#django-rest-framework)
  * [DRF Resources](#drf-resources)
  * [DRF Tutorials](#drf-tutorials)
* [Wagtail](#wagtail)
  * [Wagtail Resources](#wagtail-resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!--lint enable awesome-toc-->

## Third-Party Packages

*For a complete listing of all available packages, see [Django Packages](https://djangopackages.org/)*

### Admin

* [django-import-export](https://github.com/django-import-export/django-import-export) ⭐ 3,333 | 🐛 26 | 🌐 Python | 📅 2026-08-24 - Django application and library for importing and exporting data with admin integration.
* [django-hijack](https://github.com/django-hijack/django-hijack) ⭐ 1,745 | 🐛 5 | 🌐 Python | 📅 2026-08-27 - Admins can log in and work on behalf of other users without having to know their credentials.
* [django-admin-sortable2](https://github.com/jrief/django-admin-sortable2) ⭐ 885 | 🐛 49 | 🌐 Python | 📅 2026-07-06 - Generic drag-and-drop ordering for objects in the Django admin interface.
* [dj-control-room](https://github.com/django-control-room/dj-control-room) ⭐ 565 | 🐛 17 | 🌐 Python | 📅 2026-08-11 - Build a control plane with a suite of operational tools inside the Django admin (Redis, cache, Celery, URLs, and more).
* [django-loginas](https://github.com/skorokithakis/django-loginas) ⭐ 376 | 🐛 7 | 🌐 Python | 📅 2026-01-06 - "Log in as user" for the Django admin.
* [django-admin-env-notice](https://github.com/dizballanze/django-admin-env-notice) ⭐ 344 | 🐛 4 | 🌐 Python | 📅 2026-01-22 - Visually distinguish environments in Django Admin, for example: `development`, `staging`, `production`.
* [impostor](https://github.com/avallbona/Impostor) ⭐ 161 | 🐛 5 | 🌐 Python | 📅 2026-08-17 - Impostor is a Django application which allows staff members to log in as a different user by using their own username and password.
* [django-admin-collaborator](https://github.com/brktrlw/django-admin-collaborator) ⭐ 105 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-12 - Add real-time user presence, edit locks, and chat to Django admin with Channels and Redis.
* [django-related-admin](https://github.com/PetrDlouhy/django-related-admin) ⭐ 71 | 🐛 3 | 🌐 Python | 📅 2025-05-16 - A helper library that allows you to write list\_displays across foreign key relationships.
* [django-admin-inline-paginator-plus](https://github.com/DmytroLitvinov/django-admin-inline-paginator-plus) ⭐ 68 | 🐛 3 | 🌐 Python | 📅 2026-05-16 - A simple way to paginate your inline in Django admin
* [django-impersonate](https://pypi.org/project/django-impersonate/) - Allow superusers to “impersonate” other non-superuser accounts.

### Admin Themes

* [django-grappelli](https://github.com/sehmaschine/django-grappelli) ⭐ 3,944 | 🐛 8 | 🌐 HTML | 📅 2026-08-10 - A jazzy skin for the admin.
* [django-unfold](https://github.com/unfoldadmin/django-unfold) ⭐ 3,647 | 🐛 30 | 🌐 Python | 📅 2026-08-29 - Modern Django admin theme for seamless interface development.
* [django-admin-interface](https://github.com/fabiocaccamo/django-admin-interface) ⭐ 2,041 | 🐛 21 | 🌐 Python | 📅 2026-08-24 - Customize Admin by the admin itself(color, header. title,logo) and  popup windows replaced by modals.
* [django-jazzmin](https://github.com/farridav/django-jazzmin) ⭐ 1,878 | 🐛 175 | 🌐 HTML | 📅 2026-06-25 - Drop-in theme for django admin, that utilises AdminLTE 3 & Bootstrap 4 to make yo' admin look jazzy.
* [django-baton](https://github.com/otto-torino/django-baton) ⭐ 995 | 🐛 50 | 🌐 Python | 📅 2026-08-09 - A cool, modern and responsive django admin application based on bootstrap 5.
* [django-jet-reboot](https://github.com/assem-ch/django-jet-reboot) ⭐ 496 | 🐛 38 | 🌐 CSS | 📅 2026-02-01 - Django Jet is modern template for Django admin interface with improved functionality.
* [django-daisy](https://github.com/hypy13/django-daisy) ⭐ 364 | 🐛 14 | 🌐 CSS | 📅 2026-08-30 - A modern django dashboard fully responsive built with daisyui.
* [django-semantic-admin](https://github.com/globophobe/django-semantic-admin) ⭐ 183 | 🐛 6 | 🌐 Python | 📅 2026-08-11 - Django Semantic UI admin theme.
* [django-smartbase-admin](https://github.com/SmartBase-SK/django-smartbase-admin) ⭐ 128 | 🐛 3 | 🌐 Python | 📅 2026-08-31 - Django SmartBase Admin 🚀 performance-tuned 👥 end-user ready beautiful admin panel

### APIs

<!--lint disable double-link-->

* [django-rest-framework](https://github.com/encode/django-rest-framework) ⭐ 30,149 | 🐛 59 | 🌐 Python | 📅 2026-08-25 - Web APIs for Django.
* [django-cors-headers](https://github.com/adamchainz/django-cors-headers) ⭐ 5,586 | 🐛 9 | 🌐 Python | 📅 2026-08-18 - If your back-end and front-end are on different servers, you need this.
* [graphene-django](https://github.com/graphql-python/graphene-django) ⭐ 4,394 | 🐛 164 | 🌐 Python | 📅 2026-06-24 - GraphQL for Django.
* [django-rest-framework-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt) ⭐ 4,333 | 🐛 160 | 🌐 Python | 📅 2026-08-24 - JSON web tokens for DRF.
* [django-tastypie](https://github.com/django-tastypie/django-tastypie) ⭐ 3,946 | 🐛 411 | 🌐 Python | 📅 2026-07-27 - Creating delicious APIs for Django apps since 2010.
* [drf-yasg](https://github.com/axnsan12/drf-yasg) ⭐ 3,545 | 🐛 242 | 🌐 Python | 📅 2026-08-31 - Automated generation of real Swagger/OpenAPI 2.0 schemas from Django REST Framework code.
* [drf-spectacular](https://github.com/tfranzel/drf-spectacular) ⭐ 2,858 | 🐛 204 | 🌐 Python | 📅 2026-08-21 - Sane and flexible OpenAPI 3 schema generation for Django REST framework.
* [djoser](https://github.com/sunscrapers/djoser) ⭐ 2,680 | 🐛 201 | 🌐 Python | 📅 2026-08-01 - REST implementation of Django auth.
* [django-webpack-loader](https://github.com/django-webpack/django-webpack-loader) ⭐ 2,539 | 🐛 8 | 🌐 Python | 📅 2026-05-13 - Transparently use webpack with Django.
* [dj-rest-auth](https://github.com/iMerica/dj-rest-auth) ⭐ 1,868 | 🐛 259 | 🌐 Python | 📅 2026-06-05 - Authentication for Django Rest Framework.
* [django-modern-rest](https://github.com/wemake-services/django-modern-rest) ⭐ 1,395 | 🐛 44 | 🌐 Python | 📅 2026-08-31 - Modern REST with speed, types, async, `msgspec`, `pydantic` and other goodies!
* [django-rest-knox](https://github.com/jazzband/django-rest-knox) ⭐ 1,261 | 🐛 36 | 🌐 Python | 📅 2026-08-24 - Authentication Module for django-rest-auth.
* [strawberry-django](https://github.com/strawberry-graphql/strawberry-django) ⭐ 503 | 🐛 93 | 🌐 Python | 📅 2026-08-29 - Django integration with Strawberry, a GraphQL library designed for modern development
* [django-webhook](https://github.com/danihodovic/django-webhook) ⭐ 226 | 🐛 9 | 🌐 Python | 📅 2024-08-19 - A plug-and-play Django app for sending outgoing webhooks on model changes.
* [djaq](https://github.com/paul-wolf/djaq) ⭐ 82 | 🐛 0 | 🌐 Python | 📅 2026-06-23 - An instant remote API to Django models with a powerful query language.
* [graphene-django-filter](https://github.com/devind-team/graphene-django-filter) ⭐ 20 | 🐛 25 | 🌐 Python | 📅 2025-04-06 - Advanced filters implementing and/or/not operators in GraphQL for Django.
* [django-ninja](https://django-ninja.rest-framework.com/) - Django Ninja - Fast Django REST framework based on type annotations.

<!--lint enable double-link-->

### Async

* [channels](https://github.com/django/channels/) ⭐ 6,352 | 🐛 123 | 🌐 Python | 📅 2026-08-06 - Async support for Django.

### Caching

* [django-cacheops](https://github.com/Suor/django-cacheops) ⭐ 2,273 | 🐛 22 | 🌐 Python | 📅 2026-04-15 - A slick ORM cache with automatic granular event-driven invalidation.
* [django-cachalot](https://github.com/noripyt/django-cachalot) ⭐ 1,429 | 🐛 28 | 🌐 Python | 📅 2026-08-10 - Caches your Django ORM queries and automatically invalidates them.

### Commands

* [django-extensions](https://github.com/django-extensions/django-extensions/) ⭐ 6,813 | 🐛 219 | 🌐 Python | 📅 2026-08-31 - Custom management extensions, notably `runserver_plus` and `shell_plus`.
* [django-dbbackup](https://github.com/Archmonger/django-dbbackup) ⭐ 1,111 | 🐛 10 | 🌐 Python | 📅 2026-07-22 - Management commands to help backup and restore your project database and media files.
* [django-click](https://github.com/django-commons/django-click) ⭐ 298 | 🐛 11 | 🌐 Python | 📅 2026-08-07 - Write Django management commands using the [click CLI library](https://click.palletsprojects.com).
* [django-typer](https://github.com/django-commons/django-typer) ⭐ 273 | 🐛 19 | 🌐 Python | 📅 2026-08-12 - Write Django management commands using the [Typer CLI library](https://typer.tiangolo.com).
* [django-migration-zero](https://github.com/ambient-innovation/django-migration-zero/) ⭐ 85 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - Holistic implementation of "migration zero" pattern for Django covering local changes and in-production database adjustments.
* [django-liquidb](https://github.com/Gusakovskiy/django-liquidb) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2023-10-28 - Django application to simplify migration management and changes in states of db scheme.

### Configuration

<!--lint disable double-link-->

* [django-environ](https://github.com/joke2k/django-environ) ⭐ 3,165 | 🐛 65 | 🌐 Python | 📅 2026-08-26 - Environment variables.
* [django-constance](https://github.com/jazzband/django-constance) ⭐ 1,850 | 🐛 26 | 🌐 Python | 📅 2026-08-10 - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.
* [environs](https://github.com/sloria/environs) ⭐ 1,372 | 🐛 2 | 🌐 Python | 📅 2026-08-29 - Simplified environment variable parsing that comes with a [Django helper](https://github.com/sloria/environs#usage-with-django) ⭐ 1,372 | 🐛 2 | 🌐 Python | 📅 2026-08-29 that installs additional packages.
* [django-split-settings](https://github.com/wemake-services/django-split-settings) ⭐ 1,199 | 🐛 6 | 🌐 Python | 📅 2026-08-31 - Organize multiple settings files.
* [django-configurations](https://github.com/jazzband/django-configurations) ⭐ 1,134 | 🐛 64 | 🌐 Python | 📅 2025-12-15 - eases Django project configuration by relying on the composability of Python classes and following principles of [the twelve-factor app](https://12factor.net/config).
* [django-extra-settings](https://github.com/fabiocaccamo/django-extra-settings) ⭐ 618 | 🐛 14 | 🌐 Python | 📅 2026-08-24 - Config and manage typed extra settings using just the django admin.
* [confidential](https://github.com/candidco/confidential) ⭐ 79 | 🐛 2 | 🌐 Python | 📅 2024-11-11 - Manage configs and secrets (with CLI support).
* [django-removals](https://github.com/ambient-innovation/django-removals/) ⭐ 74 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - Detect deprecated settings variables via convenient system checks
* [dynaconf](https://www.dynaconf.com/django/) - Dynaconf loads django settings from multiple sources (multiple file formats, env vars, redis, vault, etcd), manages secrets, and allows for different merging strategies all following [the twelve-factor app](https://12factor.net/config).

<!--lint enable double-link-->

* [django-content-settings](https://github.com/occipital/django-content-settings) ⭐ 58 | 🐛 31 | 🌐 Python | 📅 2025-07-28 - Easily create and manage editable typed variables directly from the Django admin panel.
* [django-classy-settings](https://github.com/funkybob/django-classy-settings) ⭐ 38 | 🐛 2 | 🌐 Python | 📅 2026-04-17 - Class-based settings to keep your environments in order, with easy access to typed environment variables.

### Content Management Systems

<!--lint disable double-link-->

* [wagtail](https://github.com/wagtail/wagtail) ⭐ 20,471 | 🐛 1,018 | 🌐 Python | 📅 2026-08-31 - Popular Django content management system (CMS). See [awesome-wagtail](https://github.com/wagtail/awesome-wagtail) ⭐ 2,188 | 🐛 1 | 🌐 Python | 📅 2026-06-16 too.
* [django-cms](https://github.com/django-cms/django-cms) ⭐ 10,667 | 🐛 13 | 🌐 Python | 📅 2026-08-31 - CMS for Django.
* [mezzanine](https://github.com/stephenmcd/mezzanine) ⭐ 4,823 | 🐛 65 | 🌐 Python | 📅 2026-04-19 - CMS framework.
* [feincms](https://github.com/feincms/feincms) ⭐ 1,120 | 🐛 25 | 🌐 Python | 📅 2026-08-24 - An extensible Django-based CMS.
* [puput](https://github.com/APSL/puput) ⭐ 660 | 🐛 14 | 🌐 Python | 📅 2026-04-13 - Blog app features with Wagtail.

<!--lint enable double-link-->

### Database Connectors

* [djongo](https://github.com/doableware/djongo) ⭐ 1,921 | 🐛 357 | 🌐 Python | 📅 2026-08-25 - Django and MongoDB database connector.

### Dependency Injection

* [Wireup](https://github.com/maldoinc/wireup) ⭐ 432 | 🐛 18 | 🌐 Python | 📅 2026-08-29 - Dependency Injection for Django

### ECommerce

* [saleor](https://github.com/saleor/saleor) ⭐ 23,278 | 🐛 245 | 🌐 Python | 📅 2026-08-31 - GraphQL-based Django E-Commerce Platform.
* [django-oscar](https://github.com/django-oscar/django-oscar) ⭐ 6,624 | 🐛 161 | 🌐 Python | 📅 2026-08-20 - Domain-driven e-commerce for Django.

### Editors

<!--lint ignore awesome-list-item-->

* [django-tinymce](https://github.com/jazzband/django-tinymce) ⭐ 1,355 | 🐛 43 | 🌐 JavaScript | 📅 2026-08-17 - TinyMCE integration for Django.
* [django-summernote](https://github.com/lqez/django-summernote) ⭐ 1,087 | 🐛 78 | 🌐 Python | 📅 2024-06-07 - Summernote is a simple WYSIWYG editor.
* [django-markdownx](https://github.com/neutronX/django-markdownx) ⭐ 937 | 🐛 49 | 🌐 Python | 📅 2026-07-21 - Comprehensive Markdown plugin built for Django.
* [django-markdown-editor](https://github.com/agusmakmun/django-markdown-editor) ⭐ 900 | 🐛 40 | 🌐 JavaScript | 📅 2026-07-20 - Awesome Django Markdown Editor, supported for Bootstrap & Semantic-UI.
* [django-business-logic](https://github.com/dgk/django-business-logic) ⭐ 235 | 🐛 13 | 🌐 CSS | 📅 2025-03-24 - Visual DSL framework for Django.
* [django-prose](https://github.com/withlogicco/django-prose) ⭐ 221 | 🐛 5 | 🌐 Python | 📅 2026-07-21 - A lightweight editor for content creation.
* [django-ace](https://github.com/django-ace/django-ace) ⭐ 148 | 🐛 4 | 🌐 CSS | 📅 2026-05-14 - ACE integration for Django.

### Files/Images

* [django-imagekit](https://github.com/matthewwithanm/django-imagekit) ⭐ 2,349 | 🐛 93 | 🌐 Python | 📅 2026-07-12 - Django app for processing images for thumbnail, black-and-white and sizes.
* [sorl-thumbnail](https://github.com/jazzband/sorl-thumbnail) ⭐ 1,794 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Thumbnails for Django.
* [django-cleanup](https://github.com/un1t/django-cleanup) ⭐ 1,212 | 🐛 1 | 🌐 Python | 📅 2025-06-05 - Zero configuration file/image removal for local and remote files.
* [django-pictures](https://github.com/codingjoe/django-pictures) ⭐ 283 | 🐛 1 | 🌐 Python | 📅 2026-08-30 - Responsive cross-browser image library using modern codes like AVIF & WebP.

### Forms

* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms/) ⭐ 5,158 | 🐛 75 | 🌐 Python | 📅 2026-07-29 - DRY Django forms.
* [django-widget-tweaks](https://github.com/jazzband/django-widget-tweaks) ⭐ 2,163 | 🐛 48 | 🌐 Python | 📅 2026-08-24 - Tweak form field rendering in templates.
* [django-autocomplete-light](https://github.com/yourlabs/django-autocomplete-light) ⭐ 1,869 | 🐛 212 | 🌐 Python | 📅 2026-06-29 - Add autocompletion to forms.
* [django-formtools](https://github.com/jazzband/django-formtools) ⭐ 884 | 🐛 86 | 🌐 Python | 📅 2026-08-24 - For form previous and multistep forms, previously part of Django until 1.8.
* [django-floppyforms](https://github.com/jazzband/django-floppyforms) ⭐ 837 | 🐛 41 | 🌐 Python | 📅 2025-01-04 - Full control of form rendering.

### Full-stack frameworks

* [ReactPy](https://github.com/reactive-python/reactpy) ⭐ 8,153 | 🐛 51 | 🌐 Python | 📅 2026-07-14 - It's React, but in Python. Insert dynamically rendered Python into Django templates using the [ReactPy-Django module](https://github.com/reactive-python/reactpy-django) ⭐ 358 | 🐛 16 | 🌐 Python | 📅 2026-07-21.
* [Reactor](https://github.com/edelvalle/reactor/) ⭐ 638 | 🐛 18 | 🌐 Python | 📅 2025-02-10 - Phoenix LiveView, but for Django.
* [Django-Bridge](https://github.com/kaedroho/django-bridge) ⭐ 274 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-05 - The simple way to build React frontends for Django applications.
* [Django LiveView](https://github.com/Django-LiveView/liveview) ⭐ 256 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-15 - Framework for creating dynamic, reactive interfaces server-side with Django templates. Real-time updates via WebSocket with decorator-based handlers.
* [Sockpuppet](https://sockpuppet.argpar.se/) - Build reactive applications with the Django tooling you already know and love.
* [Unicorn](https://www.django-unicorn.com/) - A reactive component framework that progressively enhances a normal Django view, makes AJAX calls in the background, and dynamically updates the DOM.

### General

* [Weblate](https://github.com/WeblateOrg/weblate) ⭐ 6,045 | 🐛 500 | 🌐 Python | 📅 2026-08-31 - Weblate is a copylefted libre software web-based continuous localization system, used by over 2500 libre projects and companies in more than 165 countries.
* [django-filter](https://github.com/carltongibson/django-filter) ⭐ 4,685 | 🐛 90 | 🌐 Python | 📅 2026-07-15 - Powerful filters based on Django QuerySets.
* [django-sql-explorer](https://github.com/explorerhq/sql-explorer) ⭐ 2,877 | 🐛 49 | 🌐 Python | 📅 2025-04-23 - Share data via SQL queries.
* [django-tables2](https://github.com/jieter/django-tables2) ⭐ 2,009 | 🐛 104 | 🌐 Python | 📅 2026-08-31 - HTML tables with pagination/sorting.
* [iommi](https://github.com/iommirocks/iommi) ⭐ 1,085 | 🐛 77 | 🌐 Python | 📅 2026-08-27 - Toolkit for development of CRUD applications without writing HTML or JavaScript.
* [django-maintenance-mode](https://github.com/fabiocaccamo/django-maintenance-mode) ⭐ 527 | 🐛 5 | 🌐 Python | 📅 2026-08-24 - Shows a 503 error page when maintenance-mode is on.
* [django-data-browser](https://github.com/tolomea/django-data-browser) ⭐ 380 | 🐛 11 | 🌐 Python | 📅 2026-06-07 - Interactive, user-friendly database explorer.
* [django-freeze](https://github.com/fabiocaccamo/django-freeze) ⭐ 130 | 🐛 3 | 🌐 Python | 📅 2026-08-24 - Convert your dynamic django site to a static one with one line of code.
* [Django-Classy-Doc](https://github.com/nanuxbe/django-classy-doc) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2025-11-24 - Document your own code in the style of CCBV and CDRF.
* [django-nh3](https://github.com/marksweb/django-nh3) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2026-08-03 - Django integration with for nh3 and is an alternative for django-bleach.

### Internationalisation (i18n)

* [django-modeltranslations](https://github.com/deschler/django-modeltranslation) ⭐ 1,482 | 🐛 129 | 🌐 Python | 📅 2026-04-14 -  Translates Django models using a registration approach.
* [django-rosetta](https://github.com/mbi/django-rosetta) ⭐ 1,157 | 🐛 57 | 🌐 Python | 📅 2026-07-30 - Rosetta provides a UI to read and write your project's gettext catalogs within the Django Admin.
* [django-localflavor](https://github.com/django/django-localflavor) ⭐ 924 | 🐛 19 | 🌐 Python | 📅 2026-08-03 - A collection of functionality that is useful for particular countries or cultures. Previously a part of the Django core.
* [django-modeltrans](https://github.com/zostera/django-modeltrans) ⭐ 79 | 🐛 20 | 🌐 Python | 📅 2026-08-28 - Translate Django model fields in a JSONField.

### Logging

* [django-structlog](https://github.com/jrobichaud/django-structlog) ⭐ 530 | 🐛 11 | 🌐 Python | 📅 2026-08-10 - django-structlog is a structured logging integration for Django project using [structlog](https://www.structlog.org)
* [django-guid](https://github.com/snok/django-guid) ⭐ 485 | 🐛 17 | 🌐 Python | 📅 2026-05-05 - Inject a GUID (Correlation-ID) into every log message in a Django request.
* [DRF-API-Logger](https://github.com/vishalanandl177/DRF-API-Logger) ⭐ 344 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - An API Logger for your Django Rest Framework project.

### Monitoring

* [django-prometheus](https://github.com/django-commons/django-prometheus) ⭐ 1,665 | 🐛 101 | 🌐 Python | 📅 2026-07-30 - Export Django monitoring metrics to Prometheus.
* [django-mixin](https://github.com/adinhodovic/django-mixin) ⭐ 79 | 🐛 0 | 🌐 Jsonnet | 📅 2026-04-27 - Monitoring mixin for Django-prometheus. A set of Grafana dashboards and Prometheus rules for Django.

### Mailing

* [django-anymail](https://github.com/anymail/django-anymail) ⭐ 1,898 | 🐛 15 | 🌐 Python | 📅 2026-08-29 - Django email backends and webhooks for Amazon SES, Brevo (Sendinblue), MailerSend, Mailgun, Mailjet, Postmark, Postal, Resend, SendGrid, SparkPost, Unisender Go and more.
* [django-pony-express](https://github.com/ambient-innovation/django-pony-express) ⭐ 84 | 🐛 9 | 🌐 Python | 📅 2026-08-27 - Class-based emails including a test suite for Django.

### Model Fields

* [django-model-utils](https://github.com/jazzband/django-model-utils) ⭐ 2,760 | 🐛 124 | 🌐 Python | 📅 2026-08-17 - Django model mixins and utilities.
* [django-phonenumber-field](https://github.com/django-phonenumber-field/django-phonenumber-field) ⭐ 1,549 | 🐛 7 | 🌐 Python | 📅 2026-08-15 - Model/form field for normalized phone numbers.
* [django-colorfield](https://github.com/fabiocaccamo/django-colorfield) ⭐ 661 | 🐛 10 | 🌐 Python | 📅 2026-08-24 - Color field for django models with a nice color-picker widget.
* [django-streamfield](https://github.com/raagin/django-streamfield) ⭐ 130 | 🐛 7 | 🌐 Python | 📅 2026-01-16 - Simple StreamField for plain Django admin (based on Wagtail CMS StreamField idea).

### Models

* [django-taggit](https://github.com/jazzband/django-taggit/) ⭐ 3,448 | 🐛 114 | 🌐 Python | 📅 2026-08-24 - Simple model tags.
* [django-reversion](https://github.com/etianen/django-reversion) ⭐ 3,169 | 🐛 25 | 🌐 Python | 📅 2026-06-12 - Version control for model instances.
* [django-mptt](https://github.com/django-mptt/django-mptt) ⭐ 2,971 | 🐛 3 | 🌐 Python | 📅 2026-06-02 - Modified Preorder Tree Traversal; working with trees of Model instances.
* [django-simple-history](https://github.com/django-commons/django-simple-history) ⭐ 2,463 | 🐛 193 | 🌐 Python | 📅 2026-08-28 - Store model history and view/revert changes from the admin.
* [django-polymorphic](https://github.com/django-commons/django-polymorphic) ⭐ 1,833 | 🐛 26 | 🌐 Python | 📅 2026-08-17 - Django-polymorphic simplifies using inherited models in Django projects.
* [django-lifecycle](https://github.com/rsinger86/django-lifecycle) ⭐ 1,403 | 🐛 18 | 🌐 Python | 📅 2026-06-14 - Declarative model lifecycle hooks, an alternative to Signals.
* [django-treenode](https://github.com/fabiocaccamo/django-treenode) ⭐ 803 | 🐛 9 | 🌐 Python | 📅 2026-08-26 - Abstract model/admin for tree-based stuff.
* [django-recurrence](https://github.com/jazzband/django-recurrence) ⭐ 544 | 🐛 64 | 🌐 Python | 📅 2026-07-22 - Utility for working with recurring dates in Django.
* [django-auto-prefetch](https://github.com/adamchainz/django-auto-prefetch) ⭐ 417 | 🐛 8 | 🌐 Python | 📅 2026-08-18 - Automatically prefetch foreign key values as needed.

### Performance

* [py-spy](https://github.com/benfred/py-spy) ⭐ 15,460 | 🐛 238 | 🌐 Rust | 📅 2026-08-14 - Sampling profiler for Python programs.
* [pyinstrument](https://github.com/joerick/pyinstrument) ⭐ 8,005 | 🐛 27 | 🌐 Python | 📅 2026-08-04 - Call stack profiler for Python, Django, Flask, FastAPI.
* [django-silk](https://github.com/jazzband/django-silk) ⭐ 4,992 | 🐛 126 | 🌐 Python | 📅 2026-08-26 - Live profiling and inspection of HTTP requests and database queries.
* [django-zeal](https://github.com/taobojlen/django-zeal) ⭐ 207 | 🐛 2 | 🌐 Python | 📅 2026-08-28 - Detect N+1 queries with user-friendly error messages
* [django-perf-rec](https://cur.at/GHUO6cn?m=web) - Keep detailed records of the performance of your Django code.
* [New Relic](https://newrelic.com/python/django) - Time middleware, views, and SQL queries.
* [Scout](https://scoutapm.com/docs/python/django) - Time middleware, template rendering, and SQL queries with automatic N+1 detection.

### Permissions

* [django-guardian](https://github.com/django-guardian/django-guardian) ⭐ 3,910 | 🐛 33 | 🌐 Python | 📅 2026-08-28 - Per object permissions in Django.
* [django-rules](https://github.com/dfunckt/django-rules) ⭐ 1,976 | 🐛 41 | 🌐 Python | 📅 2025-10-11 - A tiny but powerful app providing object-level permissions, built from the ground up for Django.
* [django-role-permissions](https://github.com/vintasoftware/django-role-permissions) ⭐ 754 | 🐛 29 | 🌐 Python | 📅 2023-06-09 - Django app for role-based permissions management.

### Search

* [django-haystack](https://github.com/django-haystack/django-haystack) ⭐ 3,734 | 🐛 580 | 🌐 Python | 📅 2026-08-21 - Modular search for Django.
* [django-watson](https://github.com/etianen/django-watson) ⭐ 1,251 | 🐛 26 | 🌐 Python | 📅 2024-08-14 - Full-text search plugin.
* [django-elasticsearch-dsl](https://github.com/django-es/django-elasticsearch-dsl) ⭐ 1,056 | 🐛 145 | 🌐 Python | 📅 2025-07-23 - Elasticsearch DSL integration for Django.
* [django-admin-search](https://github.com/shinneider/django-admin-search) ⭐ 83 | 🐛 9 | 🌐 Python | 📅 2024-09-03 - Modal filter for django admin.

### Search Engine Optimisation

* [django-check-seo](https://github.com/kapt-labs/django-check-seo) ⭐ 167 | 🐛 2 | 🌐 Python | 📅 2026-03-19 - Check SEO of pages.

### Security

* [django-csp](https://github.com/mozilla/django-csp) ⭐ 624 | 🐛 11 | 🌐 Python | 📅 2025-11-14 - Adds [Content-Security-Policy](http://www.w3.org/TR/CSP/) headers to Django.
* [django-feature-policy](https://github.com/adamchainz/django-permissions-policy) ⭐ 118 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - Set the draft security HTTP header `Feature-Policy` on a Django app.
* [django-protected-media](https://github.com/cobusc/django-protected-media) ⭐ 70 | 🐛 1 | 🌐 Python | 📅 2026-01-12 - Manages media that are considered sensitive in a protected fashion.
* [DJ Checkup](https://djcheckup.com) - Runs several checks on your deployed Django site to check for common security mistakes.

### Static Assets

* [django-storages](https://github.com/jschneier/django-storages) ⭐ 2,957 | 🐛 182 | 🌐 Python | 📅 2026-08-02 - A single library to support multiple custom storage backends for Django.
* [django-compressor](https://github.com/django-compressor/django-compressor/) ⭐ 2,871 | 🐛 121 | 🌐 Python | 📅 2026-08-25 - Compress JavaScript/CSS into a single cached file.
* [whitenoise](https://github.com/evansd/whitenoise) ⭐ 2,761 | 🐛 40 | 🌐 Python | 📅 2026-08-18 - Simplified static file serving for Python websites.
* [easy-thumbnails](https://github.com/SmileyChris/easy-thumbnails) ⭐ 1,410 | 🐛 101 | 🌐 Python | 📅 2026-05-06 - Image thumbnails for Django.

### Task Queues

* [celery](https://github.com/celery/celery) ⭐ 28,842 | 🐛 758 | 🌐 Python | 📅 2026-08-29 - Robust and broker-agnostic task queues for bigger, performance-focused projects.
* [flower](https://github.com/mher/flower) ⭐ 7,238 | 🐛 156 | 🌐 Python | 📅 2026-08-16 - Flower is a web-based tool for monitoring and administrating Celery clusters.
* [huey](https://github.com/coleifer/huey) ⭐ 6,021 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - A little task queue for Python, with Django support including the new `django.tasks` API.
* [django-redis](https://github.com/jazzband/django-redis) ⭐ 3,082 | 🐛 78 | 🌐 Python | 📅 2026-08-24 - Full-featured Redis cache backend for Django.
* [django-rq](https://github.com/rq/django-rq) ⭐ 1,951 | 🐛 114 | 🌐 Python | 📅 2026-08-30 - Integration for Redis Queue.
* [django-celery-beat](https://github.com/celery/django-celery-beat) ⭐ 1,950 | 🐛 154 | 🌐 Python | 📅 2026-08-30 - A periodic task scheduler with database configured by Django's Admin Panel.
* [django-tasks](https://github.com/realOrangeOne/django-tasks) ⭐ 810 | 🐛 2 | 🌐 Python | 📅 2026-05-22 - A reference implementation and backport of background workers and tasks in Django, based on [DEP 14](https://www.djangoproject.com/weblog/2024/may/29/django-enhancement-proposal-14-background-workers/).
* [django-celery-results](https://github.com/celery/django-celery-results) ⭐ 786 | 🐛 63 | 🌐 Python | 📅 2026-08-17 - Celery result backend with Django.
* [django-q2](https://github.com/django-q2/django-q2) ⭐ 625 | 🐛 92 | 🌐 Python | 📅 2026-08-26 - A multiprocessing distributed task queue for Django.
* [celery-exporter](https://github.com/danihodovic/celery-exporter) ⭐ 559 | 🐛 44 | 🌐 Python | 📅 2026-08-31 - Prometheus & Grafana monitoring of Celery tasks.
* [django-dramatiq](https://github.com/Bogdanp/django_dramatiq) ⭐ 384 | 🐛 19 | 🌐 Python | 📅 2026-05-10 - Task processing library with a focus on simplicity, reliability, and performance.

### Templates

* [django-components](https://github.com/django-components/django-components/) ⭐ 1,517 | 🐛 35 | 🌐 Python | 📅 2026-08-24 - A way to create simple reusable template components in Django.
* [django-template-partials](https://github.com/carltongibson/django-template-partials/) ⭐ 655 | 🐛 1 | 🌐 Python | 📅 2025-11-20 - Reusable named inline partials for the Django Template Language.
* [django-suspense](https://github.com/paqstd-dev/django-suspense) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-07-20 - Easy way to display a fallback in templates until children have finished loading (like React).
* [slippers](https://mitchel.me/slippers/) - Build reusable components in Django without writing a single line of Python.
* [JinjaX](https://jinjax.scaletti.dev/) - Super components powers for your Jinja templates.
* [django-cotton](https://django-cotton.com/) - Goodbye `{% raw %}{%{% endraw %} extends, block, include {% raw %}%}{% endraw %}`, Hello `<c-component />`. Bringing modern UI composition to Django.
* [htpy](https://htpy.dev/) - htpy is a library that makes writing HTML in plain Python fun and efficient, without a template language.

### Testing

* [django-debug-toolbar](https://github.com/django-commons/django-debug-toolbar/) ⭐ 8,378 | 🐛 82 | 🌐 Python | 📅 2026-08-30 - Configurable panels to debug requests/responses.
* [factory-boy](https://github.com/FactoryBoy/factory_boy) ⭐ 3,805 | 🐛 211 | 🌐 Python | 📅 2026-01-01 - Test fixtures replacement.
* [pytest-django](https://github.com/pytest-dev/pytest-django) ⭐ 1,546 | 🐛 188 | 🌐 Python | 📅 2026-08-10 - Use pytest features in Django.
* [django-waffle](https://github.com/django-waffle/django-waffle) ⭐ 1,257 | 🐛 59 | 🌐 Python | 📅 2026-06-07 - A feature flipper for Django.
* [model-bakery](https://github.com/model-bakers/model_bakery) ⭐ 1,002 | 🐛 13 | 🌐 Python | 📅 2026-08-24 - Object factory for Django (rename of legacy Model Mommy project).
* [django-test-plus](https://github.com/revsys/django-test-plus/) ⭐ 632 | 🐛 4 | 🌐 Python | 📅 2026-08-02 - Useful additions to Django's default TestCase.
* [django-test-migrations](https://github.com/wemake-services/django-test-migrations) ⭐ 575 | 🐛 15 | 🌐 Python | 📅 2026-08-31 - Test django schema and data migrations, including migrations' order.
* [django-pattern-library](https://github.com/torchbox/django-pattern-library) ⭐ 424 | 🐛 95 | 🌐 Python | 📅 2026-08-26 - Pattern library generator for Django templates, to help testing of UI components.
* [storybook-django](https://github.com/torchbox/storybook-django) ⭐ 121 | 🐛 8 | 🌐 JavaScript | 📅 2026-02-10 - Develop Django UI components in isolation, with Storybook.
* [django-fakery](https://github.com/fcurella/django-fakery) ⭐ 116 | 🐛 4 | 🌐 Python | 📅 2024-07-07 - An easy-to-use implementation of Creation Methods for Django, backed by Faker.

### URLs

* [dj-database-url](https://github.com/jazzband/dj-database-url) ⭐ 1,572 | 🐛 12 | 🌐 Python | 📅 2026-08-25 - Database URLs.
* [django-robots](https://github.com/jazzband/django-robots) ⭐ 475 | 🐛 23 | 🌐 Python | 📅 2026-08-17 - This is a basic Django application to manage robots.txt files following the robots exclusion protocol, complementing the Django Sitemap contrib app.
* [urlman](https://github.com/andrewgodwin/urlman) ⭐ 124 | 🐛 0 | 🌐 Python | 📅 2025-12-23 - A nicer way to do URLs for Django models.
* [django-redirects](https://github.com/fabiocaccamo/django-redirects) ⭐ 79 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - Redirects as they should be, with full control.

### Users

* [django-allauth](https://github.com/pennersr/django-allauth/) ⭐ 10,374 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - Improved user registration including social auth.
* [django-organizations](https://github.com/bennylope/django-organizations/) ⭐ 1,364 | 🐛 25 | 🌐 Python | 📅 2026-08-17 - Multi-user accounts for Django projects.
* [django-allauth-ui](https://github.com/danihodovic/django-allauth-ui/) ⭐ 401 | 🐛 29 | 🌐 HTML | 📅 2026-02-14 - Better-looking templates for django-allauth.
* [django-cas-ng](https://github.com/django-cas-ng/django-cas-ng) ⭐ 392 | 🐛 11 | 🌐 Python | 📅 2026-08-09 - Django-cas-ng is Django CAS (Central Authentication Service) 1.0/2.0/3.0 client library to support SSO (Single Sign On) and Single Logout (SLO).
* [django-improved-user](https://github.com/jambonrose/django-improved-user) ⭐ 159 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - A custom Django user that authenticates via email. Follows identity and authentication best practices.
* [django-guest-user](https://github.com/julianwachholz/django-guest-user) ⭐ 79 | 🐛 4 | 🌐 Python | 📅 2024-01-27 - Allow visitors to use your site like a regular user and register later.

### Views

* [django-braces](https://github.com/brack3t/django-braces) ⭐ 2,018 | 🐛 9 | 🌐 Python | 📅 2025-03-18 - Reusable, generic mixins.
* [django-extra-views](https://github.com/AndrewIngram/django-extra-views) ⭐ 1,437 | 🐛 16 | 🌐 Python | 📅 2025-04-28 - Extra class-based generic views.
* [django-easy-audit](https://github.com/soynatan/django-easy-audit) ⭐ 845 | 🐛 108 | 🌐 Python | 📅 2026-08-11 - Keep track of user actions.
* [neapolitan](https://github.com/carltongibson/neapolitan) ⭐ 706 | 🐛 26 | 🌐 Python | 📅 2026-03-15 - Quick CRUD views for Django.
* [django-stronghold](https://github.com/mgrouchy/django-stronghold) ⭐ 396 | 🐛 13 | 🌐 Python | 📅 2024-11-24 - Makes all your Django views default login\_required.

## Developer Tools

Standalone tools that help in developing Django projects.

### Templates

* [curlylint](https://www.curlylint.org/) - Experimental HTML templates linting for Jinja, Nunjucks, Django templates, Twig, Liquid.
* [djhtml](https://github.com/rtts/djhtml) ⭐ 643 | 🐛 6 | 🌐 Python | 📅 2026-04-17 - Django/Jinja template indenter.
* [djlint](https://www.djlint.com/) - Lint & Format HTML Templates.

## Python Packages

*A short list of Python packages that work well with Django.*

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,408 | 🐛 2,160 | 🌐 Rust | 📅 2026-08-31 - An extremely fast Python linter and code formatter, written in Rust.
* [black](https://github.com/psf/black) ⭐ 41,825 | 🐛 311 | 🌐 Python | 📅 2026-08-20 - Uncompromising Python code formatter.
* [faker](https://github.com/joke2k/faker) ⭐ 19,385 | 🐛 33 | 🌐 Python | 📅 2026-08-21 - Faker is a Python package that generates fake data for you.
* [pytest](https://github.com/pytest-dev/pytest/) ⭐ 14,462 | 🐛 808 | 🌐 Python | 📅 2026-08-31 - Testing framework.
* [pillow](https://github.com/python-pillow/Pillow) ⭐ 13,793 | 🐛 173 | 🌐 Python | 📅 2026-08-31 - Python Imaging Library.
* [python-socketio](https://github.com/miguelgrinberg/python-socketio) ⭐ 4,367 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Python implementation of the Socket.IO\_ realtime client and server. [(create Socket.io Django server instance)](https://python-socketio.readthedocs.io/en/latest/server.html?highlight=django#creating-a-server-instance)
* [coveragepy](https://github.com/coveragepy/coveragepy) ⭐ 3,409 | 🐛 305 | 🌐 Python | 📅 2026-08-31 - Code coverage measurement.
* [python-decouple](https://github.com/HBNetwork/python-decouple) ⭐ 3,038 | 🐛 22 | 🌐 Python | 📅 2024-11-28 - Strict separation of settings from code.
* [sentry-python](https://github.com/getsentry/sentry-python) ⭐ 2,202 | 🐛 406 | 🌐 Python | 📅 2026-08-31 - Error reporting SDK.
* [python-slugify](https://github.com/un33k/python-slugify) ⭐ 1,624 | 🐛 17 | 🌐 Python | 📅 2026-04-27 - Returns unicode slugs.

## Resources

### Official Resources

<!--lint ignore double-link-->

* [Source Code](https://github.com/django/django/) ⭐ 89,298 | 🐛 482 | 🌐 Python | 📅 2026-08-29 - Hosted on GitHub.
* [Project Website](https://www.djangoproject.com/) - Official Django website.
* [Documentation](https://docs.djangoproject.com/en/dev/) - Comprehensive documentation for all Django versions.
* [Polls Tutorial](https://docs.djangoproject.com/en/dev/intro/tutorial01/) - Build a polls tutorial while learning Django internals.

### Educational

* [Django Styleguide](https://github.com/HackSoftware/Django-Styleguide) ⭐ 6,285 | 🐛 5 | 🌐 Python | 📅 2025-09-25 - Styleguide for Django with best practices and examples.
* [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) - Use function-based views to build a blog app.
* [LearnDjango](https://learndjango.com/) - Tutorials and premium courses on Django and Django REST Framework.
* [Adam Johnson](https://adamj.eu/tech/) - Adam is on the Technical Board of Django and regularly writes tutorials.
* [Photon Designer - Django tutorials](https://photondesigner.com/articles) - Django tutorials by Tom Dekan on how to build Django apps simply - from how to build an instant messenger with Django, add instant search, to using Google Drive as a database. Updated regularly.
* [TestDriven](https://testdriven.io/blog/) - Multiple Django-specific tutorials on topics like Docker, payments, and more.
* [Classy Class-Based Views](https://ccbv.co.uk/) - Detailed descriptions of methods/properties/attributes for each generic class-based view.
* [Classy Django REST Framework](http://www.cdrf.co) - Detailed descriptions with methods/attributes for DRF class-based views and serializers.
* [Simple is Better than Complex](https://simpleisbetterthancomplex.com/) - Regularly updated website with many tutorials and tips on Django.
* [Full Stack Python's Django Page](https://www.fullstackpython.com/django.html) - Explanation of Django philosophy and links to other resources and tutorials.
* [RealPython](https://realpython.com/tutorials/django/) - Many high-quality tutorials on Django.
* [Mozilla Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) - Create a lending library app.
* [Matt Layman](https://www.mattlayman.com) - Regular tutorials and deep-dives on Django topics.
* [Django Template Tags and Filters](https://www.djangotemplatetagsandfilters.com/) - Additional docs on Django's 57 built-in template filters and 27 template tags.
* [Django for Everybody](https://www.dj4e.com/) - A complete course for webdev beginners focused on Django.
* [CS50W](https://cs50.harvard.edu/web/2020/) - Harvard's University introductory course to web development, it explains Django as backend framework.
* [Better Simple](https://www.better-simple.com/blog/django/) - Articles from Tim Schilling about Django development, best practices, and the Django ecosystem.

### Community

<!--lint disable double-link-->

* [Django Forum](https://forum.djangoproject.com/) - Official Discourse board.
* [Community Page](https://www.djangoproject.com/community/) - Featuring feeds of Community Blog Posts, Jobs, and more.
* [Local Django Communities Page](https://www.djangoproject.com/community/local/) - Featuring local events all around the world.
* [Django Users Google Group](https://groups.google.com/forum/#!forum/django-users/) - Very active discussion board for questions/answers.
* [Developers Google Group](https://groups.google.com/forum/#!forum/django-developers/) - For contributions to Django itself only.
* [Mastodon](https://fosstodon.org/@django) - For official announcements on updates, security fixes, etc.
* [X (formerly Twitter)](https://x.com/djangoproject/) - For official announcements on updates, security fixes, etc.
* [Discord Server](https://discord.com/invite/xcRH6mN4fa) - Django Discord Community.
* IRC Channel - Chat with other Django users at irc://irc.freenode.net/django.
* [Djangonaut Space](https://djangonaut.space) - Free peer-mentoring program for the Django community to launch people into the universe of open source contributions.

<!--lint enable double-link-->

### Conferences

* [DjangoCon US](https://djangocon.us/) ([YouTube Channel](https://www.youtube.com/channel/UC0yY6a79pPY9J0ShIHRf6yw))
* [DjangoCon Europe](https://djangocon.eu/) ([YouTube Channel](https://www.youtube.com/user/djangoconeurope))
* [DjangoCon AU](https://djangocon.com.au/)
* [DjangoCon Africa](https://djangocon.africa/)
* [Django Day Copenhagen](https://djangoday.dk/) ([YouTube Channel](https://www.youtube.com/@djangodanmark))
* [PyCon US](https://us.pycon.org/) ([YouTube Channel](https://www.youtube.com/channel/UCsX05-2sVSH7Nx3zuk3NYuQ))
* [PyCon Australia](https://pycon-au.org/) ([YouTube Channel](https://www.youtube.com/user/PyConAU))
* [Euro Python](https://europython.eu/) ([YouTube Channel](https://www.youtube.com/user/PythonItalia))
* [Django Under the Hood](https://www.youtube.com/channel/UC9T1dhIlL_8Va9DxvKRowBw/videos)
* [DjangoCongress JP](https://djangocongress.jp/) ([YouTube Channel](https://www.youtube.com/@djangocongressjp3623))
* [Complete listing of all PyCons globally](https://pycon.org)

### Job Boards

* [Django Job Board](https://djangojobboard.com/) - A Django job board that also aggregates other job boards. Formerly Django News Jobs.
* [Django Jobs](https://djangojobs.net) - Django jobs posting for hiring Django Python developers.
* [Python.org Job Boards](https://www.python.org/jobs/) - While not exclusively for Django, this job board is hosted by the official Python website and features a range of Python and Django-related job opportunities.

### Newsletters

* [Django News](https://django-news.com) - Weekly newsletter on announcements, articles, projects, and talks.

### Podcasts

* [Django Chat](https://djangochat.com/) - A weekly podcast from William Vincent and Django Fellow Carlton Gibson with discussions of core Django concepts and regular guests.
* [Django Brew](https://djangobrew.com/) - A fun, caffeine-powered podcast about the Django web framework by Adam Hill and Sangeeta Jadoonanan.
* [TalkPython](https://talkpython.fm/) - The leading Python podcast with occassional episodes on Django.
* [Running in Production](https://runninginproduction.com/tags/django) - No longer active, but a great backlog of episodes on Django tech stacks.

### Videos

* [DjangoTV](https://djangotv.com) - Your source for Django conference videos and tutorials.
* [PyVideo](https://pyvideo.org) - PyVideo is an index of Python related media.

### Books

For a complete listing of in-print books, check out [DjangoBook.com](https://djangobook.com/).

*Django 5*

* [Django for APIs, Fifth Edition](https://learndjango.com/courses/django-for-apis/)
* [Boost Your Django DX](https://adamchainz.gumroad.com/l/byddx)
* [Django 5 By Example](https://www.packtpub.com/en-us/product/django-5-by-example-9781805125457)
* [Django in Action](https://www.manning.com/books/django-in-action)
* [Django for Beginners, Fifth Edition](https://learndjango.com/courses/django-for-beginners/)

## Hosting

### PaaS (Platforms-as-a-Service)

* [Appliku](https://appliku.com)
* [Dokku](https://dokku.com)
* [Divio](https://www.divio.com)
* [Fly](https://fly.io)
* [Google Cloud](https://cloud.google.com/python/django/)
* [Heroku](https://www.heroku.com)
* [Microsoft Azure](https://azure.microsoft.com/en-us/develop/python/)
* [Piku](https://github.com/piku/piku) ⭐ 6,603 | 🐛 6 | 🌐 Python | 📅 2026-08-10
* [Upsun](https://upsun.com)
* [PythonAnywhere](https://www.pythonanywhere.com)
* [Railway](https://railway.app)
* [Render](https://render.com)
* [Vercel](https://vercel.com/home)

### IaaS (Infrastructure-as-a-Service)

* [Digital Ocean](https://www.digitalocean.com)
* [Linode](https://www.linode.com)
* [Amazon Lightsail](https://aws.amazon.com/lightsail/)
* [Hetzner](https://www.hetzner.com)

## Projects

### Boilerplate

* [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django/) ⭐ 13,605 | 🐛 117 | 🌐 Python | 📅 2026-08-31 - A full-bodied starter project, highly customizable.
* [djangox](https://github.com/wsvincent/lithium/) ⭐ 2,462 | 🐛 13 | 🌐 Python | 📅 2026-04-09 - Batteries included starter project for Pip, Pipenv, or Docker.
* [wemake-django-template](https://github.com/wemake-services/wemake-django-template/) ⭐ 2,271 | 🐛 21 | 🌐 Python | 📅 2026-08-31 - Bleeding-edge Django template focused on code quality and security.
* [django-react-boilerplate](https://github.com/vintasoftware/django-react-boilerplate) ⭐ 2,271 | 🐛 20 | 🌐 Python | 📅 2026-05-04 - A Django, React, Tailwind, Webpack project boilerplate
* [django-base-site](https://github.com/epicserve/django-base-site/) ⭐ 451 | 🐛 2 | 🌐 Python | 📅 2026-08-29 - A Django site with many common third-party packages pre-installed.
* [Falco](https://github.com/falcopackages/falco-cli) ⭐ 390 | 🐛 7 | 🌐 Python | 📅 2026-06-15 - Enhance your Django developer experience: CLI and Guides for the Modern Django Developer.
* [django-startproject](https://github.com/jefftriplett/django-startproject) ⭐ 279 | 🐛 2 | 🌐 Just | 📅 2026-08-17 - Django start project template with batteries.
* [sidewinder](https://github.com/stribny/sidewinder/) ⭐ 235 | 🐛 5 | 🌐 Python | 📅 2025-09-04 - A Django starter kit that focuses on good defaults, developer experience, and deployment.
* [cookiecutter-vue-django](https://github.com/ilikerobots/cookiecutter-vue-django) ⭐ 231 | 🐛 4 | 🌐 Python | 📅 2023-11-20 - Django + Vue starter project fusing Vue SFCs & Django Templates.
* [django-docker-template](https://github.com/amerkurev/django-docker-template) ⭐ 229 | 🐛 3 | 🌐 Python | 📅 2025-04-19 - Dockerized Django with Postgres, Gunicorn, and Traefik (with auto-renew Let's Encrypt).
* [BH2](https://codeberg.org/trey/bh2) - Get a new Django site started in a Djiffy

### Open Source Projects

* [PostHog](https://github.com/PostHog/posthog) ⭐ 39,494 | 🐛 5,247 | 🌐 Python | 📅 2026-08-31 - Open-source product analytics.
* [Zulip](https://github.com/zulip/zulip/) ⭐ 25,799 | 🐛 2,056 | 🌐 Python | 📅 2026-08-31 - Open-source team chat.
* [linkding](https://github.com/sissbruecker/linkding) ⭐ 11,123 | 🐛 200 | 🌐 Python | 📅 2026-08-18 - Self-hosted bookmark manager that is designed to be minimal, fast, and easy to set up using Docker.
* [Healthchecks](https://github.com/healthchecks/healthchecks) ⭐ 10,293 | 🐛 53 | 🌐 Python | 📅 2026-08-31 - A Cron Monitoring Tool written in Python & Django.
* [Flagsmith](https://github.com/Flagsmith/flagsmith) ⭐ 6,535 | 🐛 708 | 🌐 Python | 📅 2026-08-31 - Open-source Feature Flagging, Remote Config, and AB testing.
* [Baserow](https://github.com/baserow/baserow) ⭐ 5,753 | 🐛 1,223 | 🌐 Python | 📅 2026-08-31 - Open source no-code database and Airtable alternative built with Django and Vue.js.
* [Bootcamp: An enterprise social network](https://github.com/vitorfs/bootcamp) ⭐ 2,302 | 🐛 25 | 🌐 CSS | 📅 2023-10-01
* [OpenContracts](https://github.com/Open-Source-Legal/OpenContracts) ⭐ 1,458 | 🐛 15 | 🌐 Python | 📅 2026-08-31 - Enterprise-grade document analytics platform that combines automated PDF parsing, vector embeddings, and LLM integration.
* [Blog app with users and forms](https://github.com/wsvincent/djangoforbeginners/tree/master/ch7-blog-app-with-users/) ⭐ 1,386 | 🐛 3 | 🌐 JavaScript | 📅 2025-03-22
* [Newspaper app with custom user model, full user auth](https://github.com/wsvincent/djangoforbeginners/tree/master/ch15-comments) ⭐ 1,386 | 🐛 3 | 🌐 JavaScript | 📅 2025-03-22
* [django-job-portal](https://github.com/manjurulhoque/django-job-portal) ⭐ 623 | 🐛 2 | 🌐 Python | 📅 2026-08-03 - Job portal application using Django.
* [Django CRM Admin](https://github.com/DjangoCRM/django-crm) ⭐ 619 | 🐛 6 | 🌐 Python | 📅 2026-08-26 - Open source Python CRM built entirely on Django Admin Site.
* [pythonic-news](https://github.com/sebst/pythonic-news) ⭐ 542 | 🐛 20 | 🌐 Python | 📅 2022-12-08 - Hacker News clone.
* [Image Sharing Blog](https://github.com/MeNsaaH/soMedia) ⭐ 105 | 🐛 6 | 🌐 Python | 📅 2024-08-04
* [Behavior-Driven Development with Aloe](https://github.com/testdrivenio/django-aloe-bdd/) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2023-02-15
* [Built with Django](https://builtwithdjango.com) - Curated list of awesome Django projects.
* [HyperKitty](https://gitlab.com/mailman/hyperkitty) - A web interface to access GNU Mailman v3 archives.

## Django REST Framework

*The most popular way to build web APIs with Django.*

### DRF Resources

<!--lint disable double-link-->

* [DRF Source Code](https://github.com/encode/django-rest-framework) ⭐ 30,149 | 🐛 59 | 🌐 Python | 📅 2026-08-25
* [awesome-django-rest-framework](https://github.com/nioperas06/awesome-django-rest-framework) ⭐ 1,471 | 🐛 1 | 📅 2026-07-03
* [Official Documentation](https://www.django-rest-framework.org/)

<!--lint enable double-link-->

### DRF Tutorials

<!--lint ignore double-link-->

* [Official REST Framework - A Beginner's Guide](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)
* [Building APIs with Django and DRF](https://books.agiliq.com/projects/django-api-polls-tutorial/en/latest/)
* [DRF with React](https://www.valentinog.com/blog/drf/)
* [Making React and Django play well together](https://fractalideas.com/blog/making-react-and-django-play-well-together/)

## Wagtail

*Wagtail, the powerful CMS for modern websites.*

### Wagtail Resources

<!--lint disable double-link-->

* [Wagtail Source Code](https://github.com/wagtail/wagtail/) ⭐ 20,471 | 🐛 1,018 | 🌐 Python | 📅 2026-08-31
* [awesome-wagtail](https://github.com/wagtail/awesome-wagtail) ⭐ 2,188 | 🐛 1 | 🌐 Python | 📅 2026-06-16
* [Official website](https://wagtail.org/)
* [Developer documentation](https://docs.wagtail.org/en/stable/)
* [User documentation](https://guide.wagtail.org/en-latest/)
* [This week in Wagtail](https://wagtail.org/this-week-in-wagtail/) - A (most) weekly email with updates from the Wagtail core team.
* [Wagtail Space](https://www.wagtail.space/) - Wagtail conferences around the world.
* [Wagtail events](https://wagtail.org/events/) - Online and in-person Wagtail events.

<!--lint enable double-link-->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._
