uygulama yazar: ata
# Uygulama Adı :  KOD-ASİSTAN BASİT KAYIT AKIŞI v0.1
## Uygulama Amacı :Kullanıcıdan alınan birden fazla farklı metinsel veriyi (ad, soyadı, kullanıcı adı vb.) mantıksal bir sıra dâhilinde işlemek, metin birleştirme operatörlerini kullanmak ve sonucu standart akış şeması sembolleriyle tasarlamak
## Problem Senaryosu :Kod-Asistan projesinin kullanıcı yönetim modülü tasarlanacaktır. Asistanın kullanıcıya ismiyle hitap edebilmesi ve sistemi kişiselleştirebilmesi için kayıt aşamasında ad ve soyadı verilerinin ayrı ayrı alınması, arka planda birleştirilerek tek bir profil kimliği hâline getirilmesi gerekmektedir.
BASLA
Ad ve soyad verilerini oku ("ad","soyad")
PROFİL=("ad"+"soyad")
YAZ ("Merhaba" + profil + "Uygulamaya Hoş geldin. "
DUR
