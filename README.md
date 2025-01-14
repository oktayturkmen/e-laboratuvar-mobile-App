# **E-Lab Mobile App**

## **Proje Özeti**  
E-Lab Yönetim Sistemi, laboratuvar süreçlerini dijitalleştirmek ve yönetim süreçlerini kolaylaştırmak için geliştirilmiş yenilikçi bir platformdur.  
Sistem, doktorlar ve hastalar için kullanıcı dostu bir arayüz sunarak, laboratuvar işleyişini daha hızlı ve verimli hale getirir.  

### **Özellikler**  
- **Doktorlar**:  
  - Yeni hasta ekleyebilir.  
  - Hastaların tahlil sonuçlarını görüntüleyebilir.  
  - Yeni test sonuçları ekleyebilir ve kılavuzlar yardımıyla analiz yapabilir.  
- **Hastalar**:  
  - Test sonuçlarını inceleyebilir.  
  - Geçmiş verileri görebilir ve sağlık durumlarını takip edebilir.  

---

## **Projenin Amacı**  
Bu projenin temel amacı, laboratuvar süreçlerini dijitalleştirerek hızlı, güvenilir ve kullanıcı dostu bir çözüm sunmaktır.  

- **Kullanıcı Deneyimi İyileştirme**: Doktorlar ve hastalar için kolay erişilebilir bir platform oluşturma.  
- **Yönetim Süreçlerinin Optimizasyonu**: Laboratuvarların işleyişinde zaman ve maliyet tasarrufu sağlama.  

---

## **Gerçekleştirilen Özellikler**  

### **1. Yönetici Modülü (Admin)**  
- **Hasta Yönetimi**:  
  Yeni hasta ekleme, mevcut hastaları düzenleme ve silme işlemleri.  
- **Test Sonuçları Yönetimi**:  
  Hastaların test sonuçlarını ekleme, düzenleme ve kılavuzlara göre analiz etme.  
- **Kılavuz Yönetimi**:  
  Laboratuvar test kılavuzlarının oluşturulması, güncellenmesi ve silinmesi.  

### **2. Hasta Modülü (User)**  
- **Geçmiş Test Sonuçlarını Görüntüleme**:  
  Hasta, geçmiş test sonuçlarını liste olarak görebilir ve sonuçların zaman içindeki değişimini grafiklerle analiz edebilir.  
- **Test Sonuçları Arama**:  
  Test adını seçerek ilgili sonuçları ve zaman içindeki değişimleri inceleyebilir.  
- **Profil Yönetimi**:  
  Kullanıcı, kişisel bilgilerini görüntüleyebilir ve güncelleyebilir.  

---

## **Kullanılan Teknolojiler**  

### **Frontend**  
- **React Native**: Hem iOS hem de Android cihazlarını destekleyen kullanıcı arayüzü geliştirme.  
- **React Native Paper**: Modern ve kullanıcı dostu tasarımlar için UI bileşenleri.  

### **Backend**  
- **Firebase Firestore**: Gerçek zamanlı veri senkronizasyonu sağlayan veritabanı.  
- **Firebase Authentication**: Kullanıcı kimlik doğrulama işlemleri.  

---

## **Kurulum**  

### **Gereksinimler**  
- Node.js  
- Expo CLI  
- Firebase hesabı  

### **Adımlar**  
1. Depoyu klonlayın ve bağımlılıkları yükleyin:  
   ```bash
   git clone https://github.com/oktayturkmen/e-laboratuvar-mobile-App.git
   cd e-laboratuvar-mobile-App
   npm install

