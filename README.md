# Tea Ödüllü testnet

## Linkler
 * [Hercules Telegram](https://t.me/HerculesNode)
 * [Hercules Twitter](https://twitter.com/Herculesnode)

- Öncelikle tea projesi github üzerindeki projeleri indexleyerek kendi alanında bir proje indexleme servisidir. Testnet şuanda açıldı ve ITN yani ödüllü olduğu söyleniyor. 
- Proje bir nevi geliştiriciler için güzel bir testnet imkanı sunuyor, geliştirici değilseniz bazı görevleri yaparak sizde puan kazanabilirsiniz. 

# 1- Kayıt işlemi

- tea testnet için bu adrese gidelim https://app.tea.xyz

- Resimdeki gibi Google , Outlok ve Discord hesabınızla giriş yapın. 

![image](https://github.com/HerculesNode/tea-testnet/assets/101635385/5fd6bcca-ec91-42da-92b9-66e101fac099)

- giriş yaptıktan sonra github hesabınız ile giriş yapın ardından complate diyip ana panele giriş yapın.

![image](https://github.com/HerculesNode/tea-testnet/assets/101635385/6f28bc9c-b58d-4652-98cd-6a21d3e47580)


# 2- Panel işlemleri ( Geliştirici )

- tea APT - Crates - Homebrew - npm - Pypi - RubyGames - Pkgx - swift - Appimage - Chocolatey - Cocoapods - Composer - Conda - Cran - Dnf - Fink - Flatpack gibi dilleri destekliyor.

- Github hesabınızda bir proje oluştrumanız gerekiyor ve bu projeyi Register OSS project ile kayıt etmeniz lazım. Aşağıdaki resim gibi. 
- Github projeniz oluşturduktan sonra indexlenmesi 24 saat sürüyor, yani hemen tea projenizi görmüyor.

- Şimdi proje için `index.html` , `index.js` , `package.json` ve `Readme.md` dosyaLarı oluşturacağız.  
- Bunları not defterindende yada VS yada notepad ++ ile rahatça yapablirsiniz. 


1- ilk olarak masaüstünde proje klasörü oluşturun örnek `testprojem` 


- `package.json` adında bir dosya oluşturun ve içine aşağıdaki kodları kopyalayın kendinize göre doldurun. <BURAYI DEĞİŞTİR> dediğim yerleri kendinize göre değiştirin ve <BURAYI DEĞİŞTİR> kısmını silin.

```bash
{
  "name": "testprojem",  <BURAYI DEĞİŞTİR>
  "version": "1.0.2",
  "description": "hercules test project ",  <BURAYI DEĞİŞTİR>
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
  "type": "git",
  "url": "https://github.com/HerculesNode/testprojem.git"  <BURAYI DEĞİŞTİR>
   },
    "keywords": [
    "test",     <BURAYI DEĞİŞTİR>
    "proje",    <BURAYI DEĞİŞTİR>
    "matsh"     <BURAYI DEĞİŞTİR>
  ],
  "dependencies": {
    "express":"latest",
    "ejs":"latest"
  },
  "author": "Hercules",  <BURAYI DEĞİŞTİR>
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/HerculesNode/testprojem/issues" <BURAYI DEĞİŞTİR>
  },
  "homepage": "https://github.com/HerculesNode/testprojem#readme" <BURAYI DEĞİŞTİR>
}

```


- `index.html` adında bir dosya oluşturun ve içine aşağıdaki kodları kopyalayın kendinize göre doldurun. <BURAYI DEĞİŞTİR> dediğim yerleri kendinize göre değiştirin ve <BURAYI DEĞİŞTİR> kısmını silin.

 ```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projem</title>  <BURAYI DEĞİŞTİR>
<link rel="stylesheet" href="style.css">
</head>
<body>
    
    <script src="index.js">   
    </script>
</body>
</html>

```


- `readme.md` adında bir dosya oluşturun içini kendinize göre doldurun. 

- `index.js` adında bir dosya oluşturun ve projenizi içine yerleştirin.


![image](https://github.com/HerculesNode/tea-testnet/assets/101635385/00b9e31a-7382-4236-a56e-2c5d427df40a)
![image](https://github.com/HerculesNode/tea-testnet/assets/101635385/8fc64ff3-fd48-4660-bf31-ec320a3a520a)


# 3- Panel işlemleri ( Geliştirici olmayan )

- Burada geliştirici değilseniz bazı görevler bulunuyor bunları tamamlamanız gerekiyor. 
- Ayarlardan mail adresi girmek
- kendinizi tanıtmak
- Tea tweet atmak
- stake etme işlemleri gibi.

![image](https://github.com/HerculesNode/tea-testnet/assets/101635385/2f8aeddd-e2c8-46fd-a925-996e88b7d035)
