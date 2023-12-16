# FrontMentor-Qrcode

Este projeto consiste em um layout simples para um componente QR code, criado utilizando HTML, CSS e SASS para atender a um desafio proposto pelo Frontend Mentor.

## Modelo Original

![chrome_yUrm36tfrY](https://github.com/Ykaro1/FrontMentor-Qrcode/assets/125940569/d053e303-184e-4165-974f-74a40c5bdfc2)


## Modelo Personalizado

![chrome_skyEal6pK0](https://github.com/Ykaro1/FrontMentor-Qrcode/assets/125940569/d2a71c3a-a436-4c7f-83c0-119c00083a85)


## Estrutura do Código

### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="icon" href="/images/favicon-32x32.png" />
    <link rel="stylesheet" href="/estilo/style1.css" />
    <title>Qrcode</title>
  </head>
<body>
  <main>
    <div class="first-container">
    <div class="container">
      
      <img src="/images/image-qr-code.png" alt="Qrcode" />

      <div>
        <h1>Improve your front-end <br/>
        <span>skills by building projects</span>
      </div>

      <div>
        <p>Scan the QR code to visit Frontend <br> 
        <span>Mentor and take your coding skills to </span> 
        <span>the next level</span>
        </p>
      </div>
    </div>
    </div>
  </main>
</body>
</html>
```
### SASS // CSS

```SASS
body {
  margin: 0;
}

// Cores
$primary: hsl(212, 45%, 89%);

@import url("https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@100&family=Outfit:wght@400;500&display=swap");

main {
  background-color: $primary;
  margin: 0;
  font-family: "Hanken Grotesk", sans-serif;
  font-family: "Outfit", sans-serif;

  .first-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: white;
    width: 300px;
    height: 53%;
    border-radius: 20px;
    img {
      width: 91%;
      border-radius: 10px;
      margin: auto;
    }
    h1 {
      display: flex;
      flex-direction: column;
      align-items: center;
      font-size: 22px;
      font-weight: bold;
      color: hsl(218, 44%, 22%);
      margin-bottom: -4px;
    }
    p {
      display: flex;
      flex-direction: column;
      align-items: center;
      font-size: 16px;
      opacity: 0.9;
      color: hsl(220, 15%, 55%);
    }
  }
}
```
