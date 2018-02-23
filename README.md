# multiple-vuejs-bundles-with-webpack

> Multiple VueJs bundles with the webpack template.

## Kurulum

Proje ```git@github.com:hootka/multiple-vuejs-bundles-with-webpack.git``` ile bilgisayara indirilir.

Ardından gerekli paketlerin kurulması için proje klasörü içerisinde aşağıdaki komut çalıştırılır:

```bash
yarn install
```

## Çalıştırma

Paketlerin kurulumu tamamlandıktan sonra aşağıdaki komut ile geliştirme ortamında proje ayağa kaldırılır:

app isimli projeyi ayaga kaldırmak için;

```bash
yarn run dev
```

ya da appTwo isimli projeyi ayaga kaldırmak için;

```bash
yarn run panel
```

## Derleme
Projenin derlenmesi ve yayınlanacak halinin elde edilebilmesi için aşağıdaki komut proje klasöründen çalıştırılmalıdır:

```bash
yarn run build
```

Yukarıdaki komut sunucuda yayınlanacak iki projeye ait olan kodları, dist/ klasörü içerisinde hazırlayacaktır.
