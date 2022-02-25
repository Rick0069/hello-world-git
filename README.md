# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

# Underlines

Underline 1

Underline 2

# Formatos de emphasis

- formato _italica_ de la primare forma.
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primara forma
- formato **bold o strong** de la primara forma
- formato ~~tachado~~

# Listas

1. Esto es un item de lista.
2. Esto es un item de lista.
3. Esto es un item de lista.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://hola.com">hola</a>
- [hola](http://hola.com)
- [enlace al index](index.html)

# Imágenes

![Logo GitHub](https://global-uploads.webflow.com/5f5a53e153805db840dae2db/6073fbf151fa4565d48572dc_GitHub_aprender-programaci%25C3%25B3n.jpeg)

# Code Snippets

```JSON
Código en JSON
[
    {
    "userFail": {
        "email": "0x0x0x0x0x0",
        "password": "------------"
    },
    "userOk": {
        "email": "test@test.com",
        "password": "12345678"
    }
}
]

```

```Javascript
Código en JS
module.exports = function (config) {
  config.set({
    basePath: '',
    frameworks: ['jasmine', '@angular-devkit/build-angular'],
    plugins: [
      require('karma-jasmine'),
      require('karma-chrome-launcher'),
      require('karma-jasmine-html-reporter'),
      require('karma-coverage'),
      require('@angular-devkit/build-angular/plugins/karma')
    ],
    client: {
      jasmine: {
        // you can add configuration options for Jasmine here
        // the possible options are listed at https://jasmine.github.io/api/edge/Configuration.html
        // for example, you can disable the random execution with `random: false`
        // or set a specific seed with `seed: 4321`
      },
      clearContext: false // leave Jasmine Spec Runner output visible in browser
    },
    jasmineHtmlReporter: {
      suppressAll: true // removes the duplicated traces
    },
    coverageReporter: {
      dir: require('path').join(__dirname, './coverage/spotify'),
      subdir: '.',
      reporters: [
        { type: 'html' },
        { type: 'text-summary' }
      ]
    },
    reporters: ['progress', 'kjhtml'],
    port: 9876,
    colors: true,
    logLevel: config.LOG_INFO,
    autoWatch: true,
    browsers: ['Chrome'],
    singleRun: false,
    restartOnFileChange: true
  });
};


```

# Tablas

| Nombre  | Apellido | Documento |
| ------- | -------- | --------- |
| Ricardo | Martinez | 251247458 |
| Juan    | Pérez    | 2354785   |

# Citas

Esto es un texto relacionado con la cita que vendrá a continuación:

> Esto es una cita

Esto es otro texto que no tiene que ver con la cita anterior.

> Esto es otra cita.

# Líneas divisoras

Texto para líneas divisoras utilizando guiones medios.

---

Texto para líneas divisoras utilizando asteriscos.

---

Texto para líneas divisoras utilizando guiones bajos.

---

# Saltos de línea

Esto es el primer párrafo.

Esto es el segundo párrafo.

Esto es el tercer párrafo.
