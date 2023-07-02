# Router Yapılandırması

Bu belge, bir router'ın nasıl yapılandırılacağını adım adım açıklamaktadır. Router, ağ trafiğini yönlendiren ve ağa bağlı cihazlar arasında iletişimi sağlayan bir ağ cihazıdır.

## İçindekiler

1. [Giriş](#giriş)
2. [Adım 1: Router'ı Fiziksel Olarak Bağlama](#adım-1-routerı-fiziksel-olarak-bağlama)
3. [Adım 2: Router'ı Yapılandırma](#adım-2-routerı-yapılandırma)
   - 2.1 [IP Adresi Atama](#21-ip-adresi-atama)
   - 2.2 [Kablosuz Ağ Yapılandırması](#22-kablosuz-ağ-yapılandırması)
   - 2.3 [Şifre Ayarları](#23-şifre-ayarları)
4. [Adım 3: Ağ Ayarlarının Test Edilmesi](#adım-3-ağ-ayarlarının-test-edilmesi)
5. [Örnek IP Adresleri ve Router İletişimi](#örnek-ip-adresleri-ve-router-iletişimi)
6. [Sonuç](#sonuç)
7.[Lisans](#lisans)
## Giriş

Bu belge, bir router'ın nasıl yapılandırılacağını adım adım açıklamaktadır. Herhangi bir router markası veya modeli kullanabilirsiniz, ancak örneklerde genel bir yaklaşım benimsenmiştir. İşte router'ın doğru bir şekilde yapılandırılması için izlenmesi gereken adımlar:

## Adım 1: Router'ı Fiziksel Olarak Bağlama

Router'ı ağınıza bağlamadan önce aşağıdaki adımları takip edin:

1. Router'ı güç kaynağına takın ve açın.
2. Modem veya ana ağ kaynağına gelen ağ kablosunu router'ın WAN (Wide Area Network) veya Internet portuna bağlayın.
3. Bilgisayarınızı router'ın bir LAN (Local Area Network) portuna bağlayın.

## Adım 2: Router'ı Yapılandırma

Router'ı yapılandırmak için aşağıdaki adımları izleyin:

### 2.1 IP Adresi Atama

1. Bir web tarayıcısı açın ve adres çubuğuna "192.168.1.1" (genellikle varsayılan router IP adresi) yazın.
2. Tarayıcı sizi router'ın yönetim arayüzüne yönlendirecektir. Giriş yapmanız istenebilir. (Kullanıcı adı ve şifre, router markası/modeline bağlı olarak değişebilir.)
3. Yönetim arayüzünde, ağ ayarları veya ağ yapılandırması gibi bir seçenek bulunmalıdır. Bu seçeneği tıklayın.
4. IP adresi bölümünde, router'ın yeni IP adresini ayarlayın. Örneğin, "192.168.2.1" gibi başka bir IP adresi seçebilirsiniz.
5. Ayarları kaydedin ve router'ı yeniden başlatın.

### 2.2 Kablosuz Ağ Yapılandırması

1. Yönetim arayüzünde, kablosuz ayarlar veya kablosuz ağ yapılandırması gibi bir seçeneği tıklayın.
2. Kablosuz ağı etkinleştirin.
3. Kablosuz ağ adını (SSID) belirleyin. Örneğin, "MyWiFi" gibi bir ad seçebilirsiniz.
4. Kablosuz güvenlik ayarlarını seçin. WPA2-PSK (Wi-Fi Protected Access 2 - Pre-Shared Key) genellikle en güvenli seçenektir. Bir şifre belirleyin.
5. Ayarları kaydedin ve router'ı yeniden başlatın.

### 2.3 Şifre Ayarları

1. Yönetim arayüzünde, şifre ayarları veya yönetici şifresi gibi bir seçeneği tıklayın.
2. Yönetici şifresini değiştirin. Güçlü ve benzersiz bir şifre seçin.
3. Ayarları kaydedin ve router'ı yeniden başlatın.

## Adım 3: Ağ Ayarlarının Test Edilmesi

1. Bilgisayarınızda bir web tarayıcısı açın ve herhangi bir web sitesini ziyaret edin. İnternet bağlantısının çalıştığından emin olun.
2. Kablosuz ağa bağlanmak için diğer cihazlarınızı kullanın ve internet erişimini test edin.

## Örnek IP Adresleri ve Router İletişimi

Aşağıda, İstanbul şubesindeki IP adresleri ve Kütahya şubesindeki IP adresleri için bir örnek verilmiştir:

- İstanbul Şubesi:
  - Router IP Adresi: 192.168.1.1
  - IP Adres Aralığı: 192.168.1.100 - 192.168.1.200

- Kütahya Şubesi:
  - Router IP Adresi: 192.168.2.1
  - IP Adres Aralığı: 192.168.2.100 - 192.168.2.200

İki şube arasında iletişim kurmak için aşağıdaki adımları izleyebilirsiniz:

1. İstanbul şubesindeki router'ın yönetim arayüzüne 192.168.1.1 IP adresini kullanarak erişin.
2. Yönetim arayüzünde, "Yönlendirme" veya "Routing" gibi bir seçeneği tıklayın.
3. Yeni bir yönlendirme kurmak için "Yeni Ekle" veya "Add New" gibi bir seçeneği tıklayın.
4. Hedef IP adresini (Kütahya şubesinin IP adresi olan 192.168.2.0) ve hedef ağ maskesini (örneğin 255.255.255.0) girin.
5. Gateway veya yönlendirici IP adresini (Kütahya şubesindeki router'ın IP adresi olan 192.168.2.1) girin.
6. Ayarları kaydedin ve router'ı yeniden başlatın.

Bu şekilde, İstanbul şubesindeki cihazlar Kütahya şubesindeki cihazlara erişebilir ve iletişim kurabilir.

## Sonuç

Bu adımları takip ederek router'larınızı başarılı bir şekilde yapılandırabilir ve şubeler arasında iletişimi sağlayabilirsiniz. Router'ların yönetim arayüzü ve ayarları, marka ve modele bağlı olarak değişebilir. Kullanıcı kılavuzunuza başvurarak markanızın spesifik adımlarını kontrol etmek her zaman iyi bir fikirdir.

## Lisans 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Bu projeyi [MIT Lisansı](https://opensource.org/licenses/MIT) altında lisansladık. Lisansın tam açıklamasını burada bulabilirsiniz.
