POSitiveApp Update

# 1. Eski tag'� temizle
git tag -d POSitiveApp-Update
git push --delete origin POSitiveApp-Update

# 2. Dosyay� ekle ve commitle
git add "D:\#__Project\POSitiveApp\POSitiveApp\Master\POSitiveApp_Update.7z"
git commit -m "Update POSitiveApp_Update.7z"
git push origin main

# 3. Yeni tag olu�tur
git tag -a POSitiveApp-Update -m "POSitiveApp g�ncelleme paketi"
git push origin POSitiveApp-Update