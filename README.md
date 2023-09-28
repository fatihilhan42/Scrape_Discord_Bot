# Scrape_Discord_Bot
Bu proje, Python kullanarak oluşturulan bir Discord botunu içerir. Bot, belirli web sitelerinden veri kazıma işlemini otomatize eder ve Discord sunucusunda verilen komutlarla kazılmış olan verileri belirtilen mail adreslerine gönderir. 

# Discord Bot Projesi

Bu proje, Discord API'si kullanarak bir Discord botu oluşturmayı amaçlayan bir Python uygulamasını içerir.

## Proje Açıklaması

Bu Discord botu, çeşitli web sitelerinden veri kazıma işlemini otomatize ederek kazıdığı verileri Discord sunucusundaki kanallarda veya özel mesajlarda paylaşabilir. Botun temel işlevleri şunları içerir:

- Belirli web sitelerinden veri kazıma işlemini otomatikleştirme.
- Kazıdığı verileri düzenleyerek bir Excel dosyasına kaydetme.
- Verileri belirli kullanıcılara veya sunucu kanallarına gönderme.

## Kullanım

Botun kullanımı oldukça basittir. Aşağıdaki adımları izleyebilirsiniz:

1. Discord Botunu Ekleyin:
   - Botunuzu bir Discord sunucusuna eklemek için aşağıdaki bağlantıyı kullanabilirsiniz: [Bot Ekleme Bağlantısı](https://discord.com/oauth2/authorize?client_id=YOUR_BOT_CLIENT_ID&scope=bot&permissions=YOUR_PERMISSIONS)
   - `YOUR_BOT_CLIENT_ID` ve `YOUR_PERMISSIONS` yerine botunuzun istemci kimliğini ve izinlerini eklemelisiniz.

2. Komutları Kullanın:
   - Botunuzun kullanabileceği komutları kullanarak veri kazıma işlemini başlatın ve sonuçları alın.

Örnek komutlar:
   - `!scrape`: Web kazıma işlemini başlatır.
   - `!shutdown`: Botu kapatır.

## Gereksinimler

Projenin çalışması için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:

- discord.py
- requests
- BeautifulSoup
- pandas
- smtplib
- email.mime

Gerekli kütüphaneleri yüklemek için aşağıdaki komutları kullanabilirsiniz:

```python
pip install discord.py requests beautifulsoup4 pandas
```

## Teşekkürler

Bu proje, büyük çaba ve işbirliği gerektiren bir çalışmanın ürünüdür. Bu yüzden projenin geliştirilmesine katkıda bulunan dostum [Yusuf Çınarcı](https://github.com/yusufcinarci)'ya özel teşekkürlerimi sunmak isterim. Yusuf, bu projede harika bir iş çıkardı ve işbirliği yapmak gerçekten keyifliydi.

Yusuf'un GitHub profilini ziyaret etmek ve diğer projelerini incelemek için [buraya tıklayın](https://github.com/yusufcinarci).

Projeye katkılarından dolayı Yusuf'a minnettarım!


## Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, lütfen bir çekme isteği (pull request) göndermekten çekinmeyin. Projeye katkı sağlamak için aşağıdaki adımları takip edebilirsiniz:

1. Bu depoyu (repository) çatallayın (fork).
2. Yeni bir özellik eklemek veya hata düzeltmeleri yapmak için bir dal (branch) oluşturun.
3. Değişikliklerinizi bu yeni dalda yapın.
4. Çekme isteği (pull request) gönderin.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LİSANS](LICENSE) dosyasına başvurun.


