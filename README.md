# pustaya-lavka

Простой статический сайт. Инструкции по деплою на GitHub Pages:

1. Создайте новый репозиторий на GitHub (например `pustaya-lavka`).
2. В локальной папке проекта выполните:

```powershell
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. На GitHub: Settings → Pages → Source: `main` branch (root) → Save. Через несколько минут сайт будет доступен по адресу `https://<your-username>.github.io/<repo-name>`.

Если хотите — можно использовать `gh` (GitHub CLI) для автоматизации:

```powershell
gh repo create <repo-name> --public --source=. --remote=origin --push
```

Если нужна помощь с пушем или созданием репозитория — скажите, помогу.
