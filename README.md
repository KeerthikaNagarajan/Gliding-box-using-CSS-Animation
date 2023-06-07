# Exp 10 Create a Gliding box using CSS Animation
## Program:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Hovering</title>
    <link href="https://fonts.googleapis.com/css?family=Archivo+Black&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Archivo:700&display=swap" rel="stylesheet">
    <style>
      .card {
      background-color: var(--background);
      display: block;
      width: 300px;
      min-height: 90px;
      cursor: pointer;
      padding: 15px;
      margin: calc(50vh - 30px) auto 0 auto;
      border: 3px solid var(--primary);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
                  20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
                  30px -30px 0 -3px var(--background), 30px -30px var(--orange),
                  40px -40px 0 -3px var(--background), 40px -40px var(--red);
    }
    .card:hover {
      animation: shadow-wave 1s ease infinite;
    }
    @keyframes shadow-wave {
      90% {
        border: 3px solid var(--primary);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
          20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
          30px -30px 0 -3px var(--background), 30px -30px var(--orange),
          40px -40px 0 -3px var(--background), 40px -40px var(--red);
      }
      20% {
        border: 3px solid var(--red);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--primary),
          20px -20px 0 -3px var(--background), 20px -20px var(--green),
          30px -30px 0 -3px var(--background), 30px -30px var(--yellow),
          40px -40px 0 -3px var(--background), 40px -40px var(--orange);
      }
      40% {
        border: 3px solid var(--orange);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--red),
          20px -20px 0 -3px var(--background), 20px -20px var(--primary),
          30px -30px 0 -3px var(--background), 30px -30px var(--green),
          40px -40px 0 -3px var(--background), 40px -40px var(--yellow);
      }
      60% {
        border: 3px solid var(--yellow);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--orange),
          20px -20px 0 -3px var(--background), 20px -20px var(--red),
          30px -30px 0 -3px var(--background), 30px -30px var(--primary),
          40px -40px 0 -3px var(--background), 40px -40px var(--green);
      }
      80% {
        border: 3px solid var(--green);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--yellow),
          20px -20px 0 -3px var(--background), 20px -20px var(--orange),
          30px -30px 0 -3px var(--background), 30px -30px var(--red),
          40px -40px 0 -3px var(--background), 40px -40px var(--primary);
      }
      100% {
        border: 3px solid var(--primary);
        box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
          20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
          30px -30px 0 -3px var(--background), 30px -30px var(--orange),
          40px -40px 0 -3px var(--background), 40px -40px var(--red);
      }
    }
    :root {
      --primary: #22D2A0;
      --secondary: #192824;
      --background: #192824;
      --green: #1FC11B;
      --yellow: #FFD913;
      --orange: #FF9C55;
      --red: #FF5555;
    } 
    *{
      padding: 0;
      margin: 0;
      box-sizing: border-box;
    }
    body {
      background-image: radial-gradient(var(--secondary) 30%, var(--background) 30%);
      background-size: 2px 3px;
      font-family: "Archivo", sans-serif;
      color: var(--primary);
    }
    .card p {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 10px;
    }
    .card h2 {
      font-size: 14px;
      font-family: "Archivo Black", "Archivo", sans-serif;
      font-weight: normal;
    }
    </style>
</head>
<body>
  <div class="card">
      <p>Similar post</p>
      <h2>How I recreated a Polaroid camera with CSS gradients only</h2>
    </div>
</body>
</html>
```
## Output:
### Gliding Animation:

![1](https://github.com/KeerthikaNagarajan/Gliding-box-using-CSS-Animation/assets/93427089/f889ea32-3226-4824-9a52-5cdbb74b470e)

### On Cursor Hover:
![2](https://github.com/KeerthikaNagarajan/Gliding-box-using-CSS-Animation/assets/93427089/e912e780-a3cb-4068-b060-30235e54b2e4)

