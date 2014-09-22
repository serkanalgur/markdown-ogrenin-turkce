# Başlıklar

Markdown dökümanı yazarken ilk olarak başlık ve alt başlıklar eklemeliyiz değil mi?

Markdown iki tarzda başlık stilini desteklemektedir. Setext ve atx.

Setext stili başlıklar için “alt çizgi” kullanır, eşittir işareti (birincil başlıklar için) ve kesik çizgileri (ikincil başlıklar için) kullanır. Örneğin;

```
Bir H1 başlığı
=============

Bir H2 başlığı
--------------
```

Eşittir işareti veya kesik çizgilerin sayısı önemli değildir.

Atx stili başlık türünde ise 1-6 arası kare (#) karakteri satır başına eklenir ve bu başlığın seviyesini oluşturur. Örnek olarak;

```
# H1 başlık örneği

## H2 başlık örneği

###### H6 başlık örneği
```

Opsiyonel olarak atx stil başlıkları “kapatabilirsiniz”. Bu sadece olayın süslemesi olur. Gözünüze hoş geliyorsa bu başlıkları kapatabilirsiniz. Kapatma karakterleri (#) sayısı başlıkla bağdaşık değildir. (Açılış kareleri başlığın stilini belirler):

```
# H1 başlık örneği #

## H2 başlık örneği ##

### H3 başlık örneği ######
```


---

Markdown başlıklar için ufak bir test yapalım.

Geçerli başlığı seçin:
- [x] `# merhaba`
- [ ] `#merhaba`

> Başlıklar kare ile arasında bir boşluk olmalıdır.

Geçerli başlık türünü seçin:
- [ ]
```
test
########
```
- [x]
```
test
=======
```

> Sadece '=' ve '-' işaretleri alt çizgili başlık türü için kullanılabilir.

---


