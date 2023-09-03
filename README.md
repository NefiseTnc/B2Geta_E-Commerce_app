
![Logo](https://github.com/NefiseTnc/flutter_movies_app/assets/100851004/5c1279df-74af-4ce5-8d0d-9abc7df9f460)

    
# E-Ticaret Uygulaması 🛍️📦

Proje genel olarak Flutter teknolojisi ile yazılmış android ve ios platformlarına yönelik bir mobil e-ticaret uygulamasıdır.İçerik olarak kullanıcıların üye olup içersinde kendi firmalarını oluşturup ürünlerini ekleyip, bir çok varyasyonda paylaşım yapabildikleri aynı zamanda kendi içinde alışveriş yapabildikleri bir sosyal platform ve e-ticaret'in hibrik şeklinde yer aldığı mobil uygulamasıdır.

Bu proje gelişmeye devam etmektedir.
## Ekran Görüntüleri

![Uygulama Ekran Görüntüsü](https://github.com/NefiseTnc/flutter_movies_app/assets/100851004/1b3af8d2-ce78-4adf-a5dc-14b91307d271 | width=100)

  
## Özellikler

- Light/Dark tema geçişi
- 2 Dil Desteği (English–Turkish)
- Üye olup giriş yapma
- Firma listeleme/ekleme/güncelleme
- Ürün listeleme/ekleme/güncelleme/silme
- Ürün arama
- Ürün detayı görüntüleme
- Sepete ürün ekleme/güncelleme/listeleme/silme
- Sosyal platform (post/story/reels paylaşma/listeleme, takip etme/takipten çıkma/takipçileri listeleme, Post/Reels beğenme/yorum yapma)
- Sipariş oluşturma/listeleme
- Siparişe anlaşmazlık oluşturma/listeleme
- Firmaya mesaj atma özelliği


  
## Kullanılan Teknolojiler

**Client:** Flutter

**Database:** RESTful API

**Architecture:** MVC

**State Managment:** Provider,GetX

**Networking:** http 

**Localization:** GetX

**Networking:** http 

**Local Storage:** Shared Preferences

**Dependency Injection:** GetX

**Payment System:** iyzico





  
## Proje Klasör Yapısı
```
📦 lib
├─ enums
│  └─ user_enums.dart
├─ languages
│  ├─ en.dart
│  └─ tr.dart
├─ models
│  ├─ basket
│  │  └─ basket_model.dart
│  ├─ categories
│  │  ├─ category_feature_model.dart
│  │  └─ category_model.dart
│  ├─ company
│  │  ├─ company_detail_model.dart
│  │  └─ company_model.dart
│  ├─ follow
│  │  ├─ my_follower_model.dart
│  │  └─ my_following_model.dart
│  ├─ ..
│  │  ├─ ..
│  │  └─ ..
│  └─ ..
│     └─ ..
├─ providers
│  ├─ basket
│  │  └─ basket_page_provider.dart
│  ├─ company_profile
│  │  └─ company_profile_page_provider.dart
│  ├─ explore
│  │  └─ explore_page_provider.dart
│  ├─ home
│  │  └─ home_page_provider.dart
│  ├─ login_register
│  │  └─ login_register_page_provider.dart
│  ├─ marketplace
│  │  └─ marketplace_page_provider.dart
│  ├─ ..
│  │  └─ ..
│  ├─ ..
│  ├─ ..
│  └─ theme_provider.dart
├─ services
│  ├─ agreement
│  │  └─ agreement_services.dart
│  ├─ basket
│  │  └─ basket_services.dart
│  ├─ categories
│  │  └─ categories_services.dart
│  ├─ order
│  │  └─ order_services.dart
│  ├─ ..
│  ├─ ..
│  ├─ general_services.dart
│  └─ theme_services.dart
├─ views
│  ├─ basket
│  │  └─ basket_page.dart
│  ├─ custom
│  │  ├─ custom_pages
│  │  │  ├─ custom_comment_page.dart
│  │  │  ├─ custom_post_page.dart
│  │  │  ├─ custom_reels_page.dart
│  │  │  └─ custom_story_page.dart
│  │  └─ custom_widgets
│  │     ├─ custom_appbar_widget.dart
│  │     ├─ custom_button_widget.dart
│  │     ├─ custom_gallery_widget.dart
│  │     └─ custom_inner_appbar_widget.dart
│  ├─ explore
│  │  └─ explore_page.dart
│  ├─ home
│  │  ├─ sub_pages
│  │  │  ├─ story_add_sub_page.dart
│  │  │  └─ upload_steps_sub_page.dart
│  │  └─ home_page.dart
│  ├─ login_register
│  │  ├─ sub_pages
│  │  │  ├─ clarification_text_sub_page.dart
│  │  │  ├─ membership_agreement_sub_page.dart
│  │  │  ├─ password_verify_sub_page.dart
│  │  │  ├─ privacy_policy_sub_page.dart
│  │  │  ├─ reset_password_sub_page.dart
│  │  │  └─ verify_sub_page.dart
│  │  ├─ login_page.dart
│  │  ├─ register_page.dart
│  │  └─ language_page.dart
│  ├─ marketplace
│  │  ├─ sub_pages
│  │  │  ├─ product_list_sub_page.dart
│  │  │  ├─ product_detail_sub_page.dart
│  │  │  └─ ..
│  │  └─ marketplace_page.dart
│  ├─ ..
│  │  ├─ ..
│  │  │  └─ ..
│  │  └─ ..
│  ├─ ..
│  │  ├─ ..
│  │  └─ ..
│  ├─ ..
│  │  └─ ..
│  ├─ ..
│  ├─ navigation_page.dart
│  ├─ search_page.dart
│  └─ splash_page.dart
├─ app_languages.dart
├─ app_theme.dart
├─ constants.dart
├─ locator.dart
├─ main.dart
├─ utils.dart
```

## 
Copyright © 2023 B2GETA. Tüm Hakları Saklıdır.
  
