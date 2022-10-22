# CSS - patika.dev - Soru ve Cevapları
>**[patika.dev](https://app.patika.dev/courses/css) platformu CSS öğrenme amaçlı soruların cevaplanması projesidir.** \
> **Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)**


![](https://raw.githubusercontent.com/nmelihkutlu/patikaCSS/main/patikaCSS.png)



[Ödev1](#ödev-1) - [Ödev3](#ödev-2)

## Ödev 1

### Soru
Sayfamıza biraz makyaj yapalım

![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/css/odev1/figures/htmlcssjs.png)

Herkese merhaba arkadaşlar kanalımıza hoş geldiniz, bugün HTML sayfamıza hafif bir makyaj yapacağız. Komik gelse de aslında tam olarak böyle yapacağız. Bir HTML sayfası oluşturup buna CSS ile tasarımsal açıdan güzellikler katacağız, HTML sayfamıza güzelliği getireceğiz.


- HTML sayfasını sıfırdan oluşturacaksınız. Eklemek istediğiniz ekstra özellikler tamamen size kalmış durumda.

-Sitemiz birkaç sayfadan oluşacak. Yani menü kısmında linkler vererek başka sayfaya geçilebilecek.

- Renkler tamamen sizin zevkinize kalmış durumda. Fakat renkler konusunda biraz yardım almak isterseniz Colorhunt renk paletleri konusunda muazzam bir site.

- Yazacağınız CSS etiketlerini Inline ve Internal yazabilirsiniz. External kullanmak tamamen sizin tercihinizdir.

- CSS yazarken noktalı virgülleri unutmayın. Biliyorum unutacaksınız, olur böyle şeyler...

- CSS ile ilgili yardımcı kaynak için w3schools.com'un CSS tutorialını, Türkçe kaynak için Fatih Hayrioğlu'nun web sitesini kullanabilirsiniz.

- Kendini tekrar eden yapılar kullanmamaya özen gösteriniz. Ya da kendini tekrar eden yapılarda kullandığımız özelliği kullanın. (İpucu: Inline(Etikete Özel), Internal(Aynı Dosyada) ve External(CSS Dosyasında) CSS Kullanımı)

- Sayfalarınızda kullandığınız fontlar için daha önce de videolarda bahsettiğimiz Google Fonts'u kullanabilirsiniz.

- Ana sayfada bulunan listelerin noktalarını ortalamak için list-style-position: inside'i kullanabilirsiniz.

### Cevap

**Dosya için tıklayınız: [index.html](https://github.com/nmelihkutlu/patikaCSS/blob/main/index.html)**


```html
body{
    text-align: center;
    background-color:lightcyan;
}
h1{
    color: red;
}
p{
    color: black;
}
footer.p{
    color: green;
}
```


## Ödev 2

### Soru
![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/css/cssodev3/figures/googlehomepage.png)

Google Ana Sayfasını Tasarlamak
Hepimiz her gün Google kullanıyoruz ve çok işimize yarıyor değil mi? Her gün Google'da milyonlarca arama yapılıyor ve hatta siz de bu sayfaya gelmek için Google'ı kullanmış olabilirsiniz. Peki Google'ın geçmişten günümüze nasıl geliştiğini hiç merak ettiniz mi?

Google 1996 yılında kuruldu ve ilk versiyonunu 1998 yılında yayınladı. 1998, çok uzun bir süre önce değil mi? İlk versiyonu ile şu anki versiyonu arasında büyük fark var tabii ki. Peki size Google'ın ilk versiyonunu gösterebileceğimizi söylesek ne hissederdiniz?

İnternetteki gelmiş geçmiş bütün web sitelerini görebileceğiniz Wayback Machine adında bir web arşivi bulunmakta. Google 1998 linkinden Google'ın ilk versiyonu nasılmış görebilirsiniz. Oldukça garip öyle değil mi? Garip olmasının yanında bu sizin HTML bölümündeki üçüncü ve son ödeviniz olacak. Bu sayfayı tasarlamanızı istiyoruz.

Bu sayfada şu ana kadar öğrendiğiniz her şeyi kullanabilirsiniz. Bu sizin HTML becerilerinizi oldukça iyi bir şekilde geliştirmenizi sağlayacaktır.
googlehomepage

Butonların çalışmaması hiç sorun değil. Sadece tasarımsal olarak bu görüntüye benzesin ve aşağıdaki linkler çalışıyor olsun yeterli.
Tasarladığınız bölümler ile alakalı kodunuzda açıklama satırlarına yer veriniz.
Sayfa ile alakalı detaylara sayfanın üzerine sağ tıklayıp "İncele/Inspect" diyerek ulaşabilirsiniz.
Bu logo'yu kullanabilirsiniz.
İleride göreceğimiz CSS'den sonra Google'ın bugünkü halini de tasarlayacağız. Ama öncelikle bakalım Larry Page ve Sergey Brin başlangıçta nasıl yapmışlar!

Hepinize başarılar ve kolay gelsin!

## Cevap

**Dosya için tıklayınız: [index.html](https://github.com/nmelihkutlu/patikaCSS/blob/main/google.html)**


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google!</title>
</head>
<body bgcolor="#FFFFFF" background="https://web.archive.org/web/19981202230410im_/http://www.google.com/alpha.jpg">
    <form method="GET" action="https://web.archive.org/web/19981202230410/http://www.google.com/search">
        <center><img src="https://web.archive.org/web/19981202230410im_/http://www.google.com/google.jpg" width="351" height="113" alt="Google!"></center>
        <center>
            <table border="0" width="90%">
                <tr>
                    <td bgcolor="#EEEEEE" colspan="3">
                        <center>
                            Search the web using Google! <br>
                            <input type="text" name="q" value="" size="40"><br>
                            <input type="submit" value="Google Search">
                            <input type="submit" name="sa" value="I'm feeling lucky"><br>
                        </center>
    </form>
    <form method="GET" action="https://web.archive.org/web/19981202230410/http://www.findmail.com/cgi-bin/subscribe.py">
                    </td>
                </tr>
                <tr>
                    <td width="37%" bgcolor="#7EE5DA">
                        <center>
                            Special Searches<br>
                            <a href="https://web.archive.org/web/19981202230410/http://www.google.com/stanford">Stanford Search</a><br>
                            <a href="https://web.archive.org/web/19981202230410/http://www.google.com/linux">Linux Search</a><br>
                        </center>
                    </td>
                    <td bgcolor="#70CCC2">
                        <center>
                            <font size="-1">
                            <a href="https://web.archive.org/web/19981202230410im_/http://www.google.com/help.html">Help!</a> <br>
                            <a href="https://web.archive.org/web/19981202230410im_/http://www.google.com/about.html">About Google!</a> <br>
                            <a href="https://web.archive.org/web/19981202230410im_/http://www.google.com/company.html">Company Info</a> <br>
                            <a href="https://web.archive.org/web/19981202230410im_/http://www.google.com/stickers.html">Google! Logos</a> <br>
                            </font>
                        </center>
                    </td>
                    <td align="right" bgcolor="#62B3AA">
                        <center>
                            <font size="-1">
                                Get Google! <br> updates monthly: <br>
                                <input type="hidden" name="listname" value="google-friends">
                                <input type="text" name="emailaddr" value="your e-mail"> <br>
                                <input type="submit" name="SubmitAction" value="Subscribe"> 
                                &nbsp;&nbsp;
                                <font size="-1"><a href="https://web.archive.org/web/19981202230410/http://www.findmail.com/list/google-friends/">Archive</a></font>      
                            </font>
                        </center>
                    </td>
            </table>
        </center>
        
        <p>
        <center><font size="-1">Copyright &copy;1998 Google Inc.</font></center>
    </form>
        
    
</body>
</html>

```