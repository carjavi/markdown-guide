<p align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/markdown/markdown-original.svg" height="300" alt=" " /></p>
<h1 align="center">Markdown Guide</h1> 
<h4 align="right">Aug 22</h4>


- [Comenzando 🚀](#comenzando-)
- [Header](#header)
- [Encabezado nivel 1](#encabezado-nivel-1)
  - [Encabezado nivel 2](#encabezado-nivel-2)
    - [Encabezado nivel 3](#encabezado-nivel-3)
      - [Encabezado nivel 4](#encabezado-nivel-4)
        - [Encabezado nivel 5](#encabezado-nivel-5)
          - [Encabezado nivel 6](#encabezado-nivel-6)
- [Text Format](#text-format)
    - [comment not visible in markdown](#comment-not-visible-in-markdown)
  - [Additional Line Spacing](#additional-line-spacing)
  - [Blockquotes](#blockquotes)
  - [Admonitions](#admonitions)
- [Alertas](#alertas)
- [Footnote](#footnote)
- [Table of contents](#table-of-contents)
- [Links](#links)
  - [Linking to Heading](#linking-to-heading)
- [Images](#images)
  - [Image Size](#image-size)
  - [Align Text \& images](#align-text--images)
  - [Justificar Texto](#justificar-texto)
  - [Alinear Verticalmente Imagen y Texto (align="middle")](#alinear-verticalmente-imagen-y-texto-alignmiddle)
  - [Image in paragraphs:](#image-in-paragraphs)
  - [Linking Images](#linking-images)
- [Markdown-badges Shieds](#markdown-badges-shieds)
  - [Custotm Shieds Static](#custotm-shieds-static)
  - [Local image github](#local-image-github)
- [Code](#code)
- [Horizontal lines](#horizontal-lines)
- [Tables](#tables)
- [Tables HTML](#tables-html)
- [Lists](#lists)
  - [Lista de pendientes](#lista-de-pendientes)
- [Caracteres Especiales](#caracteres-especiales)
- [Videos](#videos)
    - [Youtube Video: Life as an Engineer - WFH](#youtube-video-life-as-an-engineer---wfh)
- [Info](#info)
- [Samples](#samples)
  - [Authors](#authors)
- [License](#license)
- [Insert Animation AR into HTML (no Markdown)](#insert-animation-ar-into-html-no-markdown)
  - [Autores](#autores)
- [My style](#my-style)
  - [listening on Spotify now!](#listening-on-spotify-now)
  - [Contador de visitas](#contador-de-visitas)
- [HTML  Tag](#html--tag)
- [With custom styles (Only HTML, not Markdown)](#with-custom-styles-only-html-not-markdown)
- [Vincular a otro documento markdown](#vincular-a-otro-documento-markdown)
- [Mi marca](#mi-marca)
  - [Etiqueta normalizada para mi código como desarrollador (sample)](#etiqueta-normalizada-para-mi-código-como-desarrollador-sample)
  - [Presentación ASCII para mis archivos .sh](#presentación-ascii-para-mis-archivos-sh)
  - [Start \& Sponsors](#start--sponsors)
  - [Shields](#shields)
  - [Titule \& Footer](#titule--footer)

<br>

more: https://docs.github.com/es/get-started

<br>

# Comenzando 🚀

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

# Alertas

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

```
> > [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

```
<br>

# Footnote

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.

[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.

[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

<br>

# Table of contents

De forma automatica:
```
# Titulo
- [titulo](#titulo)
al darle enter crea automaticamente toda la tabla de todo el contenido del archivo Markdown
```

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

## Justificar Texto
```
<p style="text-align: justify;">Párrafo con un texto</p>
```

## Alinear Verticalmente Imagen y Texto (align="middle")
```
<img  align="middle" width="32" height="32" src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/adobe-pdf.svg"> [autorun-install.sh](https://url.com)
```
<img  align="middle" width="32" height="32" src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/adobe-pdf.svg"> [file PDF](https://url.com)
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

<br>

# Markdown-badges Shieds 

``` 
https://img.shields.io/badge/<your label>-<value>-<background color>.svg?&style=for-the-badge&logo=<icon here>

``` 

``` 
<img src="https://img.shields.io/badge/Python-3.7-<background color>.svg?&style=for-the-badge&logo=python">

<img src="https://img.shields.io/badge/Javascript-3.7-<background color>.svg?&style=for-the-badge&logo=javascript">

<img src="https://img.shields.io/badge/linux-3.7-<background color>.svg?&style=for-the-badge&logo=linux">

<img src="https://img.shields.io/badge/twitter-mohammed__16695-1da1f2.svg?&style=for-the-badge&logo=twitter">



[![Linux](https://img.shields.io/badge/Linux-0f80c0?logo=linux&logoColor=white)](https://)

[![Windows](https://img.shields.io/badge/Windows-0f80c0?logo=windows&logoColor=white)](https://)

[![macOS](https://img.shields.io/badge/macOS-0f80c0?logo=apple&logoColor=white)](https://)

![Amazon Alexa](https://img.shields.io/badge/amazon%20alexa-52b5f7?style=for-the-badge&logo=amazon%20alexa&logoColor=white)

![Google Assistant](https://img.shields.io/badge/google%20assistant-4285F4?style=for-the-badge&logo=google%20assistant&logoColor=white)

![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)

![IE](https://img.shields.io/badge/Internet%20Explorer-0076D6?style=for-the-badge&logo=Internet%20Explorer&logoColor=white)

![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white)

![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)

![Dropbox](https://img.shields.io/badge/Dropbox-%233B4D98.svg?style=for-the-badge&logo=Dropbox&logoColor=white)

![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

![Mega.nz](https://img.shields.io/badge/Mega-%23D90007.svg?style=for-the-badge&logo=Mega&logoColor=white)

![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)

![OneDrive](https://img.shields.io/badge/OneDrive-0078D4.svg?style=for-the-badge&logo=microsoftonedrive&logoColor=white)

![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)

![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)

![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)

![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white)

![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)

![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)

![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)

![Google Pay](https://img.shields.io/badge/GooglePay-%233780F1.svg?style=for-the-badge&logo=Google-Pay&logoColor=white)

![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)

![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

![github pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)

![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)

![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)

![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

![Lubuntu](https://img.shields.io/badge/-Lubuntu-%230065C2?style=for-the-badge&logo=lubuntu&logoColor=white)

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)

![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

![Home Assistant](https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white)

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)

![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)

![Yahoo!](https://img.shields.io/badge/Yahoo!-6001D2?style=for-the-badge&logo=Yahoo!&logoColor=white)

![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)

![Skype](https://img.shields.io/badge/Skype-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white)

![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)

```
<img src="https://img.shields.io/badge/Python-3.7-<background color>.svg?&style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Javascript-3.7-<background color>.svg?&style=for-the-badge&logo=javascript">
<img src="https://img.shields.io/badge/linux-20.4-<background color>.svg?&style=for-the-badge&logo=linux">
<img src="https://img.shields.io/badge/twitter-mohammed__16695-1da1f2.svg?&style=for-the-badge&logo=twitter">

<br>

[![Linux](https://img.shields.io/badge/Linux-0f80c0?logo=linux&logoColor=white)](https://)

[![Windows](https://img.shields.io/badge/Windows-0f80c0?logo=windows&logoColor=white)](https://)

[![macOS](https://img.shields.io/badge/macOS-0f80c0?logo=apple&logoColor=white)](https://)

![Amazon Alexa](https://img.shields.io/badge/amazon%20alexa-52b5f7?style=for-the-badge&logo=amazon%20alexa&logoColor=white)

![Google Assistant](https://img.shields.io/badge/google%20assistant-4285F4?style=for-the-badge&logo=google%20assistant&logoColor=white)

![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)

![IE](https://img.shields.io/badge/Internet%20Explorer-0076D6?style=for-the-badge&logo=Internet%20Explorer&logoColor=white)

![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white)

![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)

![Dropbox](https://img.shields.io/badge/Dropbox-%233B4D98.svg?style=for-the-badge&logo=Dropbox&logoColor=white)

![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

![Mega.nz](https://img.shields.io/badge/Mega-%23D90007.svg?style=for-the-badge&logo=Mega&logoColor=white)

![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)

![OneDrive](https://img.shields.io/badge/OneDrive-0078D4.svg?style=for-the-badge&logo=microsoftonedrive&logoColor=white)

![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)

![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)

![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)

![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white)

![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)

![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)

![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)

![Google Pay](https://img.shields.io/badge/GooglePay-%233780F1.svg?style=for-the-badge&logo=Google-Pay&logoColor=white)

![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)

![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

![github pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)

![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)

![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)

![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

![Lubuntu](https://img.shields.io/badge/-Lubuntu-%230065C2?style=for-the-badge&logo=lubuntu&logoColor=white)

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)

![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

![Home Assistant](https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white)

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)

![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)

![Yahoo!](https://img.shields.io/badge/Yahoo!-6001D2?style=for-the-badge&logo=Yahoo!&logoColor=white)

![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)

![Skype](https://img.shields.io/badge/Skype-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white)

![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)


LINK: https://ileriayo.github.io/markdown-badges/

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

# Tables HTML
Tabla sin filas:
```
<!-- Nueva tabla -->
<table style="border-collapse: collapse;border-top: 0.5pt solid ; border-bottom: 0.5pt solid ; ">
    <colgroup><col align="left"><col align="left"><col align="left"></colgroup>
    <thead>
	<!-- Encabezado de la tabla -->
	<tr>
	   <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Command</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Action</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Example usage and subcommand examples</p></th>
	</tr>
    </thead>
    <tbody>
    <!-- aqui van las filas-->
    </tbody>
</table>
```
Output:
<!-- Nueva tabla -->
<table style="border-collapse: collapse;border-top: 0.5pt solid ; border-bottom: 0.5pt solid ; ">
    <colgroup><col align="left"><col align="left"><col align="left"></colgroup>
    <thead>
	<!-- Encabezado de la tabla -->
	<tr>
	   <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Command</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Action</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Example usage and subcommand examples</p></th>
	</tr>
    </thead>
    <tbody>
    <!-- aqui van las filas-->
    </tbody>
</table>

<br>

Tabla con filas:

```
<!-- Nueva tabla -->
<table style="border-collapse: collapse;border-top: 0.5pt solid ; border-bottom: 0.5pt solid ; ">
    <colgroup><col align="left"><col align="left"><col align="left"></colgroup>
    <thead>
	<!-- Encabezado de la tabla -->
	<tr>
	   <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Command</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Action</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Example usage and subcommand examples</p></th>
	</tr>
    </thead>
    <tbody>
	<!-- Example fila comandos 1 -->
	<tr>
	   <td style="" align="left" valign="top"><p><code class="literal">COMMANDS</code></p></td>
	   <td style="" align="left" valign="top"><p>DESCRIPCION</p></td>
	   <td style="" align="left" valign="top"><p><code class="literal">$ ros command [parameter]</code></p></td>
	</tr>
	<!-- Example fila comandos 1 end -->
	<!-- Example fila comandos 2 -->
	 <tr>
	    <td style="" align="left" valign="top"><p><code class="literal">COMANDO-ROS</code></p></td>
	    <td style="" align="left" valign="top"><p>DESCRIPCION</p></td>
	    <td style="" align="left" valign="top"><p><code class="literal">$ rosxxx &lt;subcommand&gt; [parameter]</code></p>
            <p>Subcommands: <code class="literal">get</code>, <code class="literal">set</code>, <code class="literal">list</code>, and <code class="literal">delete</code></p></td>
     </tr>
	<!-- Example fila comandos 2 end -->
    <tr>
	   <td style="" align="left" valign="top"><p><code class="literal">rosservice</code></p></td>
	   <td style="" align="left" valign="top"><p>A tool for listing and querying ROS services.</p></td>
	   <td style="" align="left" valign="top">
            <p><code class="literal">$ rosservice list</code> Print information about active services.</p>
            <p>Launch a file in a package: <code class="literal">$ roslaunch package filename.launch</code></p>
            <p><code class="literal">$ rosservice list</code> Print information about active services.</p>
       </td>
	</tr>
    <tr>
	    <td style="" align="left" valign="top"><p><code class="literal">rosed</code></p></td>
	    <td style="" align="left" valign="top"><p>It allows you to directly edit a file within a package by package name rather than having to know the package path.</p></td>
	    <td style="" align="left" valign="top">
                <p>Usage:</p>
                <p><code class="literal">$ rosed packagename filename</code></p>
                <p>Example:</p>
                <p><code class="literal">$ rosed roscpp ros.h</code></p>
        </td>
	</tr>
    </tbody>
</table>
<!-- Nueva tabla end -->
```
Output:

<!-- Nueva tabla -->
<table style="border-collapse: collapse;border-top: 0.5pt solid ; border-bottom: 0.5pt solid ; ">
    <colgroup><col align="left"><col align="left"><col align="left"></colgroup>
    <thead>
	<!-- Encabezado de la tabla -->
	<tr>
	   <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Command</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Action</p></th>
           <th style="border-bottom: 0.5pt solid ; " align="left" valign="bottom"><p>Example usage and subcommand examples</p></th>
	</tr>
    </thead>
    <tbody>
	<!-- Example fila comandos 1 -->
	<tr>
	   <td style="" align="left" valign="top"><p><code class="literal">COMMANDS</code></p></td>
	   <td style="" align="left" valign="top"><p>DESCRIPCION</p></td>
	   <td style="" align="left" valign="top"><p><code class="literal">$ ros command [parameter]</code></p></td>
	</tr>
	<!-- Example fila comandos 1 end -->
	<!-- Example fila comandos 2 -->
	 <tr>
	    <td style="" align="left" valign="top"><p><code class="literal">COMANDO-ROS</code></p></td>
	    <td style="" align="left" valign="top"><p>DESCRIPCION</p></td>
	    <td style="" align="left" valign="top"><p><code class="literal">$ rosxxx &lt;subcommand&gt; [parameter]</code></p>
            <p>Subcommands: <code class="literal">get</code>, <code class="literal">set</code>, <code class="literal">list</code>, and <code class="literal">delete</code></p></td>
     </tr>
	<!-- Example fila comandos 2 end -->
    <tr>
	   <td style="" align="left" valign="top"><p><code class="literal">rosservice</code></p></td>
	   <td style="" align="left" valign="top"><p>A tool for listing and querying ROS services.</p></td>
	   <td style="" align="left" valign="top">
            <p><code class="literal">$ rosservice list</code> Print information about active services.</p>
            <p>Launch a file in a package: <code class="literal">$ roslaunch package filename.launch</code></p>
            <p><code class="literal">$ rosservice list</code> Print information about active services.</p>
       </td>
	</tr>
    <tr>
	    <td style="" align="left" valign="top"><p><code class="literal">rosed</code></p></td>
	    <td style="" align="left" valign="top"><p>It allows you to directly edit a file within a package by package name rather than having to know the package path.</p></td>
	    <td style="" align="left" valign="top">
                <p>Usage:</p>
                <p><code class="literal">$ rosed packagename filename</code></p>
                <p>Example:</p>
                <p><code class="literal">$ rosed roscpp ros.h</code></p>
        </td>
	</tr>
    </tbody>
</table>
<!-- Nueva tabla end -->

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

License
=======
Copyright (c) 2012 [Vitaly Puzrin](https://github.com/puzrin).
<br>
MIT © [Sindre Sorhus](http://sindresorhus.com)

<br>

# Insert Animation AR into HTML (no Markdown)
<p align="center"><img src="./img/AR-robot.png" height="200" alt=" " /></p>

```
<html>
	<head>
		<title>Mi página de ejemplo</title>
	</head>
	<body>
        <div class="hero__model">                     
            <iframe id="landing-model" title="A 3D model of a shoe" class="hero__iframe" width="auto" height="auto" src="https://sketchfab.com/models/99bfe75ebd734fa3832a63e02e2cacf7/embed?annotations_visible=0&amp;autospin=-0.1&amp;autostart=1&amp;camera=0&amp;double_click=0&amp;internal=1&amp;max_texture_size=1024&amp;orbit_constraint_pan=1&amp;orbit_constraint_zoom_in=40&amp;orbit_constraint_zoom_out=60&amp;preload=1&amp;scrollwheel=0&amp;sound_enable=0&amp;transparent=1&amp;ui_animations=0&amp;ui_annotations=0&amp;ui_ar=1&amp;ui_ar_help=0&amp;ui_color=white&amp;ui_fadeout=0&amp;ui_fullscreen=1&amp;ui_help=0&amp;ui_infos=0&amp;ui_inspector=0&amp;ui_settings=0&amp;ui_stop=0&amp;ui_theatre=0&amp;ui_theme=dark&amp;ui_vr=0&amp;ui_watermark=0" frameborder="0" allow="autoplay; fullscreen; xr-spatial-tracking" allowfullscreen="" mozallowfullscreen="true" webkitallowfullscreen="true" xr-spatial-tracking="true" execution-while-out-of-viewport="true" execution-while-not-rendered="true" web-share="true"></iframe>                  
        </div>
	</body>
</html>
```

<br>

## Autores

| [<img src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img src="https://avatars.githubusercontent.com/u/71970858?v=4" width=115><br><sub>Ellen Pimentel</sub>]([https://github.com/guilhermeonrails](https://github.com/ellenpimentel)) |  [<img src="https://avatars.githubusercontent.com/u/91544872?v=4" width=115><br><sub>Génesys Rondón</sub>](https://github.com/genesysaluralatam) |
| :---: | :---: | :---: |

```

| [<img src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img src="https://avatars.githubusercontent.com/u/71970858?v=4" width=115><br><sub>Ellen Pimentel</sub>]([https://github.com/guilhermeonrails](https://github.com/ellenpimentel)) |  [<img src="https://avatars.githubusercontent.com/u/91544872?v=4" width=115><br><sub>Génesys Rondón</sub>](https://github.com/genesysaluralatam) |
| :---: | :---: | :---: |
```


<br>

# My style

## listening on Spotify now!
```
### 🎵 listening on Spotify now!
 spotify github profile 
[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=22jsdvk3ryfqzw7bljmxox54a&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=true)](https://github.com/kittinan/spotify-github-profile)
```
[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=22jsdvk3ryfqzw7bljmxox54a&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=true)](https://github.com/kittinan/spotify-github-profile)

source: https://spotify-github-profile.vercel.app/api/login

<br>

## Contador de visitas
```
<!-- Counter Visits:START -->
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fcarjavi%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=Visitors%3A+Today%2FTotal&edge_flat=false)](https://hits.seeyoufarm.com)
<!-- Counter Visits:END -->
```

<!-- Counter Visits:START -->
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fcarjavi%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=Visitors%3A+Today%2FTotal&edge_flat=false)](https://hits.seeyoufarm.com)
<!-- Counter Visits:END -->

<br>

# HTML <kbd> Tag
```
<p>presione <kbd>Ctrl</kbd> + <kbd>↑</kbd>, y para desplazarse hacia abajo, presione <kbd>Ctrl</kbd> + <kbd>↓</kbd>.</p>

<p>Para acceder a la sección de ayuda, presione <a href="https://www.ejemplo.com/ayuda"><kbd>F1</kbd></a>.</p>
<p>Para iniciar el programa, presione <kbd class="teclas">F12</kbd>.</p>

<p>Press <kbd>esc</kbd></p>
<p>Press <kbd>→</kbd></p>
<p><kbd>Ctrl+V</kbd> o <kbd>Shift+Ins</kbd></p>
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd></p>

<kbd><samp>Ok</samp></kbd>
<kbd><samp>Archivo</samp> → <samp>Imprimir...</samp></kbd>

```
<p>presione <kbd>Ctrl</kbd> + <kbd>↑</kbd>, y para desplazarse hacia abajo, presione <kbd>Ctrl</kbd> + <kbd>↓</kbd>.</p>

<p>Para acceder a la sección de ayuda, presione <a href="https://www.ejemplo.com/ayuda"><kbd>F1</kbd></a>.</p>
<p>Para iniciar el programa, presione <kbd class="teclas">F12</kbd>.</p>

<p>Press <kbd>esc</kbd></p>
<p>Press <kbd>→</kbd></p>
<p><kbd>Ctrl+V</kbd> o <kbd>Shift+Ins</kbd></p>
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd></p>

<kbd><samp>Ok</samp></kbd>
<kbd><samp>Archivo</samp> → <samp>Imprimir...</samp></kbd>

<br>

# With custom styles (Only HTML, not Markdown)
```
<style>
		.teclas {
        background-color: #333;
        color: #fff;
        padding: 5px;
        border-radius: 5px;
		}
    .teclas2 {
			      background-color: #eee;
            border-radius: 3px;
            border: 1px solid #b4b4b4;
            box-shadow: 0 1px 1px rgba(0, 0, 0, 0.2), 0 2px 0 0 rgba(255, 255, 255, 0.7) inset;
            color: #333;
            display: inline-block;
            font-size: 0.85em;
            font-weight: 700;
            line-height: 1;
            padding: 2px 4px;
            white-space: nowrap;
		}
    .teclas3 {
			      -moz-border-radius:3px;
            -moz-box-shadow:0 1px 0 rgba(0,0,0,0.2),0 0 0 2px #fff inset;
            -webkit-border-radius:3px;
            -webkit-box-shadow:0 1px 0 rgba(0,0,0,0.2),0 0 0 2px #fff inset;
            background-color:#f7f7f7;
            border:1px solid #ccc;
            border-radius:3px;
            box-shadow:0 1px 0 rgba(0,0,0,0.2),0 0 0 2px #fff inset;
            color:#333;
            display:inline-block;
            font-family:Arial,Helvetica,sans-serif;
            font-size:11px;
            line-height:1.4;
            margin:0 .1em;
            padding:.1em .6em;
            text-shadow:0 1px 0 #fff;
		}
    .teclas4 {
			      padding: 3px 5px;
            background: black;
            color: white;
            border-radius: 5px;
		}
    .teclas5 {
			      display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            padding: 0.1em 0.5em;
            margin: 0 0.2em;
            box-shadow: 0 1px 0px rgba(0, 0, 0, 0.2), 0 0 0 2px #fff inset;
            background-color: #f7f7f
		}
    .teclas6 {
            font-family: Menlo,Consolas,Monaco,andale mono,Courier,Verdana,sans-serif;
			      font-size: 14px;
            color: #4e4e4e;
            background-color: #f7f7f7;
            padding: 4px 7px;
            border: 1px solid #ccc;
            border-radius: 7px;
            box-shadow: 0 1px 0 rgba(0,0,0,.2),0 0 0 1px #fafafa inset,0 0 0 1px #fff inset;
            margin: 0 1px;
		}
</style>

<p><kbd class="teclas">Ctrl</kbd> + <kbd class="teclas">S</kbd></p>

<p><kbd class="teclas2">Ctrl</kbd> + <kbd class="teclas2">S</kbd></p>

<p><kbd class="teclas3">Ctrl</kbd> + <kbd class="teclas3">S</kbd></p>

<p><kbd class="teclas4">Ctrl</kbd> + <kbd class="teclas4">S</kbd></p>

<p><kbd class="teclas6">Ctrl</kbd> + <kbd class="teclas6">S</kbd></p>

<kbd class="teclas5">⌘</kbd>+<kbd class="teclas5">Opt</kbd>+<kbd class="teclas5">Shift</kbd>+<kbd class="teclas5">V</kbd>

```
<p align="center">
    <a href="https://instintodigital.net/" target="_blank"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/key.png" height="250" alt=""></a>
</p>

<br>

# Vincular a otro documento markdown
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

<br>

# Mi marca
```
<div>
  <p>
    <img  align="top" width="42" style="padding:0px 0px 0px 0px;" src="./img/carjavi.png"/>&nbsp;&copy; 2023 Instinto Digital
  </p>
</div>
```

<div>
  <p>
    <img  align="top" width="42" style="padding:0px 0px 0px 0px;" src="./img/carjavi.png"/>&nbsp;&copy; 2023 Instinto Digital
  </p>
</div>

<br>

## Etiqueta normalizada para mi código como desarrollador (sample)
```
/** 
  @fileoverview 
      ver 0.1 XX/2024
  @Author  carjavi <carjavi@hotmail.com>
  @license copyright www.instintodigital.net, Month 2024 
  @Commands
  @Note 
  @Module_npm
    sudo npm i node-gyp
    sudo npm i coffee-script
    sudo npm i i2c
    sudo npm i @abandonware/i2c@^0.2.4-0
**/
```
<br>

## Presentación ASCII para mis archivos .sh

```
#!/usr/bin/env bash

# Define colors
readonly ANSI_RED="\033[0;31m"
readonly ANSI_GREEN="\033[0;32m"
readonly ANSI_YELLOW="\033[0;33m"
readonly ANSI_RASPBERRY="\033[0;35m"
readonly ANSI_ERROR="\033[1;37;41m"
readonly ANSI_RESET="\033[m"
readonly RASPAP_LATEST="2.0"

# Outputs a welcome message
function display_welcome() {
echo -e "${ANSI_RASPBERRY}\n"
echo -e "                            d8b                   d8b" 
echo -e "                            Y8P                   Y8P"
echo -e "                                                     "
echo -e " .d8888b  8888b.  888d888  8888  8888b.  888  888 888"
echo -e "d88P'        '88b 888P'    '888     '88b 888  888 888" 
echo -e "888      .d888888 888       888 .d888888 Y88  88P 888" 
echo -e "Y88b.    888  888 888       888 888  888  Y8bd8P  888" 
echo -e " 'Y8888P 'Y888888 888       888 'Y888888   Y88P   888" 
echo -e "                            888                      " 
echo -e "                           d88P                      " 
echo -e "                         888P'                       " 
echo -e "                                                     "
echo -e "${ANSI_GREEN}"
echo -e "The Quick Installer will guide you through a few easy steps${ANSI_RESET}"
echo -e "\033[1;32m***************************************************************$*\033[m"
echo -e "\n\n"
}

# calling Titulo 
display_welcome
    
#sleep 3seg
sleep 3

echo
echo "------------------------------"
echo "Install and ..."
echo "------------------------------"
echo
```

## Start & Sponsors

```

[![GitHub stars](https://img.shields.io/github/stars/carjavi/carjavi?style=flat&logo=github&color=orange)](https://github.com/bblanchon/ArduinoJson/stargazers)

[![GitHub Sponsors](https://img.shields.io/github/sponsors/bblanchon?logo=github&color=orange)](https://github.com/sponsors/carjavi)

```

[![GitHub stars](https://img.shields.io/github/stars/carjavi/carjavi?style=flat&logo=github&color=orange)](https://github.com/bblanchon/ArduinoJson/stargazers)

[![GitHub Sponsors](https://img.shields.io/github/sponsors/bblanchon?logo=github&color=orange)](https://github.com/sponsors/carjavi)

<br>

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


## Titule & Footer
```bash
<p align="center"><img src="./img/logo.png" width="100" height="100"  alt=" " /></p>
<h1 align="center"> Titule </h1> 
<h4 align="right">Month 24</h4>

<img src="https://img.shields.io/badge/OS-Linux%20GNU-yellowgreen">
<img src="https://img.shields.io/badge/OS-Windows%2011-blue">
<img src="https://img.shields.io/badge/Hardware-Raspberry%20ver%204-red">
<img src="https://img.shields.io/badge/Hardware-ESP32-red">

<br>

# Table of contents
- [Table of contents](#Table-of-contents)
- [Install](#Install)
- [Troubleshooting](#Troubleshooting)

<br>

# Install
```bash```
> :memo: **Note:*
> :bulb: **Tip:**


<br>

# Troubleshooting
> :warning: **Warning:**

<br>

---
Copyright &copy; 2022 [carjavi](https://github.com/carjavi). <br>
```www.instintodigital.net``` <br>
carjavi@hotmail.com <br>
<p align="center">
    <a href="https://instintodigital.net/" target="_blank"><img src="./img/developer.png" height="100" alt="www.instintodigital.net"></a>
</p>
```



<br>

<br>

---
Copyright &copy; 2022 [carjavi](https://github.com/carjavi). <br>
```www.instintodigital.net``` <br>
carjavi@hotmail.com <br>
<p align="center">
    <a href="https://instintodigital.net/" target="_blank"><img src="https://raw.githubusercontent.com/carjavi/markdown-guide/master/img/developer.png" height="100" alt="www.instintodigital.net"></a>
</p>







