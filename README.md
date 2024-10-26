# Currency Converter (Döviz Çevirici)

Bu proje, farklı para birimleri arasında hızlı ve kolay dönüşüm yapmanıza olanak tanıyan bir Döviz Çevirici uygulamasıdır. Kullanıcılar dil ve tema seçeneklerini özelleştirebilir, miktar, başlangıç ve hedef para birimlerini seçerek çevrim işlemlerini gerçekleştirebilir.

## İçindekiler
1. [Özellikler](#özellikler)
2. [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
3. [Kurulum](#kurulum)
4. [Kullanım](#kullanım)
5. [Dosya Yapısı](#dosya-yapısı)

### Özellikler

- **Para Birimi Dönüştürme**: Seçilen para biriminden diğerine dönüşüm sağlar.
- **Dil Desteği**: Türkçe ve İngilizce dillerinde kullanılabilir.
- **Tema Seçeneği**: Açık ve koyu tema seçenekleri sunar.
- **Anlık Kur Güncellemeleri**: Güncel döviz kurları ile dönüşüm yapar.

### Kullanılan Teknolojiler

- **HTML**: Yapısal içerik ve form alanları oluşturmak için.
- **CSS**: Tema, görünüm ve stil ayarları için.
- **JavaScript**: Döviz çevirme işlemleri, tema ve dil değişimi gibi etkileşimli özellikleri sağlamak için.
- **Exchange Rate API**: Anlık döviz kurları almak için.

### Kurulum

1. Bu projeyi klonlayın:
   ```bash
   git clone https://github.com/kullanıcıadınız/currency-converter.git
   ```
2. Proje dizinine gidin:
   ```bash
   cd currency-converter
   ```
3. `index.html` dosyasını bir tarayıcıda açın.

### Kullanım

- **Dil Seçimi**: Sayfanın üst kısmında yer alan dil seçeneklerinden (`Language`) İngilizce veya Türkçe seçebilirsiniz.
- **Tema Seçimi**: `Light` (Açık) ve `Dark` (Koyu) olmak üzere iki tema arasında geçiş yapabilirsiniz.
- **Döviz Çevirme**: `Amount` alanına bir miktar girin, `From` ve `To` seçeneklerinden para birimlerini seçin ve `Convert` butonuna tıklayarak sonucu görüntüleyin.

### Dosya Yapısı

- **index.html**: Uygulamanın HTML yapısını ve temel bileşenleri içerir.
- **styles.css**: Açık ve koyu tema dahil olmak üzere, kullanıcı arayüzü için stil dosyasıdır.
- **script.js**: Döviz çevirme işlemleri, dil ve tema yönetimini içeren JavaScript işlevleri.
