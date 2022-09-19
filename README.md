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

## SVG
```
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file-zip color-fg-muted">
    <path fill-rule="evenodd" d="M3.5 1.75a.25.25 0 01.25-.25h3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h2.086a.25.25 0 01.177.073l2.914 2.914a.25.25 0 01.073.177v8.586a.25.25 0 01-.25.25h-.5a.75.75 0 000 1.5h.5A1.75 1.75 0 0014 13.25V4.664c0-.464-.184-.909-.513-1.237L10.573.513A1.75 1.75 0 009.336 0H3.75A1.75 1.75 0 002 1.75v11.5c0 .649.353 1.214.874 1.515a.75.75 0 10.752-1.298.25.25 0 01-.126-.217V1.75zM8.75 3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM6 5.25a.75.75 0 01.75-.75h.5a.75.75 0 010 1.5h-.5A.75.75 0 016 5.25zm2 1.5A.75.75 0 018.75 6h.5a.75.75 0 010 1.5h-.5A.75.75 0 018 6.75zm-1.25.75a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM8 9.75A.75.75 0 018.75 9h.5a.75.75 0 010 1.5h-.5A.75.75 0 018 9.75zm-.75.75a1.75 1.75 0 00-1.75 1.75v3c0 .414.336.75.75.75h2.5a.75.75 0 00.75-.75v-3a1.75 1.75 0 00-1.75-1.75h-.5zM7 12.25a.25.25 0 01.25-.25h.5a.25.25 0 01.25.25v2.25H7v-2.25z"></path>
</svg>
```
--><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file-zip color-fg-muted">
    <path fill-rule="evenodd" d="M3.5 1.75a.25.25 0 01.25-.25h3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h2.086a.25.25 0 01.177.073l2.914 2.914a.25.25 0 01.073.177v8.586a.25.25 0 01-.25.25h-.5a.75.75 0 000 1.5h.5A1.75 1.75 0 0014 13.25V4.664c0-.464-.184-.909-.513-1.237L10.573.513A1.75 1.75 0 009.336 0H3.75A1.75 1.75 0 002 1.75v11.5c0 .649.353 1.214.874 1.515a.75.75 0 10.752-1.298.25.25 0 01-.126-.217V1.75zM8.75 3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM6 5.25a.75.75 0 01.75-.75h.5a.75.75 0 010 1.5h-.5A.75.75 0 016 5.25zm2 1.5A.75.75 0 018.75 6h.5a.75.75 0 010 1.5h-.5A.75.75 0 018 6.75zm-1.25.75a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM8 9.75A.75.75 0 018.75 9h.5a.75.75 0 010 1.5h-.5A.75.75 0 018 9.75zm-.75.75a1.75 1.75 0 00-1.75 1.75v3c0 .414.336.75.75.75h2.5a.75.75 0 00.75-.75v-3a1.75 1.75 0 00-1.75-1.75h-.5zM7 12.25a.25.25 0 01.25-.25h.5a.25.25 0 01.25.25v2.25H7v-2.25z"></path>
</svg> <--icono zip


```
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star mr-2">
    <path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path>
</svg>
```
-->
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star mr-2">
    <path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path>
</svg> <-- Star


```
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye mr-2">
    <path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path>
</svg>
```
-->
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye mr-2">
    <path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path>
</svg> <-- eye


```
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book mr-2">
    <path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path>
</svg> 
```
-->
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book mr-2">
    <path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path>
</svg> <-- book

// rocket
```
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-rocket">
    <path fill-rule="evenodd" d="M14.064 0a8.75 8.75 0 00-6.187 2.563l-.459.458c-.314.314-.616.641-.904.979H3.31a1.75 1.75 0 00-1.49.833L.11 7.607a.75.75 0 00.418 1.11l3.102.954c.037.051.079.1.124.145l2.429 2.428c.046.046.094.088.145.125l.954 3.102a.75.75 0 001.11.418l2.774-1.707a1.75 1.75 0 00.833-1.49V9.485c.338-.288.665-.59.979-.904l.458-.459A8.75 8.75 0 0016 1.936V1.75A1.75 1.75 0 0014.25 0h-.186zM10.5 10.625c-.088.06-.177.118-.266.175l-2.35 1.521.548 1.783 1.949-1.2a.25.25 0 00.119-.213v-2.066zM3.678 8.116L5.2 5.766c.058-.09.117-.178.176-.266H3.309a.25.25 0 00-.213.119l-1.2 1.95 1.782.547zm5.26-4.493A7.25 7.25 0 0114.063 1.5h.186a.25.25 0 01.25.25v.186a7.25 7.25 0 01-2.123 5.127l-.459.458a15.21 15.21 0 01-2.499 2.02l-2.317 1.5-2.143-2.143 1.5-2.317a15.25 15.25 0 012.02-2.5l.458-.458h.002zM12 5a1 1 0 11-2 0 1 1 0 012 0zm-8.44 9.56a1.5 1.5 0 10-2.12-2.12c-.734.73-1.047 2.332-1.15 3.003a.23.23 0 00.265.265c.671-.103 2.273-.416 3.005-1.148z"></path>
</svg>
```
-->
<svg aria-hidden="true" height="16" viewBox="0 0 16 16" width="16" class="svg-icon">
    <path fill-rule="none" d="M14.064 0a8.75 8.75 0 00-6.187 2.563l-.459.458c-.314.314-.616.641-.904.979H3.31a1.75 1.75 0 00-1.49.833L.11 7.607a.75.75 0 00.418 1.11l3.102.954c.037.051.079.1.124.145l2.429 2.428c.046.046.094.088.145.125l.954 3.102a.75.75 0 001.11.418l2.774-1.707a1.75 1.75 0 00.833-1.49V9.485c.338-.288.665-.59.979-.904l.458-.459A8.75 8.75 0 0016 1.936V1.75A1.75 1.75 0 0014.25 0h-.186zM10.5 10.625c-.088.06-.177.118-.266.175l-2.35 1.521.548 1.783 1.949-1.2a.25.25 0 00.119-.213v-2.066zM3.678 8.116L5.2 5.766c.058-.09.117-.178.176-.266H3.309a.25.25 0 00-.213.119l-1.2 1.95 1.782.547zm5.26-4.493A7.25 7.25 0 0114.063 1.5h.186a.25.25 0 01.25.25v.186a7.25 7.25 0 01-2.123 5.127l-.459.458a15.21 15.21 0 01-2.499 2.02l-2.317 1.5-2.143-2.143 1.5-2.317a15.25 15.25 0 012.02-2.5l.458-.458h.002zM12 5a1 1 0 11-2 0 1 1 0 012 0zm-8.44 9.56a1.5 1.5 0 10-2.12-2.12c-.734.73-1.047 2.332-1.15 3.003a.23.23 0 00.265.265c.671-.103 2.273-.416 3.005-1.148z"></path>
</svg> <-- rocker

```
// C3PO star war
<svg class="svg-icon" viewBox="0 0 20 20">
							<path fill="none" d="M5.177,17.658c0,0,3.445,1.987,4.823,1.987c2.067,0,4.823-1.987,4.823-1.987c0.024-0.025,0.044-0.054,0.068-0.08H5.109C5.133,17.604,5.153,17.633,5.177,17.658z M8.622,1.583V0.531C6.496,0.973,2.539,2.521,1.376,7.933H0.699c-0.189,0-0.344,0.155-0.344,0.344v1.378C0.354,9.845,0.509,10,0.699,10h0.392c-0.016,0.224-0.026,0.454-0.033,0.689H0.699c-0.189,0-0.344,0.155-0.344,0.344v1.378c0,0.189,0.155,0.344,0.344,0.344h0.439c0.089,0.79,0.262,1.804,0.594,2.849v2.663H4.34c-2.233-2.449-2.264-6.822-2.264-7.01C2.077,4.052,6.353,2.108,8.622,1.583zM10.689,0.354H9.311v2.059h1.378V0.354z M11.378,2.63v0.472H8.622V2.63C6.612,3.147,3.11,4.951,3.11,11.258c0,0,0.004,3.373,1.47,5.632h4.042v-0.689h2.756v0.689h4.042c1.466-2.259,1.47-5.632,1.47-5.632C16.89,4.951,13.388,3.147,11.378,2.63z M5.005,12.035c-0.318-0.364-0.517-0.833-0.517-1.354S4.687,9.69,5.005,9.327V12.035zM6.383,10.026c-0.295,0.078-0.517,0.335-0.517,0.654c0,0.319,0.222,0.576,0.517,0.654v1.395c-0.384-0.032-0.738-0.163-1.033-0.377V9.008c0.296-0.214,0.649-0.345,1.033-0.377V10.026z M7.761,12.353c-0.296,0.214-0.649,0.345-1.033,0.377v-1.395C7.022,11.257,7.244,11,7.244,10.681c0-0.319-0.222-0.576-0.517-0.654V8.631c0.384,0.032,0.738,0.163,1.033,0.377V12.353zM8.105,12.035V9.327c0.318,0.363,0.517,0.833,0.517,1.354S8.423,11.671,8.105,12.035z M10,13.445l-1.378,0.689L10,12.756l1.378,1.378L10,13.445z M11.895,12.035c-0.318-0.364-0.517-0.833-0.517-1.354s0.199-0.991,0.517-1.354V12.035z M13.273,10.026c-0.295,0.078-0.517,0.335-0.517,0.654c0,0.319,0.222,0.576,0.517,0.654v1.395c-0.384-0.032-0.738-0.163-1.033-0.377V9.008c0.296-0.214,0.649-0.345,1.033-0.377V10.026z M14.651,12.353c-0.296,0.214-0.649,0.345-1.033,0.377v-1.395c0.295-0.078,0.517-0.335,0.517-0.654c0-0.319-0.222-0.576-0.517-0.654V8.631c0.384,0.032,0.738,0.163,1.033,0.377V12.353zM14.995,12.035V9.327c0.318,0.363,0.517,0.833,0.517,1.354S15.313,11.671,14.995,12.035z M19.646,9.656V8.278c0-0.189-0.155-0.344-0.344-0.344h-0.678c-1.163-5.413-5.12-6.96-7.246-7.402v1.052c2.269,0.525,6.545,2.469,6.545,9.675c0,0.188-0.031,4.561-2.264,7.01h2.608v-2.663c0.333-1.044,0.505-2.058,0.594-2.849h0.439c0.189,0,0.344-0.155,0.344-0.344v-1.378c0-0.189-0.155-0.344-0.344-0.344h-0.359c-0.007-0.235-0.017-0.465-0.033-0.689h0.392C19.491,10,19.646,9.845,19.646,9.656z"></path>
</svg>

<<<<< svgicons.ccs >>>>

/* -----
SVG Icons - svgicons.sparkk.fr
----- */

.svg-icon {
  width: 1em;
  height: 1em;
}

.svg-icon path,
.svg-icon polygon,
.svg-icon rect {
  fill: #4691f6;
}

.svg-icon circle {
  stroke: #4691f6;
  stroke-width: 1;
}

```
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

```
| Name      | Purpose                                         |
|-----------|-------------------------------------------------|
| `DEBUG`   | Enables/disables specific debugging namespaces. |
| `DEBUG_HIDE_DATE` | Hide date from debug output (non-TTY).  |
| `DEBUG_COLORS`| Whether or not to use colors in the debug output. |
| `DEBUG_DEPTH` | Object inspection depth.                    |
| `DEBUG_SHOW_HIDDEN` | Shows hidden properties on inspected objects. |
```
| Name      | Purpose                                         |
|-----------|-------------------------------------------------|
| `DEBUG`   | Enables/disables specific debugging namespaces. |
| `DEBUG_HIDE_DATE` | Hide date from debug output (non-TTY).  |
| `DEBUG_COLORS`| Whether or not to use colors in the debug output. |
| `DEBUG_DEPTH` | Object inspection depth.                    |
| `DEBUG_SHOW_HIDDEN` | Shows hidden properties on inspected objects. |

```
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --------- | --------- | --------- |
| renglón 1, columna 1 | renglón 1, columna 2 | renglón 1, columna 3|
| renglón 2, columna 1 | renglón 2, columna 2 | renglón 2, columna 3|
| renglón 3, columna 1 | renglón 3, columna 2 | renglón 3, columna 3|
```
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --------- | --------- | --------- |
| renglón 1, columna 1 | renglón 1, columna 2 | renglón 1, columna 3|
| renglón 2, columna 1 | renglón 2, columna 2 | renglón 2, columna 3|
| renglón 3, columna 1 | renglón 3, columna 2 | renglón 3, columna 3|
<br>

# Lists
Para crear listas desordenadas utiliza * asteriscos, - guiones, o + símbolo de suma.
```
- [x] Lorem ipsum dolor sit amet
- [ ] Lorem consectetur adipisicing elit
- [ ] Lorem ut labore et dfolore
```
- [x] Lorem ipsum dolor sit amet
- [ ] Lorem consectetur adipisicing elit
- [ ] Lorem ut labore et dfolore


```
1. First item
2. Second item
3. Third item
4. Fourth item
```
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

```
* Frutas
  * Manzanas
  * Naranjas
  * Uvas
* Lácteos
  * Leche
  * Queso
```

listado con titulo:

```
Lista de pendientes
------------------
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo
```
Lista de pendientes
------------------
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo

<br>

```
* [Ina219](#Ina219)
  * [new Ina219()](#new_Ina219_new)
  * [.init(address, device)](#Ina219+init)
  * [.enableLogging(enable)](#Ina219+enableLogging)
  * [.writeRegister(register, value, callback)](#Ina219+writeRegister)
  * [.readRegister(register, callback)](#Ina219+readRegister)
  * [.calibrate32V1A(callback)](#Ina219+calibrate32V1A)
  * [.log(s)](#Ina219+log)
```

* [Ina219](#Ina219)
  * [new Ina219()](#new_Ina219_new)
  * [.init(address, device)](#Ina219+init)
  * [.enableLogging(enable)](#Ina219+enableLogging)
  * [.writeRegister(register, value, callback)](#Ina219+writeRegister)
  * [.readRegister(register, callback)](#Ina219+readRegister)
  * [.calibrate32V1A(callback)](#Ina219+calibrate32V1A)
  * [.log(s)](#Ina219+log)

```
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
```

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

1. OS-Raspberry --------------
<img src="https://img.shields.io/badge/OS%20-Raspbian%20GNU%2FLinux%2011%20(bulleye)-yellowgreen">

<img src="https://img.shields.io/badge/OS%20-Raspbian%20GNU%2FLinux%2010%20(buster)-yellowgreen">


2. OS ------------------------
Linux
<img src="https://img.shields.io/badge/OS-Linux%20GNU-yellowgreen">

OS-Windows
<img src="https://img.shields.io/badge/OS-Windows%2011-blue">


3. Hardware------------------
Raspberry 4
<img src="https://img.shields.io/badge/Hardware-Raspberry%20ver%204-red">

Raspberry 3B+
<img src="https://img.shields.io/badge/Hardware-Raspberry%203B%2B-red">

Raspberry Zero
<img src="https://img.shields.io/badge/Hardware-Raspberry%20Zero-red">

Hardware-Arduino
<img src="https://img.shields.io/badge/Hardware-Arduino__nano-red">

Hardware-ESP32
<img src="https://img.shields.io/badge/Hardware-ESP32-red">



4. Node ver ----------------------------------------
<img src="https://img.shields.io/badge/Node%20-V18.7.0-green">


5. Python ----------------------------------------
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







