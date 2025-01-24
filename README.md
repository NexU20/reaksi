# Reaksi

> React like framework, for fun ☺


## Motivation
Saya membuat ini untuk mempelajari lebih dalam soal framework ReactJs, yaitu dengan membuatnya 😁


## Hal yang belum ada di library ini (untuk sekarang)
- Functional Components (hanya bisa class component)
- Hooks lainnya
- Component Lifecycle
- `Ref` Attribute
- Reconciliation dengan `key`
- Teknik Rendering Lainnya
- Old Browser Support 


## Usage
Kloning repositori ini dan jalankan

```
$ npm run build
```

jika berhasil folder `dist` akan muncul di root directory yang berisikan:
- `reaksi.es.js`
- `reaksi.umd.js`

kamudian buat file `html` dan tambahkan
```html
<div id="root"></div>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>

<!-- import library yang sudah dibuild di sini -->
<script src="reaksi.umd.js"></script>
<script type="text/jsx" data-presets="es2016,react">
    //kode react di sini
</script>
```


## Demos
[Hello World](https://nexu20.github.io/reaksi/examples/01-hello-world.html)

[State Example](https://nexu20.github.io/reaksi/examples/02-state.html)