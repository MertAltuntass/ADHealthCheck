# AD-Health-Check

AD Health Check işlemini anlatacağım. Bu işlemi Task Scheduler ile planlamasını yaparak günlük olarak Active Directory takibimizi yapabiliriz. Scriptte Ping Testi, Netlogon Testi, NTDS Testi, DNS Testi, Replication, Sysvol, Services gibi testleri bulunmaktadır.

Bu yazımda ana kaynak olarak Microsoft MVP’lerinden Sukhija Vikas’ın yazmış olduğu Powershell Scriptini kullanacağız.
Not: Gmail hesabı üzerinden gönderim sağlayacaksanız “Less Secure Apps” özelliğini aktif etmeniz gerekmektedir. 

Bu scripti indirdikten sonrasında editleyerek kendimize uygun hale getirmemiz gerekmektedir.
İndirdiğimiz scripti sağ tıklayıp “Edit” seçeneğine tıklıyoruz. Böylece PowerShell ISE açılacaktır. Ben göndermesi için yazdığım kısmı en aşağıya ekledim.

$From = Gönderici E-posta adresi

$To = Alıcı  E-posta adresi”

$Cc = CC’deki Alıcı CC birine eklemek isterseniz buraya mail adresini girebilirsiniz.

$Subject = Konu Active Directory Health Check olarak bıraktım isterseniz değiştirebilirsiniz.

$SMTPServer = SMTP sunucunuz (gmail,yandex veya exchange)

$SMTPPort = İlgili Port numarası

$pass Gönderici şifreniz bu mail şifrenizdir.

