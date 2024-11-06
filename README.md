# Sarcina1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tema: Administrarea repozitoriului. Sarcini cu administrarea repozitoriului.</title>
    <link rel="stylesheet" href="main.css">
    <style>
      .container {
          width: 1300px;
          height: 500px;
          margin: 100px auto;
          background-color: rgb(68, 68, 68);
          display: flex;
          gap: 60px;
          justify-content: center;
          border-radius: 5px;
          box-shadow: 10px 10px 20px grey;
      }
      .block {
          background-color: grey;
          color: white;
          width: 100px;
          height: 100px;
          font-size: 90px;
          text-align: center;
          margin-top: 100px;
          border-radius: 10px;

      }
      .block:hover {
          cursor: pointer;
          transition: ease-in-out .5s ;
          transform: rotate(360deg);
          color: rgb(221, 219, 219);
          background-color: rgb(29, 29, 29);
          border: 3px solid white;
          box-shadow: 0px 0px 40px 20px rgb(224, 224, 224);
          border-radius: 100%;
      }
    </style>
</head>

<body>
    <div class="container">
        <div class="block">1</div>
        <div class="block">2</div>
        <div class="block">3</div>
        <div class="block">4</div>
        <div class="block">5</div>
    </div>
</body>

</html>
