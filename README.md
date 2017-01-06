# Magento 2 Language pack ko_KR

## Install
```sh
cd <MAGENTO_ROOT>
mkdir -p app/i18n/Bluewisesoft/ko_KR
cd app/i18n/Bluewisesoft/ko_KR
git clone https://github.com/wisecommerce/magento2-korean-locale.git ./
```

## Apply locale
```sh
php bin/magento i18n:pack --mode=merge -d app/i18n/Bluewisesoft/ko_KR/ko_KR.csv ko_KR
```
