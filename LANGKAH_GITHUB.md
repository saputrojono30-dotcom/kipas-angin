# Build APK lewat GitHub (dari nol)

1. Buat akun/masuk github.com. Buat repositori baru (New repository), nama bebas, centang "Add a README" TIDAK perlu.
2. Unggah isi folder ini (bukan zip-nya): Add file > Upload files > seret semua file dan folder di sini (app, build.gradle.kts, settings.gradle.kts, gradle.properties, dst). Commit changes.
3. File workflow: kalau folder `.github` tidak ikut terunggah, buat manual: Add file > Create new file,
   nama file: .github/workflows/build-apk.yml
   isi: salin dari SALIN_KE_.github_workflows_build-apk.yml.txt. Commit changes.
4. Tab Actions (di HP: More > Actions) > Build APK > Run workflow.
5. Setelah centang hijau: buka run-nya > Artifacts > unduh DLMS-S3-Control-debug-apk > ekstrak > app-debug.apk.
