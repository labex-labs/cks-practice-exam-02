# Практический экзамен CKS 02

**Языки:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ru/courses/cks-practice-exam-02">
    <img src="https://course-cover.labex.io/cks-practice-exam-02.png?lang=ru" alt="Практический экзамен CKS 02">
  </a>
</p>

Второй независимый практический экзамен в стиле CKS, включающий 20 задач по безопасности Kubernetes, которые охватывают все ключевые области CKS через различные сценарии операционной безопасности.

[Начать курс на LabEx](https://labex.io/ru/courses/cks-practice-exam-02)

## Упражнения

|   Индекс | Название                                              | Сложность   | Практика                                                                                                                                             |
|----------|-------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | Запрет доступа рабочей нагрузки к метаданным узла     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02'>Начать испытание</a>     |
|       02 | Анализ результатов CIS для выявления уязвимостей K... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02'>Начать испытание</a>  |
|       03 | Перевыпуск TLS для разделенного маршрута Ingress      | Средний     | <a target='_blank' href='https://labex.io/ru/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02'>Начать испытание</a>     |
|       04 | Ограничение прав оператора пространства имен          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02'>Начать испытание</a>           |
|       05 | Изоляция скомпрометированного токена ServiceAccoun... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02'>Начать испытание</a>     |
|       06 | Блокировка эскалации через прокси-сервер API-серве... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02'>Начать испытание</a>         |
|       07 | Отключение отладочной службы хоста                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02'>Начать испытание</a>              |
|       08 | Ограничение прав доступа сборщика логов хоста         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02'>Начать испытание</a>   |
|       09 | Применение границ безопасности Pod для арендатора     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02'>Начать испытание</a>      |
|       10 | Ротация и ограничение секретов приложения             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02'>Начать испытание</a>  |
|       11 | Изоляция исходящего трафика арендатора с помощью и... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02'>Начать испытание</a> |
|       12 | Удаление кэша hostPath из веб-пода                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02'>Начать испытание</a>      |
|       13 | Принудительное использование доверенных реестров о... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02'>Начать испытание</a>          |
|       14 | Проверка подписанного манифеста релиза                | Средний     | <a target='_blank' href='https://labex.io/ru/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02'>Начать испытание</a>        |
|       15 | Удаление секретов сборки из образа                    | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02'>Начать испытание</a>        |
|       16 | Сканирование вывода Helm с помощью KubeLinter         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02'>Начать испытание</a>          |
|       17 | Восстановление политики на основе данных аудита       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02'>Начать испытание</a>        |
|       18 | Изоляция подозрительной рабочей нагрузки (Quaranti... | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02'>Начать испытание</a>           |
|       19 | Обнаружение отклонений файлов во время выполнения     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02'>Начать испытание</a>                 |
|       20 | Изоляция скомпрометированного токена задания          | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02'>Начать испытание</a>           |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

