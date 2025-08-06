POSitiveApp Update

# 1. Eski tag'ý temizle
git tag -d POSitiveApp-Update
git push --delete origin POSitiveApp-Update

# 2. Dosyayý ekle ve commitle
git add "D:\#__Project\POSitiveApp\POSitiveApp\Master\POSitiveApp_Update.7z"
git commit -m "Update POSitiveApp_Update.7z"
git push origin main

# 3. Yeni tag oluþtur
git tag -a POSitiveApp-Update -m "POSitiveApp güncelleme paketi"
git push origin POSitiveApp-Update