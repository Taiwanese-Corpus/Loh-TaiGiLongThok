# Loh-TaiGiLongThok

駱嘉鵬老師ê全國語文競賽閩南語朗讀文章變調屬性標記佮競賽講評

```
wget \
     --recursive \
     --no-clobber \
     --page-requisites \
     --adjust-extension \
     --span-hosts \
     --convert-links \
     --restrict-file-names=windows \
     --domains www.kaphing.idv.tw \
     --no-parent \
         https://www.kaphing.idv.tw/loh/taigilongthok/

iconv -f big5 www.kaphing.idv.tw/loh/taigilongthok/index.html > index.html

mv index.html www.kaphing.idv.tw/loh/taigilongthok/
```
