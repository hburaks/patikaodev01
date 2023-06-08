# Temel GIT Eğitimi Ödevi 
~Main branch'ta README dosyası oluşturuldu.
- `git add README.md` komutu ile git'in dosyayı takip etmesi sağlandı.
- `git commit -m "README.md dosyası oluşturuldu."` komutu ile değişiklikler commit edildi.
- `git push` ile proje remote repository' e gönderildi.~

### Branch Oluşturma
- `git branch` komutu ile mevcut branch kontrol edildi.
Aktif olan branch, yıldız (*) işaretiyle gösterilecektir.

- `git branch developer` komutu ile yeni bir branch oluşturuldu.
- `git checkout developer` komutu ile developer branch 'ına geçildi.
- `git commit -m "Developer Branch'i içierisinde branch oluşturma açıklamaları README.md dosyasına yazıldı."`

### Feature Branchi Oluşturma

- `git branch feature` komutu ile yeni bir branch oluşturuldu.
- `git checkout feature` komutu ile feature branch 'ına geçildi.

Tüm **ünlü** harfle başlayan kelimeler vurgulanacak şekilde bir paragraf **eklendi.**

- `git commit -m "Feature Branch'i içerisinde branch oluşturma açıklamaları README.md dosyasına yazıldı."` komutu ile değişiklikler commit edildi.
- `git push origin feature` ile remote repository'de de branch oluşturulup değişiklikler eklendi.

### Branchleri merge etme
- `git checkout developer` komutu ile developer branch ine geçildi 
- `git merge feature` komutu ile feature branchi developer branchine merge edildi.
- `git branch -d feature` komutu ile feature branchi silindi.
- `git push origin :feature` komutu ile feature branchinin silindiği githuba bildirildi.
- `git push origin developer` komutu ile developer branchine merge edildiği githuba bildirildi.
