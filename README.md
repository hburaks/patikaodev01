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

### Branchleri Merge Etme
- `git checkout developer` komutu ile developer branch ine geçildi 
- `git merge feature` komutu ile feature branchi developer branchine merge edildi.
- `git branch -d feature` komutu ile feature branchi silindi.
- `git push origin :feature` komutu ile feature branchinin silindiği githuba bildirildi.
- `git push origin developer` komutu ile developer branchine merge edildiği githuba bildirildi.

- `git checkout main` komutu ile main branch ine geçildi 
- `git merge developer` komutu ile developer branchi main branchine merge edildi.

### Hotfix branchi oluşturma
- Ünlü harfle başlayan kelimelerden oluşan bir paragraf oluşturulmadığı fark edildi.
- `git branch hotfix` komutu ile hotfix branchi oluşturuldu.
- `git checkout hotfix` komutu ile hotfix branchine geçildi.
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.