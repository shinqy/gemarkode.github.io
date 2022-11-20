# Website

Gemar Kode Official Website

[![Deploy Jekyll site to Pages](https://github.com/gemarkode/Website/actions/workflows/jekyll.yml/badge.svg)](https://github.com/gemarkode/Website/actions/workflows/jekyll.yml)

## install

### Required 

- ruby version 2.7.x
- Bundler version 2.3.x
- Gem version 3.1.x
- jekyll version 4.3.x

### Clone

```
git clone https://github.com/gemarkode/Website
```

### Install Dependensi

```
bundle install
```

### Ganti Url 

buka file ```_config.yml```

ubah
```yml
url : https://www.gemarkode.or.id
```
menjadi
```yml
url : http://127.0.0.1:4000
```

### jalankan Jekyll
```
gem exec jekyll serve
```

cek folder [```/script```](https://github.com/gemarkode/Website/tree/master/script) untuk melihat detail command
