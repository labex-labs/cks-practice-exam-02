# Практический экзамен CKS 02

## Языки

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Практический экзамен CKS 02](https://course-cover.labex.io/cks-practice-exam-02.png?lang=ru)](https://labex.io/ru/courses/cks-practice-exam-02)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ru/courses/cks-practice-exam-02)

Второй независимый практический экзамен в стиле CKS, включающий 20 задач по безопасности Kubernetes, которые охватывают все ключевые области CKS через различные сценарии операционной безопасности.

![kubernetes](https://img.shields.io/badge/kubernetes-whitesmoke?style=for-the-badge&logo=kubernetes)
![cks](https://img.shields.io/badge/cks-whitesmoke?style=for-the-badge&logo=cks)


## Упражнения

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                                                             |
|----------|----------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  Запрет доступа рабочей нагрузки к метаданным узла     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02'>Начать Испытание</a>     |
|       02 | 🎯  Анализ результатов CIS для выявления уязвимостей K... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02'>Начать Испытание</a>  |
|       03 | 🎯  Перевыпуск TLS для разделенного маршрута Ingress      | Средний     | <a target='_blank' href='https://labex.io/ru/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02'>Начать Испытание</a>     |
|       04 | 🎯  Ограничение прав оператора пространства имен          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02'>Начать Испытание</a>           |
|       05 | 🎯  Изоляция скомпрометированного токена ServiceAccoun... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02'>Начать Испытание</a>     |
|       06 | 🎯  Блокировка эскалации через прокси-сервер API-серве... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02'>Начать Испытание</a>         |
|       07 | 🎯  Отключение отладочной службы хоста                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02'>Начать Испытание</a>              |
|       08 | 🎯  Ограничение прав доступа сборщика логов хоста         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02'>Начать Испытание</a>   |
|       09 | 🎯  Применение границ безопасности Pod для арендатора     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02'>Начать Испытание</a>      |
|       10 | 🎯  Ротация и ограничение секретов приложения             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02'>Начать Испытание</a>  |
|       11 | 🎯  Изоляция исходящего трафика арендатора с помощью и... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02'>Начать Испытание</a> |
|       12 | 🎯  Удаление кэша hostPath из веб-пода                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02'>Начать Испытание</a>      |
|       13 | 🎯  Принудительное использование доверенных реестров о... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02'>Начать Испытание</a>          |
|       14 | 🎯  Проверка подписанного манифеста релиза                | Средний     | <a target='_blank' href='https://labex.io/ru/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02'>Начать Испытание</a>        |
|       15 | 🎯  Удаление секретов сборки из образа                    | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02'>Начать Испытание</a>        |
|       16 | 🎯  Сканирование вывода Helm с помощью KubeLinter         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02'>Начать Испытание</a>          |
|       17 | 🎯  Восстановление политики на основе данных аудита       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02'>Начать Испытание</a>        |
|       18 | 🎯  Изоляция подозрительной рабочей нагрузки (Quaranti... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02'>Начать Испытание</a>           |
|       19 | 🎯  Обнаружение отклонений файлов во время выполнения     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02'>Начать Испытание</a>                 |
|       20 | 🎯  Изоляция скомпрометированного токена задания          | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02'>Начать Испытание</a>           |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

## Больше

- 🔗 [Обучение CKS Курсы программирования](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [Обучение CKS Проекты программирования](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Обучение CKS Бесплатные туториалы](https://github.com/labex-labs/cks-free-tutorials)

