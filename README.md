<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/markdown_logo.png" height="100" alt=" " /></p>
<br>
<h1 align="center">Markdown Guide</h1> 
<h4 align="right">Aug 22</h4>


# Header

```
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6
```
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6   

<br>

Escrito de otra forma:
```
Encabezado nivel 1
==========================

Encabezado nivel 2
--------------------------
```
#  Text Format
## html:

```
<span style="color:red">cardenales</span>
<p style="color:blue">Make this text blue.</p>
<font color="red">This text is red!</font>
<font size="5"> Markdown text content</font>
<h1 align="center">Marlin 3D Printer Firmware</h1>
<div style="background-color: #FFFF00">Highlighted text</div>
<mark >Highlighted text</mark>  
<span style="background-color:green">Mrs. Robinson</span>
```
<span style="color:red">cardenales</span>
<p style="color:blue">Make this text blue.</p>
<font color="red">This text is red!</font><br>
<font size="5"> Markdown text content</font>
<h1 align="center">Marlin 3D Printer Firmware</h1>
<div style="background-color: #FFFF00">Highlighted text</div>
<mark >Highlighted text</mark> <br> 
<span style="background-color:green">Mrs. Robinson</span>
<br>

## markdown text :
```
**Esto es una negrita**
*Esto es una itálica*
**_Esto es una negrita con itálica_**
***cursiva y negrita***
___cursiva y negrita___
```
**Esto es una negrita** <br>
*Esto es una itálica* <br>
**_Esto es una negrita con itálica_** <br>
***cursiva y negrita***<br> 
___cursiva y negrita___ <br>

<br>


### comment not visible in markdown
```
<!-- This content will not appear in the rendered Markdown -->
```
<br>

## Additional Line Spacing
This is how you add additional line spacing between lines.
```
&nbsp;
&nbsp;
```
This is how you add additional line spacing &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;between lines.

<br>

## Blockquotes
```
> Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.
> 
> La cita principal llegaría hasta aquí. 
```
> Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.
> 
> La cita principal llegaría hasta aquí. 

<br>

## Admonitions
```
> :warning: **Warning:** Do not push the big red button.
> :memo: **Note:** Sunrises are beautiful.
> :bulb: **Tip:** Remember to appreciate the little things in life.
```
> :warning: **Warning:** Do not push the big red button.<br>
> :memo: **Note:** Sunrises are beautiful.<br>
> :bulb: **Tip:** Remember to appreciate the little things in life.<br>
<br>

# Table of contents

link to headers
```
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
```
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

<br>

# Links
```
[[documento de instalación](../INSTALL.md)] // local
[[Become a sponsor](https://opencollective.com/debug#sponsor)] // URL
[Here is a link](www.linkurl.com)
<femail@url.com>
[Link display text - Email](mailto:example@mail.com)
[Contact Us](mailto:admin@cloudhadoop.com)
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```
[[documento de instalación](../INSTALL.md)] <br>
[[Become a sponsor](https://opencollective.com/debug#sponsor)] <br>
[Here is a link](www.linkurl.com)<br>
<femail@url.com> <br>
[Link display text - Email](mailto:example@mail.com) <br>
[Contact Us](mailto:admin@cloudhadoop.com) <br>
I love supporting the **[EFF](https://eff.org)**. <br>
This is the *[Markdown Guide](https://www.markdownguide.org)*. <br>
See the section on [`code`](#code).<br>

## Linking to Heading
```
  [Heading IDs](#heading-ids)
```

<br>

# Images
local file:
```
![img1](/ruta/a/la/imagen.jpg)
![Screenshot](screenshot.png) // la raiz
![Optional Text](../master/myFolder/image.png) // relativa
![img2](/ruta/a/la/imagen.jpg "Título alternativo")
![Screenshot](/screenshots/control_suitcase.png?raw=true) 
![Alt text](relative/path/to/img.jpg?raw=true "Title")
```
Web:
```
![Logo de Wikipedia](https://upload.wikimedia.org/wikipedia/en/8/80/Wikipedia-logo-v2.svg "Wikipedia logo")

<figure>
    <img src="https://mdg.imgix.net/assets/images/albuquerque.jpg?auto=format&fit=clip&q=40&w=1080"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>

<figure>
    <img src="https://images.unsplash.com/photo-1549740425-5e9ed4d8cd34?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXwzOTU0NTB8fGVufDB8fHw%3D&w=1000&q=80" alt="Trulli" style="width:100%">
    <figcaption align = "center"><b>Fig.1 - 4K Mountains Wallpaper</b></figcaption>
</figure>
```
![Logo de Wikipedia](https://upload.wikimedia.org/wikipedia/en/8/80/Wikipedia-logo-v2.svg "Wikipedia logo")

<figure>
    <img src="https://mdg.imgix.net/assets/images/albuquerque.jpg?auto=format&fit=clip&q=40&w=1080"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>

<figure>
    <img src="https://images.unsplash.com/photo-1549740425-5e9ed4d8cd34?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXwzOTU0NTB8fGVufDB8fHw%3D&w=1000&q=80" alt="Trulli" style="width:100%">
    <figcaption align = "center"><b>Fig.1 - 4K Mountains Wallpaper</b></figcaption>
</figure>

<br>

## Image Size
```
<img src="image.png" width="200" height="100">
```

<br>

## Align Text & images

```
<center> center </center> 
<div style="text-align: right"> Aug 22</div>
<h4 align="right">derecha2</h4>

<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/sample.jpg" height="100" alt=" " /></p>

<center>
    <img src="https://myoctocat.com/assets/images/base-octocat.svg">
</center>

<p align="center">
  <img width="200" src="https://opencollective.com/debug/backer/0/avatar.svg" alt="Material Bread logo">
</p>

|First Image|Second Image|
|:-:|:-:|
|![First Image](https://images.pexels.com/photos/585759/pexels-photo-585759.jpeg?h=750&w=1260)|![Second Image](https://images.pexels.com/photos/1335115/pexels-photo-1335115.jpeg?h=750&w=1260)|

<img align="right" width="100" height="100" src="https://media.tenor.com/images/6a136e1c2d7b30298a5b657348097a60/tenor.gif">

At the 2019 rendition of E3, an eccentric gamer in attendance interrupted Keanu Reeves' presentation of the role-playing game (RPG) Cyberpunk 2077, loudly claiming, 
```
<center> center </center> 
<div style="text-align: right"> derecha</div>
<h4 align="right">derecha2</h4>
<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/sample.jpg" height="100" alt=" " /></p>

<center>
    <img src="https://myoctocat.com/assets/images/base-octocat.svg">
</center>

<p align="center">
  <img width="200" src="https://opencollective.com/debug/backer/0/avatar.svg" alt="Material Bread logo">
</p>

|First Image|Second Image|
|:-:|:-:|
|![First Image](https://images.pexels.com/photos/585759/pexels-photo-585759.jpeg?h=750&w=1260)|![Second Image](https://images.pexels.com/photos/1335115/pexels-photo-1335115.jpeg?h=750&w=1260)|

<img align="right" width="100" height="100" src="https://media.tenor.com/images/6a136e1c2d7b30298a5b657348097a60/tenor.gif">

At the 2019 rendition of E3, an eccentric gamer in attendance interrupted Keanu Reeves' presentation of the role-playing game (RPG) Cyberpunk 2077, loudly claiming, 

<br>

## Image in paragraphs: 
```
![alt text][id]

[id]: /url/to/img.jpg "Título"

De esta forma podrías insertar una imagen
![nombre de la imagen][img1]
O dos, sin ensuciar tu espacio de escritura.
![nombre de la imagen2][img2] 

[img1]: /ruta/a/la/imagen.jpg "Título alternativo"
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo"
```


<br>


## Linking Images

```
<a href="url-here" target="_blank"><img src="https://opencollective.com/debug/backer/0/avatar.svg"></a>

<center>
    <img src="https://myoctocat.com/assets/images/base-octocat.svg">
</center>

<a href="https://heroku.com/deploy">
  <img  align="right"  src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
```
<a href="url-here" target="_blank"><img src="https://opencollective.com/debug/backer/0/avatar.svg"></a>
<br>

<a href="https://heroku.com/deploy">
  <img  align="right"  src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>

## Shieds 

``` 
https://img.shields.io/badge/<your label>-<value>-<background color>.svg?&style=for-the-badge&logo=<icon here>

``` 

``` 
<img src="https://img.shields.io/badge/Python-3.7-<background color>.svg?&style=for-the-badge&logo=python">

<img src="https://img.shields.io/badge/Javascript-3.7-<background color>.svg?&style=for-the-badge&logo=javascript">

<img src="https://img.shields.io/badge/linux-3.7-<background color>.svg?&style=for-the-badge&logo=linux">

<img src="https://img.shields.io/badge/twitter-mohammed__16695-1da1f2.svg?&style=for-the-badge&logo=twitter">
```
<img src="https://img.shields.io/badge/Python-3.7-<background color>.svg?&style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Javascript-3.7-<background color>.svg?&style=for-the-badge&logo=javascript">
<img src="https://img.shields.io/badge/linux-20.4-<background color>.svg?&style=for-the-badge&logo=linux">
<img src="https://img.shields.io/badge/twitter-mohammed__16695-1da1f2.svg?&style=for-the-badge&logo=twitter">

<br>

## Custotm Shieds Static
go to:
```
https://shields.io/
```
<a href="https://shields.io" target="_blank"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/shields.png"></a>

format:
```
https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>
![etiq1](https://img.shields.io/badge/OS-Rasbian%20GNU%20linux-green>)
![etiq2](https://img.shields.io/badge/Hardware-raspberry%20ver%204-red>)
```
![etiq1](https://img.shields.io/badge/OS-Rasbian%20GNU%20linux-green>)
![etiq2](https://img.shields.io/badge/Hardware-raspberry%20ver%204-red>)


<br>

## Local image github
image route:

    https://raw.githubusercontent.com/usuario/repositorio/rama/ruta/
    sample:
    https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png
format:
```
<img src="https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png" height="250" alt="MarlinFirmware's logo" />
```
<img src="https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png" height="250" alt="MarlinFirmware's logo" />

<br>



# Code
Fragmentos de código (snippets). basta con usar la tecla TABULACION

`Esto es una línea de código`

dentro de un parrafo <code>string</code> 

la forma mas comun usando **\``` al inicio y al final \```**
<br>

\``` html
```
<html>
    <head>
        <title>Título del sitio Web</title>
    </head>
    <body>
    </body>
</html>
```
\```

\```javascript
```
//javascript
var conf = require('rc')(appname, {
  port: 2468,
  views: {
    engine: 'jade'
  }
});
```
\```

\```js
```
//javascript
var server = require('http').createServer();
var io = require('socket.io')(server);
io.on('connection', function(client){
  client.on('event', function(data){});
  client.on('disconnect', function(){});
});
server.listen(3000);
```
\```

\```bash
```
npm install socket.io --save
```
\```

\```python
```
# python
input_string_var = input("Enter some data: ")
print("You entered: {}".format(input_string_var))
```
\```

\```sh
```
$ npm install --save strip-json-comments
```
\```

\```cmd
```
set DEBUG=*,-not_this
```
\```


\```
```
$ whoami
```
\```

<br>

# Horizontal lines
___
* * *
- - - - - -

<br>

# Tables

| Name      | Purpose                                         |
|-----------|-------------------------------------------------|
| `DEBUG`   | Enables/disables specific debugging namespaces. |
| `DEBUG_HIDE_DATE` | Hide date from debug output (non-TTY).  |
| `DEBUG_COLORS`| Whether or not to use colors in the debug output. |
| `DEBUG_DEPTH` | Object inspection depth.                    |
| `DEBUG_SHOW_HIDDEN` | Shows hidden properties on inspected objects. |


| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --------- | --------- | --------- |
| renglón 1, columna 1 | renglón 1, columna 2 | renglón 1, columna 3|
| renglón 2, columna 1 | renglón 2, columna 2 | renglón 2, columna 3|
| renglón 3, columna 1 | renglón 3, columna 2 | renglón 3, columna 3|
<br>

# Lists
Para crear listas desordenadas utiliza * asteriscos, - guiones, o + símbolo de suma.

- [x] Lorem ipsum dolor sit amet
- [ ] Lorem consectetur adipisicing elit
- [ ] Lorem ut labore et dfolore

1. First item
2. Second item
3. Third item
4. Fourth item

<br>

* Frutas
  * Manzanas
  * Naranjas
  * Uvas
* Lácteos
  * Leche
  * Queso

<br>

Lista de pendientes
------------------
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo


<br>

* [Ina219](#Ina219)
  * [new Ina219()](#new_Ina219_new)
  * [.init(address, device)](#Ina219+init)
  * [.enableLogging(enable)](#Ina219+enableLogging)
  * [.writeRegister(register, value, callback)](#Ina219+writeRegister)
  * [.readRegister(register, callback)](#Ina219+readRegister)
  * [.calibrate32V1A(callback)](#Ina219+calibrate32V1A)
  * [.log(s)](#Ina219+log)

<br>

<details open> 
    <summary> 
      What is Lorem Ipsum?
    </summary>
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
</details>

<details> 
    <summary> 
      Why do we use it?
    </summary>
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. 
</details>

<br>

# Caracteres Especiales

```
símbolo de copyright: &copy;
símbolo: AT&amp;T
como se escribe: 4 &lt; 5   
como se escribe: E=MC<sup>2</sup>
como se escribe: CO<sub>2</sub>
como se escribe: aaa &#124; bbb
como se escribe: &reg;
como se escribe: &larr;
como se escribe: &rarr;
como se escribe: &uarr;
como se escribe: &darr;
como se escribe: &#176;
como se escribe: &#960;

\   backslash (barra invertida) para poder escriibir caracteres especiales

`   backtick (acento grave)
*   asterisk (asterisco)
_   underscore (subrayado)
{}  curly braces (llaves)
[]  square brackets (corchetes)
()  parentheses (paréntesis)
#   hash mark (almohadilla)
.   dot (punto)
!   exclamation mark (exclamación)
```
    sample: \* asteriscos, sin énfasis

símbolo de copyright: &copy;

símbolo: AT&amp;T

como se escribe: 4 &lt; 5   

como se escribe: E=MC<sup>2</sup>

como se escribe: CO<sub>2</sub>

como se escribe: aaa &#124; bbb

 como se escribe: &reg;

como se escribe: &larr;

como se escribe: &rarr;

 como se escribe: &uarr;

 como se escribe: &darr;

 como se escribe: &#176;

como se escribe: &#960;

# Videos

    !video[text to display](url)
```
[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/)
```

[![image alt text](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=fUatlXlAsuw&t=861s&ab_channel=RaulDiosdado)


con imagen miniatura de foto

### Youtube Video: Life as an Engineer - WFH

[![][thumbnail]](https://youtu.be/Rgx8dpiPwpA "Life as an Engineer - WFH")

[thumbnail]: https://raw.githubusercontent.com/6aravind/tidbits/main/assets/images/markdown_Life%20as%20Engineer.png


<br>

# Info
Si usted desea realmente insertar una marca `<br/>` de salto de línea usando Markdown, sólo tiene que finalizar una línea con dos o más espacios, y a continuación pulsar la tecla de retorno, es decir, Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora antes de pulsar una vez intro.

<br>

# Samples
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)

```
<summary>Emeriti</summary>
```
<summary>Emeriti</summary>



## Authors
```
- [Daniel Muchiri](https://github.com/daydroidmuchiri)
- [Kevin Wairi](https://github.com/kevinwairi)
```
  
- [Daniel Muchiri](https://github.com/daydroidmuchiri)
- [Kevin Wairi](https://github.com/kevinwairi)
  
```
<details>
* [addaleax](https://github.com/addaleax) -
  **Anna Henningsen** <<anna@addaleax.net>> (she/her)
* [bnoordhuis](https://github.com/bnoordhuis) -
  **Ben Noordhuis** <<info@bnoordhuis.nl>>
* [chrisdickinson](https://github.com/chrisdickinson) -
  **Chris Dickinson** <<christopher.s.dickinson@gmail.com>>
* [codebytere](https://github.com/codebytere) -
  **Shelley Vohr** <<shelley.vohr@gmail.com>> (she/her)
</details>
  ```
<details>
  * [addaleax](https://github.com/addaleax) -
  **Anna Henningsen** <<anna@addaleax.net>> (she/her)
* [bnoordhuis](https://github.com/bnoordhuis) -
  **Ben Noordhuis** <<info@bnoordhuis.nl>>
* [chrisdickinson](https://github.com/chrisdickinson) -
  **Chris Dickinson** <<christopher.s.dickinson@gmail.com>>
* [codebytere](https://github.com/codebytere) -
  **Shelley Vohr** <<shelley.vohr@gmail.com>> (she/her)
</details>

 ```
<!-- node-core-utils and find-inactive-collaborators.mjs depend on the format
     of the collaborator list. If the format changes, those utilities need to be
     tested and updated. -->
 ```
 <!-- node-core-utils and find-inactive-collaborators.mjs depend on the format
     of the collaborator list. If the format changes, those utilities need to be
     tested and updated. -->

     
<br>

```
**Supported params:**

- ```description``` - Text to display before the argument help.
- ```epilog``` - Text to display after the argument help.


Details in [original ArgumentParser guide](http://docs.python.org/dev/library/argparse.html#argumentparser-objects)
```

**Supported params:**

- ```description``` - Text to display before the argument help.
- ```epilog``` - Text to display after the argument help.


Details in [original ArgumentParser guide](http://docs.python.org/dev/library/argparse.html#argumentparser-objects)

<br>

## Shield in HTML
```
<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">OS</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#C03027">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">Raspbian GNU/Linux 11</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">node</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#53B21D">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">18.0.9</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">python</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#E89B33">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">3.7.0</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">arduino</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#27A4C0">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">3.7.0</font>&nbsp;&nbsp;&nbsp;</span>
```
<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">OS</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#C03027">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">Raspbian GNU/Linux 11</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">node</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#53B21D">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">18.0.9</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">python</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#E89B33">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">3.7.0</font>&nbsp;&nbsp;&nbsp;</span>

<span style="background-color:#535050">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">arduino</font>&nbsp;&nbsp;&nbsp;</span><span style="background-color:#27A4C0">&nbsp;&nbsp;&nbsp;&nbsp;<font color="white">3.7.0</font>&nbsp;&nbsp;&nbsp;</span>

<br>

License
=======
Copyright (c) 2012 [Vitaly Puzrin](https://github.com/puzrin).
<br>
MIT © [Sindre Sorhus](http://sindresorhus.com)

<br>

# My style

## Titule
```
<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/markdown_logo.png" height="100" alt=" " /></p>
<br>
<h1 align="center">Markdown Guide</h1> 
<h4 align="right">Aug 22</h4>
```

## Shields
```
https://shields.io/

OS-Linux
<img src="https://img.shields.io/badge/OS%20-Raspbian%20GNU%2FLinux%2011%20(bulleye)-yellowgreen">
OS-Windows
<img src="https://img.shields.io/badge/OS-Windows%2011-blue">

Hardware-Raspberry
<img src="https://img.shields.io/badge/Hardware-Raspberry%20ver%204-red">
Hardware-Arduino
<img src="https://img.shields.io/badge/Hardware-Arduino__nano-red">
Hardware-ESP32
<img src="https://img.shields.io/badge/Hardware-ESP32-red">

Node
<img src="https://img.shields.io/badge/Node%20-V18.7.0-green">
Python
<img src="https://img.shields.io/badge/Python%20-V3.9.2-orange">
```

## Footer
```
---
Copyright &copy; 2022 [carjavi](https://github.com/carjavi). <br>
```www.instintodigital.net``` <br>
carjavi@hotmail.com <br>
<p align="center">
    <a href="https://instintodigital.net/" target="_blank"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/developer.png" height="100" alt="www.instintodigital.net"></a>
</p>
```

---
Copyright &copy; 2022 [carjavi](https://github.com/carjavi). <br>
```www.instintodigital.net``` <br>
carjavi@hotmail.com <br>
<p align="center">
    <a href="https://instintodigital.net/" target="_blank"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/developer.png" height="100" alt="www.instintodigital.net"></a>
</p>







