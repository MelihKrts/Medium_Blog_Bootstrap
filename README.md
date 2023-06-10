# Bootstrap Kurulum Aşaması
Bootstrap kurulum aşaması npm ve node.js ile bu adımlar uygulandı. <br>

1. ```npm install bootstrap@5.3.0```
2. Kurulumu tamamlamak için terminal ekranına `npm run bootstrap` yazılacak
3. Kurulum tamamlandı.
4. Tailwind kıyasla daha az uğraştırıcı kurulum.

<br>

# Class Yapısı
```html
<header class="w-100 bg-succes h-25"></header>
```

<br>

# Custom Class Added
Tailwind gibi kolaylıkla yapılamıyor. Harici CSS dosyası ile kendimiz class ekleyebiliriz. Tailwind kıyasla kısıtlayıcı özelliğe sahip.

<br>

# Bootstrap Docs Kullanılabilirlik

Tailwind CSS ile eşit konumda. Kullanılabilirlik iyi. Bolca örnek verilmiş durumda. ```https://getbootstrap.com/docs/5.3/getting-started/introduction/```

<br>

# Responsive Mobile First Yaklaşımı
Tailwind kıyasla xs adlı harici class eklemedik. Bu ek kod yazmamızdan kurtarmış oluyor.

<br>

# Bootstrap Kendi Kuralı Dayatması

Bootstrap 12 sütün ve altı duyarlı katman mevcut. Flexbox model kullanmaya zorluyor. Projede kullanılan grid yapısını geliştirici kendisi eklemek zorunda. Bu geliştiriciyi kısıtlıyor ve grid yapısı kullanırken geliştirici kendisi yazmak zorunda. <br>

**Bkz :** Bootstrap ızgara (grid) yapısı ```https://getbootstrap.com/docs/5.3/layout/grid/``` <br>

**Bkz :** Flexbox model; <br>
1. ```https://www.w3schools.com/css/css3_flexbox.asp``` 
2. ```https://css-tricks.com/snippets/css/a-guide-to-flexbox/```