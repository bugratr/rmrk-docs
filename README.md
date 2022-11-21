# Website

Bu web sitesi, modern bir statik web sitesi oluşturucu olan [Docusaurus 2](https://v2.docusaurus.io/) kullanılarak oluşturulmuştur.

## Yükleme

```console
yarn install
```

## Yerelde Geliştirme

```console
yarn start
```

Bu komut yerel bir geliştirme sunucusu başlatır ve bir tarayıcı penceresi açar. Çoğu değişiklik, sunucuyu yeniden başlatmak zorunda kalmadan canlı olarak yansıtılır.

## İnşa Et

```console
yarn build
```
Bu komut, 'build' dizinine statik içerik oluşturur ve herhangi bir statik içerik barındırma hizmeti kullanılarak sunulabilir.

## Yükleme

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

Barındırma için GitHub sayfalarını kullanıyorsanız, bu komut web sitesini oluşturmanın ve "gh-pages" dalına göndermenin uygun bir yoludur.
