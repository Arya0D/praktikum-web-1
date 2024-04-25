# Praktikum Pemograman WEB-1

## HTML

HTML adalah kepanjangan dari **Hyper Text Markup Language**, markup language adalah bahasa komputer yang menggunakan tags atau tanda yang akan diterjemahkan komputer menjadi sebuah tampilan web.

### Struktur HTML

<img src="./img/strukturHTML.png">
<img src="./img/pageStruktur.png">

- &lt;!DOCTYPE html&gt;: deklarasi yang menadakan bahwa dokumen ini adalah HTML5.
- &lt;html&gt; : akar(root) dari halaman HTML.
- &lt;head&gt; : berisi informasi meta mengenai halaman HTML.
- &lt;body&gt; : container dari semua konten yang dapat dilihat seperti, heading, paragraphs, images, hyperlinks, tables, lists, dll.

Tidak semua HTML mempunyai content dan end tag, seperti &lt;br&gt;. Elements yang tidak mempunyai content sidebut empty elements.

## Basic HTML

### HTML Heading

HTML heading menggunakan tag dari &lt;h1&gt;(terbesar) sampai yang &lt;h6&gt;(terkecil)

<img src="./img/heading.png">

### HTML Paragraphs

HTML paragraphs menggunakan tag &lt;p&gt;

<img src="./img/paragraph.png">
<img src="./img/paragraphHasil.png">

### HTML Links

HTML link mengunakan tag &lt;a&gt; dengan atribut href untuk link destinasi.

<img src="./img/link.png">
<img src="./img/linkHasil.png">

### HTML Images

HTML Images mengunakan tag &lt;img&gt;, dan memiliki atribut src(source file), alt(alternative text), width(lebar) dan height(panjang).

<img src="./img/image.png">
<img src="./img/imageHasil.png">

## HTML Elements

HTML element terdiri dari start tag, content, dan end tag.

**&lt;startTag&gt; Content &lt;/endTag&gt;**

**&lt;h1&gt; Heading &lt;/h1&gt;**

**&lt;p&gt; paragraph &lt;/p&gt;**

### Nested element

Nested element atau element bersarang artinya elemen dapat berisi elemen lain. Contoh nya seperti elemen &lt;body&gt; yang berisi elemen-elemen lain yang akan ditampilkan pad website, seperti &lt;p&gt; dan &lt;h1&gt;.

## HTML Attributes

- Semua HTML element bisa memiliki attributes.
- Attributes memberikan informasi tambahan mengenai elemetnts.
- Attributes selalu diletakan pada start tag.
- Attributes biasanya menggunakan value seperti name="value".

### Contoh Attributes

#### 1. href

href adalah attribut yang digunakan pada element &lt;a&gt;.menentukan URL halaman yang dituju tautannya.
![href](./img/href.png)

#### 2. src

src attribut yang digunakan pada element &lt;img&gt; menentukan parh ke gambar yang akan ditampilkan .

ada dua cara untuk menentukan URL pada src attribute:

1. Absosulte URL:
   Tautan ke gambar eksternal yang dihosting di situs web lain. Contoh: src="https://www.w3schools.com/images/img_girl.jpg".

   ![absolueteURL](/img/absoluteSRC.png)

2. Relative URL: Tautan ke gambar yang di-host di dalam situs web. Di sini, URL tidak menyertakan nama domain. Jika URL dimulai tanpa garis miring, URL akan relatif terhadap halaman saat ini. Contoh: src="img_girl.jpg". Jika URL dimulai dengan garis miring, maka akan relatif terhadap domain. Contoh: src = "/images/img_girl.jpg".
   ![relativeteURL](/img/relativeSRC.png)

   ![src](/img/src.png)

#### 3. width dan height

width dan height digunakan pada tag &lt;img&gt; untuk menentukan ukuran lebar dan panjang gambar.
![size](/img/width&height.png)

![alt text](w&h.png)
