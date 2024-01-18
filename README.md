# CARD_1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
        @import url("https://fonts.googleapis.com/css2?family=Georama:wght@3008display=swap");

        * {
            margin: 0;
            padding: 0;
            /* box-sizing: border-box; */
            font-family: "Georama", sans-serif;
        }

        body {
            height: 100vh;
            /* display: grid; */
            /* place-items: center; */
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgb(122, 122, 215);
        }

        .main-div {
            width: 600px;
            height: 600px;
            padding: 30px;
            background-color: rgb(100, 241, 194);
            border-radius: 10px;
            clip-path: circle(14.4% at 100% 0);
            transition: 1s;
        }

        .main-div h1 {
            margin: 30px 0;
            color: yellow;
        }

        .main-div p {
            color: white;
            line-height: 150%;
        }

        .main-div h3 {
            color: tomato;
            margin-top: 20px;
        }

        .main-div:hover {
            /* clip-path: circle(141.4% at 100% 0); */
            clip-path: circle(141.4% at 100% 0);

        }
    </style>
</head>

<body>
    <div class="main-div">
        <h1>Lorem ipsum dolor, sit amet consectetur adipisicing.</h1>
        <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odit, quasi
            sit iusto illo pariatur omnis facere delectus sed assumenda libero
            molestias sunt in quae, voluptate ad? Officiis quod praesentium aperiam.
        </p>
        <h3>Lorem ipsum dolor sit.</h3>
    </div>
</body>

</html>
