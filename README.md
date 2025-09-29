# yengec-eticaret-sistemi
Harika! Şimdi size **ayyildizmeltem38-a11y** hesabınız için **adım adım** repository kurulumunu göstereyim:

## 🎯 **GITHUB REPOSITORY KURULUM ADIMLARI**

### **1️⃣ GitHub'da Yeni Repository Oluşturun**

1. [GitHub.com](https://github.com/ayyildizmeltem38-a11y) hesabınıza girin
2. Yeşil **"New"** butonuna tıklayın
3. **Repository name:** `yengec-eticaret-sistemi`
4. **Description:** `XML tabanlı çoklu pazaryeri ürün yönetim sistemi`
5. **Public** seçin
6. ✅ **Add a README file** işaretleyin
7. **Create repository** tıklayın

### **2️⃣ Dosya Yapısını Oluşturun**

GitHub'da **"Add file" → "Create new file"** ile şu dosyaları oluşturun:

## 📁 **DOSYA HAZIRLAMA LİSTESİ**

### **📄 1. README.md** (Kök dizine)
```markdown
# 🛍️ Yengeç E-ticaret Yönetim Sistemi

XML tabanlı çoklu pazaryeri ürün yönetim sistemi

## 🚀 Kurulum

```bash
git clone https://github.com/ayyildizmeltem38-a11y/yengec-eticaret-sistemi.git
cd yengec-eticaret-sistemi

# Frontend
cd frontend
npm install
npm start

# Backend  
cd ../backend
pip install -r requirements.txt
uvicorn server:app --host 0.0.0.0 --port 8001
```

## ✨ Özellikler

- XML kaynak yönetimi
- Otomatik fiyatlandırma (×1.20 + 105 TL)
- 5 pazaryeri desteği
- API entegrasyonları

## 🌐 Giriş: test@yengec.co / 123456
```

### **📄 2. frontend/package.json**
Action: file_editor view /app/frontend/package.json
Observation: /app/frontend/package.json:
1|{
2|  "name": "frontend",
3|  "version": "0.1.0",
4|  "private": true,
5|  "dependencies": {
6|    "@hookform/resolvers": "^5.0.1",
7|    "@radix-ui/react-accordion": "^1.2.8",
8|    "@radix-ui/react-alert-dialog": "^1.1.11",
9|    "@radix-ui/react-aspect-ratio": "^1.1.4",
10|    "@radix-ui/react-avatar": "^1.1.7",
11|    "@radix-ui/react-checkbox": "^1.2.3",
12|    "@radix-ui/react-collapsible": "^1.1.8",
13|    "@radix-ui/react-context-menu": "^2.2.12",
14|    "@radix-ui/react-dialog": "^1.1.11",
15|    "@radix-ui/react-dropdown-menu": "^2.1.12",
16|    "@radix-ui/react-hover-card": "^1.1.11",
17|    "@radix-ui/react-label": "^2.1.4",
18|    "@radix-ui/react-menubar": "^1.1.12",
19|    "@radix-ui/react-navigation-menu": "^1.2.10",
20|    "@radix-ui/react-popover": "^1.1.11",
21|    "@radix-ui/react-progress": "^1.1.4",
22|    "@radix-ui/react-radio-group": "^1.3.4",
23|    "@radix-ui/react-scroll-area": "^1.2.6",
24|    "@radix-ui/react-select": "^2.2.2",
25|    "@radix-ui/react-separator": "^1.1.4",
26|    "@radix-ui/react-slider": "^1.3.2",
27|    "@radix-ui/react-slot": "^1.2.0",
28|    "@radix-ui/react-switch": "^1.2.2",
29|    "@radix-ui/react-tabs": "^1.1.9",
30|    "@radix-ui/react-toast": "^1.2.11",
31|    "@radix-ui/react-toggle": "^1.1.6",
32|    "@radix-ui/react-toggle-group": "^1.1.7",
33|    "@radix-ui/react-tooltip": "^1.2.4",
34|    "axios": "^1.8.4",
35|    "class-variance-authority": "^0.7.1",
36|    "clsx": "^2.1.1",
37|    "cmdk": "^1.1.1",
38|    "cra-template": "1.2.0",
39|    "date-fns": "^4.1.0",
40|    "embla-carousel-react": "^8.6.0",
