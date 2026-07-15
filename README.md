@'
# 🐦 n8n Automation Project

Bu depo, Docker üzerinde çalışan kişisel **n8n** altyapımı ve geliştirdiğim otomasyon projelerini barındırır.

## 📁 Projeler
### 1. Twitter (X) to Telegram RSS Bot
Belirlenen bir Twitter (X) kullanıcısının paylaşımlarını takip eden ve yeni bir tweet atıldığında Telegram üzerinden bildirim gönderen otomatik iş akışı.

- **Dinamik Veri Çekme:** Twitter API engellerinden etkilenmemek için `xcancel.com` RSS altyapısı kullanılır.
- **JavaScript ile Tekilleştirme:** n8n'in kalıcı hafızasını kullanan özel JS kodu sayesinde Telegram kutunuza mükerrer mesajların gitmesi önlenir.

## 📦 Kurulum ve Çalıştırma
1. Docker konteynerlerini ayağa kaldırın:
   ```bash
   docker-compose up -d
