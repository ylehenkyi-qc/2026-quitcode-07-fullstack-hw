# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: ylehenkyi-qc
- Ваше репо: https://github.com/ylehenkyi-qc/property-workflows
- SHA: 289f53f192d5a190224b52eb9bcdd400fa2d5af6
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://pmwp-ylehenkyi.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/ylehenkyi-qc/property-workflows/pull/9
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/ylehenkyi-qc/property-workflows/pull/22
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/35, https://github.com/solomchaak/property-workflows-spec/issues/36 (власні; PM відповів і закрив обидва, а також питання колег #21–#34, #37, #38, на які спиралась реалізація)
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/ylehenkyi-qc/property-workflows/pull/13 (також уточнення після відповідей PM: https://github.com/ylehenkyi-qc/property-workflows/pull/23)
- Дизайн-система — PR (B): https://github.com/ylehenkyi-qc/property-workflows/pull/15
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/DESIGN.md · джерело: AI-чат: Claude Code
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40694213527
- Знімки «до/після» (B): https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-before-runs-dark.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-after-runs-dark.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-before-runs-light.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-after-runs-light.png
- Зміна `impl-<зріз2>` (C): https://github.com/ylehenkyi-qc/property-workflows/tree/289f53f192d5a190224b52eb9bcdd400fa2d5af6/openspec/changes/archive/2026-10-28-impl-templates-editor
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/ylehenkyi-qc/property-workflows/pull/16, https://github.com/ylehenkyi-qc/property-workflows/pull/18, https://github.com/ylehenkyi-qc/property-workflows/pull/20, https://github.com/ylehenkyi-qc/property-workflows/pull/25, https://github.com/ylehenkyi-qc/property-workflows/pull/26, https://github.com/ylehenkyi-qc/property-workflows/pull/29
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40544394081 (AC-EDITOR-02, AC-EDITOR-07, AC-EDITOR-08), https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40548027474 (AC-EDITOR-08, AC-EDITOR-09), https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40550894079 (AC-TASK-16, AC-TASK-18), https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40570157152 (AC-EDITOR-12, AC-EDITOR-26), https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40575868933 (AC-EDITOR-15, AC-EDITOR-20)
- ADR (D): https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/decisions/0002-template-versions.md, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/decisions/0003-template-validation.md
- Архітектурне правило, крім `check:design` (D): job «Секретний ключ лише на сервері» (`check:boundary`, `.github/workflows/architecture.yml`), червоний прогін на порушенні (секретний ключ у коді): https://github.com/ylehenkyi-qc/property-workflows/actions/runs/40544394168 (PR https://github.com/ylehenkyi-qc/property-workflows/pull/17)
- Акаунти для PM (E): pm-admin@example.test (admin), pm-manager@example.test (manager). Паролі — PM у чаті, не тут
- Скріни за ролями (E): https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-admin-templates.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-admin-template.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-admin-editor.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-manager-templates.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-manager-runs.png, https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/docs/img/ws7-role-manager-denied.png
- AC зрізу 2 (E): як у `docs/conformance.md` на SHA — реалізовано (59 з 67): AC-RUN-01…12, AC-TASK-01…18, AC-DSYS-01, AC-DSYS-02, AC-DSYS-03, AC-DSYS-04, AC-DSYS-08, AC-EDITOR-01…12, AC-EDITOR-14…20, AC-EDITOR-23, AC-EDITOR-25, AC-EDITOR-26, AC-EDITOR-28, AC-EDITOR-29; відкладено (8): AC-EDITOR-13 (діалог видалення є, але «Cancel» без DOM-тестів не перевірити), AC-EDITOR-21, AC-EDITOR-22, AC-EDITOR-24 (назва шаблону належить версії — зміна моделі даних і міграція, не вмістили в строк; рішення PM solomchaak/property-workflows-spec#29, #30), AC-EDITOR-27 (поведінку забезпечує бекфіл міграції, тест «запуск до міграції» неможливий; solomchaak/property-workflows-spec#33), AC-DSYS-05, AC-DSYS-06, AC-DSYS-07 (вибір теми System/Light/Dark не реалізовано, тема лише за системою; solomchaak/property-workflows-spec#34)
- Відхилення від PM (E): не надходило

## Бонус

—
