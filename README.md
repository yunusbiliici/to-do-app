# To-Do App

Basit ve kullanıcı dostu bir arayüze sahip, görevlerinizi yönetmenizi sağlayan bir To-Do (Yapılacaklar Listesi) uygulaması. Bu proje, Node.js ve Express kullanılarak oluşturulmuştur ve `public` klasöründeki statik dosyaları sunar.

## ✨ Özellikler

*   **Görev Ekleme:** Listeye yeni görevler ekleyin.
*   **Görevleri Listeleme:** Tüm görevlerinizi tek bir yerde görüntüleyin.
*   **Görevleri Güncelleme:** Görevleri tamamlandı olarak işaretleyin.
*   **Görev Silme:** Artık ihtiyaç duymadığınız görevleri listeden kaldırın.

## 🛠️ Kullanılan Teknolojiler

*   **Backend:** Node.js, Express.js
*   **Frontend:** HTML, CSS, JavaScript (Statik olarak sunulur)

## 🚀 Kurulum ve Başlatma

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin.

### Gereksinimler

*   Node.js (LTS sürümü önerilir)
*   npm (Node.js ile birlikte gelir)

### Adımlar

1.  **Projeyi klonlayın:**
    (Eğer bir Git reposu kullanıyorsanız, `kullanici-adiniz/todo-app` kısmını kendi bilgilerinizle güncelleyin.)
    ```bash
    git clone https://github.com/kullanici-adiniz/todo-app.git
    ```

2.  **Proje dizinine gidin:**
    ```bash
    cd todo-app
    ```

3.  **Gerekli paketleri yükleyin:**
    (Projenizde `express` gibi bağımlılıklar olduğunu varsayarak)
    ```bash
    npm install
    ```

4.  **Uygulamayı başlatın:**
    ```bash
    node index.js
    ```
    *Öneri: `package.json` dosyanıza bir `start` betiği ekleyerek `npm start` komutuyla da çalıştırabilirsiniz:*
    ```json
    "scripts": {
      "start": "node index.js"
    }
    ```

5.  **Uygulamayı açın:**
    Tarayıcınızda `http://localhost:3000` adresine gidin.

## 📂 Proje Yapısı

```
todo-app/
├── public/              # Frontend dosyaları (HTML, CSS, JS)
│   ├── index.html
│   ├── style.css
│   └── script.js
├── node_modules/        # Yüklenen npm paketleri
├── index.js             # Express sunucu dosyası
├── package.json         # Proje bilgileri ve bağımlılıklar
├── package-lock.json
└── README.md            # Proje dökümantasyonu
```

## 🤝 Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyin:

1.  Projeyi fork'layın.
2.  Yeni bir özellik dalı oluşturun (`git checkout -b ozellik/yeni-ozellik`).
3.  Değişikliklerinizi commit'leyin (`git commit -m 'Yeni bir özellik eklendi'`).
4.  Dalınızı push'layın (`git push origin ozellik/yeni-ozellik`).
5.  Bir Pull Request açın.

## 📄 Lisans
