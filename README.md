# ostrava.pirati.cz

Postup spuštění lokálního Jekyll serveru se stránkou (Ubuntu a ostatní Debian based distribuce):
```
cd <adresář_kam_naklonovat_GIT_repozitář>
git clone https://github.com/pirati-web/ostrava.pirati.cz.git
cd ostrava.pirati.cz
bundle install
bundle install --path vendor/bundle
bundle update listen
bundle exec jekyll serve --watch --livereload

Ve webovém prohlížeči: http://127.0.0.1:4000
```

Obrázky rozměry: posts 1200x628 people 165x220
