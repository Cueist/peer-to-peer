# Merhaba, Bu bir 'WebRTC' projesidir.

WebRTC ile ilgili bilgiler/dökümanlara aşağıdaki linklerden ulaşabilirsiniz.
https://webrtc.org/?authuser=1 // https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API

##Gerekllilikler

node.js

WebRTC dışında socket.io , express ve nodemon (npm dependicies) kullanılmıştır.

Terminalden ;

npm i express https://expressjs.com/

npm i nodemon https://www.npmjs.com/package/nodemon , https://nodemon.io/

npm i socket.io https://socket.io/

Yukardakileri ekledikten sonra,

"npm start" ile başlatabilirsiniz.

#

Tarayıcınızdan yada farklı tarayıcılardan,

http://localhost:3000 ile toplam 2 pencere açınız.

Kamera ve ses için izin istenir.  

2 pencerede de farklı anahtarlar/ID' (socketid) ler -görünmeli.

herhangi birini kopyalayıp, diğerine yapıştırdıktan sonra -video call butonuna tıklayınız.  

Böylece bağlantı sağlanmış oldu.

Ekran Paylaşımı, mesajlaşma, mikrofon sesi aç-kapa işlemleri -yapılabilir.

## TO DO :

Daha iyi bir dökümantasyon

2 den fazla kullanıcı arasında bağlantı media alışverişi sağlanması.

Akış şeması 
