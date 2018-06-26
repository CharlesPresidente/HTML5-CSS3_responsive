# HTML5/CSS3 - Resposivo

Layout Responsivo utilizando Media Queries.

## Arquivos

### .html

	<!DOCTYPE html>
	<html  lang="pt">
		<head>
			<meta  charset="UTF-8">
			<meta  name="viewport"  content="width=device-width, initial-scale=1.0">
			<meta  http-equiv="X-UA-Compatible"  content="ie=edge">
			<title>Document</title>
		</head>
		
		<div class="container">
            <h1>Layout Responsivo</h1>
            <p>Utilizando html5, Css3 e media Queries</p>
        </div>
	</html>

### .css
Destaque para os elementos sinalizados com as setas:

	<style type="text/css">
		body {
            width: 100%;
            height: 100vh;
            margin: 0;
            padding: 0;
            text-align: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-transform: uppercase;
            color: white;
            background-image: url(../HTML5-CSS3_responsive/img/bg.jpg);
            background-size: cover; <--
            background-repeat: no-repeat;
            background-position: 50% 50%;
            display: table; <--
        }

        .container {
            margin-top: 220px;
        }

        h1 {
            font-weight: 300;
            font-size: 500%;
            margin-bottom: 0;
        }

        p {
            font-weight: lighter;
            letter-spacing: 15px;
            font-style: 20px;
            margin-top: 10px;
        }

        @media (max-width: 768px) { <--
            h1 {
                font-size: 300%;
            }
            p {
                letter-spacing: 5px;
                font-style: 17px;
            }
        }
	</style>
