# NoteHub — routing (Next.js)

Next.js (App Router) + TanStack Query + Formik/Yup.

- `/notes/filter/[...slug]` — список нотаток з фільтром за тегом (`all` = без фільтра)
- `@sidebar` — паралельний маршрут з меню тегів
- `@modal/(.)notes/[id]` — перехоплений маршрут: модальне вікно з деталями нотатки
- `/notes/[id]` — повна сторінка нотатки (при прямому заході / оновленні)

## Запуск

1. `npm install`
2. Створіть `.env` з `.env.example` і вкажіть `NEXT_PUBLIC_NOTEHUB_TOKEN`
3. `npm run dev`
