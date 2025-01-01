# Rent A Car Uygulaması 🚗  

Bu proje, araç kiralama işlemleri için bir backend API geliştirme uygulamasıdır. **Django** ve **Django REST Framework** ile oluşturulmuştur. Kullanıcı kimlik doğrulaması ve API yönetimi gibi modern özellikler içermektedir.  

## Özellikler  
- **Kullanıcı Yönetimi:** Kullanıcı kayıt, giriş ve kimlik doğrulama.  
- **REST API:** Django REST Framework ile hızlı ve güvenilir API.  
- **Token Authentication:** Kullanıcı oturumlarını yönetmek için token tabanlı kimlik doğrulama.  
- **Pagination:** API sonuçlarında sayfalama desteği.  

## Teknolojiler ve Bağımlılıklar  
- Python  
- Django 4.2.2  
- Django REST Framework 3.14.0  
- dj-rest-auth 4.0.1  
- python-decouple  

## Kurulum  
1. Projeyi klonlayın:  
   ```bash
   git clone https://github.com/KullaniciAdin/rent-a-car.git
Sanal bir ortam oluşturun ve bağımlılıkları yükleyin:

bash
Copy code
python -m venv venv  
source venv/bin/activate  
pip install -r requirements.txt  
Django uygulamasını başlatın:

bash
Copy code
python manage.py runserver  
API Kullanımı
Projenin temel uç noktalarına erişmek için http://127.0.0.1:8000/ adresini kullanabilirsiniz. Örneğin:

Kullanıcı İşlemleri: /user/
Araç Kiralama İşlemleri: /api/cars/
Katkıda Bulunma
Projeye katkıda bulunmak için pull request oluşturabilir veya bir issue açabilirsiniz.

Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
