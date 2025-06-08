readme_content_clean = """# 👋 Cześć, jestem Jakub Firkowski

## 📱 Specjalizacje

- Kotlin (Jetpack Compose, MVVM)
- Android App Development
- PHP (API, cookies, sesje)
- Bazy danych: MySQL
- Git / GitHub

---

## 📫 Kontakt

- 📧 Email: [jakubfirko@gmail.com](mailto:jakubfirko@gmail.com)
- 💬 Discord: `Kubusiowy#1234`

---



# Zapisujemy plik
readme_path_clean = Path("/mnt/data/README_profesjonalny.md")
readme_path_clean.write_text(readme_content_clean, encoding='utf-8')

readme_path_clean.name
