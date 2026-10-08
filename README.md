# ae69-docs

Технические документы (PDF: чертежи, каталоги производителей) для сайта
AE69 B2B (Freon717/ae69-b2b-app). Сайт открывает их через jsDelivr:
`https://cdn.jsdelivr.net/gh/Freon717/ae69-docs@<коммит>/tech-docs/<файл>`.
В сборку сайта эти файлы не входят (у Grok лимит сборки 30 МБ).

- `tech-docs/` — бывшая папка `public/tech-docs` сайта; имена файлов те же,
  в коде сайта ссылки остаются вида `/tech-docs/<файл>`.

Новый документ: положить файл в `tech-docs/`, запушить и вписать новый
коммит в `DOCS_MIRROR_REF` (`src/lib/doc-src.ts` в репозитории сайта),
обновить список `src/lib/catalog/tech-docs-files.ts`.
