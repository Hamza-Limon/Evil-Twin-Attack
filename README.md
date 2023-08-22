# Evil-Twin-Attack

<div align="center">
	<img width="770" height='500' alt="image" src="https://github.com/Hamza-Limon/Evil-Twin-Attack/assets/140405710/290b67e5-c663-4389-801b-c4216a3ee103">
</div>

### Evil-Twin Saldırısı:
Evil Twin (Kötü İkiz) saldırısı temel olarak bir MITM (Man in the Middle – Ortadaki Adam) saldırısıdır. Bir evil twin saldırısında saldırganın amacı internete bağlanan bir cihaz ve o interneti yayan modem arasına girmektir. Saldırgan bunu yapabilmek için kendini interneti yayan modem gibi gösterir ve gerçek modeme Deauth Saldırısı uygular. Gerçek modem deauth saldırısından dolayı internet yayamayacak durumda olduğundan internete bağlanan cihaz sahte modeme, saldırgana bağlanır. Evil twin saldırısı aynı zamanda Fake AP (Fake Access Point – Sahte Erişim Noktası) adıyla da geçmektedir.


- İşte Evil Twin saldırısının çalışma şekli:

##### Ağ Taklit Edilir: Saldırgan, hedefin bağlanmak istediği kablosuz ağı (örneğin, kafe, otel veya halka açık bir ağ) taklit etmek için aynı SSID (Service Set Identifier) adını kullanır. Bu, hedefin sahte ağı gerçek ağla karıştırmasını kolaylaştırır.

##### Hedef Bağlanır: Hedef, cihazının kablosuz ağı arayarak ve bağlanmak istediği ağı seçerek sahte ağa bağlanır. Hedef, bu ağı gerçek kablosuz ağla karıştırabilir veya sahte ağın sinyali daha güçlü olduğu için otomatik olarak bağlanabilir.

##### Tüm Trafik Saldırgan Üzerinden Geçer: Hedef sahte ağa bağlandığında, tüm ağ trafiği sahte ağ üzerinden geçer. Saldırgan, bu trafiği izleyebilir, kaydedebilir veya manipüle edebilir.

##### Giriş Bilgileri Çalınabilir: Eğer hedef, sahte ağ üzerinden giriş yapmaya çalışıyorsa (örneğin, bir web sitesine kullanıcı adı ve şifre ile giriş yapmaya çalışıyorsa), saldırgan bu giriş bilgilerini çalabilir.

##### Evil Twin saldırıları, halka açık Wi-Fi ağlarının kullanılması durumunda özellikle tehlikeli olabilir çünkü bu tür ağlara bağlanan kullanıcılar, sahte ağı gerçek ağla karıştırabilirler.

> Bu tür saldırılardan korunmak için şu önlemleri alabilirsiniz:

- Halka açık Wi-Fi ağlarını kullanırken dikkatli olun ve bağlantı yapmadan önce güvenilirliğini doğrulayın.
- VPN (Virtual Private Network) gibi şifreli bağlantılar kullanarak ağ trafiğinizi koruyun.
- Güvenilir bir antivirüs yazılımı kullanın.
- Düzenli olarak güncellenen cihaz yazılımı ve uygulamalarını kullanın.
- İnternette gezinirken bilinçli olun ve kişisel bilgilerinizi paylaşmaktan kaçının.
- Kablosuz ağlarınıza güçlü ve karmaşık şifreler kullanın.




