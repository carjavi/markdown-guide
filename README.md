<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/markdown_logo.png" height="100" alt=" " /></p>
<br>
<h1 align="center">Markdown Guide</h1>
<h4 align="right">Aug 22</h4>
<br>

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

<br>

# Images
local file:
```
![img1](/ruta/a/la/imagen.jpg) 
![img2](/ruta/a/la/imagen.jpg "Título alternativo")
![Screenshot](/screenshots/control_suitcase.png?raw=true) 
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

## Align Text & images

```
<center> center </center> 
<div style="text-align: right"> Aug 22</div>
<h4 align="right">derecha2</h4>

<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/markdown_logo.png" height="100" alt=" " /></p>
```
<center> center </center> 
<div style="text-align: right"> derecha</div>
<h4 align="right">derecha2</h4>
<p align="center"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/sample.jpg" height="100" alt=" " /></p>

<br>


## Linking Images


<br>

## Local image github
route image:

    https://raw.githubusercontent.com/usuario/repositorio/rama/ruta/
    sample:
    https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png
format:
```
<img src="https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png" height="250" alt="MarlinFirmware's logo" />
```
<img src="https://raw.githubusercontent.com/carjavi/install-nodejs-ARM/master/img/nodejs-npm_logos.png" height="250" alt="MarlinFirmware's logo" />




