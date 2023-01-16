# AD-Health-Check

AD Health Check işlemini anlatacağım. Bu işlemi Task Scheduler ile planlamasını yaparak günlük olarak Active Directory takibimizi yapabiliriz. Scriptte Ping Testi, Netlogon Testi, NTDS Testi, DNS Testi, Replication, Sysvol, Services gibi testleri bulunmaktadır.

Bu yazımda ana kaynak olarak Microsoft MVP’lerinden Sukhija Vikas’ın yazmış olduğu Powershell Scriptini kullanacağız. Scripti hazır olarak kullanmak yerine ben Scripte kendi katma değerimi katmak istedim. Scriptin güncellenmiş haline buradan ulaşabilirsiniz. 

Not: Gmail hesabı üzerinden gönderim sağlayacaksanız “Less Secure Apps” özelliğini aktif etmeniz gerekmektedir. İlgili dokumana bu link üzerinden ulaşabilirsiniz.

Bu scripti indirdikten sonrasında editleyerek kendimize uygun hale getirmemiz gerekmektedir.
İndirdiğimiz scripti sağ tıklayıp “Edit” seçeneğine tıklıyoruz. Böylece PowerShell ISE açılacaktır. Ben göndermesi için yazdığım kısmı en aşağıya ekledim.

$From = Gönderici “abc@abc.com”

$To = Alıcı “abc@abc.com”

$Cc = CC’deki Alıcı “cba@abc.com”

$Subject = Konu ”Health Check”

$SMTPServer = SMTP sunucumuz “smtp@abc.com”

$SMTPPort = Port “587”

$pass Gönderici şifreniz



 Detaylı bilgi için https://www.mshowto.org/ad-health-check.html adresinden makalemi okuyabilirsiniz.

 Konuyla ilgili sorularınızı iletisim@zeynelugurlu.com adresinden bana ulaştırabilirsiniz.
