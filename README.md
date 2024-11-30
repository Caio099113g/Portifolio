# <!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="estilo.css">
    <script src="app.js" async></script>
    <title>ꜱᴇɢᴜɴᴅᴏꜱ ᴘʀᴇᴄɪᴏꜱᴏꜱ</title>
</head>

<body>
    <header>
        <h1>―𝐒𝐞𝐠𝐮𝐧𝐝𝐨𝐬 𝐏𝐫𝐞𝐜𝐢𝐨𝐬𝐨𝐬―</h1>
    </header>
    <section class="contenedor">

        <div class="contenedor-items">
            <div class="item">
                <span class="titulo-item">Box Engasse</span>
                <img src="boxengasse.png" alt="" class="img-item">
                <span class="precio-item">$15.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">English Horse</span>
                <img src="englishrose.png" alt="" class="img-item">
                <span class="precio-item">$25.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Knock Nap</span>
                <img src="knocknap.png" alt="" class="img-item">
                <span class="precio-item">$35.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">La Night</span>
                <img src="lanight.png" alt="" class="img-item">
                <span class="precio-item">$18.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Silver All</span>
                <img src="silverall.png" alt="" class="img-item">
                <span class="precio-item">$32.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Skin Glam</span>
                <img src="skinglam.png" alt="" class="img-item">
                <span class="precio-item">$18.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Midimix</span>
                <img src="midimix.png" alt="" class="img-item">
                <span class="precio-item">$54.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Sir Blue</span>
                <img src="sirblue.png" alt="" class="img-item">
                <span class="precio-item">$32.000</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
            <div class="item">
                <span class="titulo-item">Middlesteel</span>
                <img src="middlesteel.png" alt="" class="img-item">
                <span class="precio-item">$42.800</span>
                <button class="boton-item">Adicione ao Carrinho</button>
            </div>
        </div>

        <div class="carrito" id="carrito">
            <div class="header-carrito">
                <h2>Seu Carrinho</h2>
            </div>

            <div class="carrito-items">

                <div class="carrito-item">
                    <img src="boxengasse.png" width="80px" alt="">
                    <div class="carrito-item-detalles">
                        <span class="carrito-item-titulo">Box Engasse</span>
                        <div class="selector-cantidad">
                            <i class="fa-solid fa-minus restar-cantidad"></i>
                            <input type="text" value="1" class="carrito-item-cantidad" disabled>
                            <i class="fa-solid fa-plus sumar-cantidad"></i>
                        </div>
                        <span class="carrito-item-precio">$15.000,00</span>
                    </div>
                    <span class="btn-eliminar">
                        <i class="fa-solid fa-trash"></i>
                    </span>
                </div>
                <div class="carrito-item">
                    <img src="skinglam.png" width="80px" alt="">
                    <div class="carrito-item-detalles">
                        <span class="carrito-item-titulo">Skin Glam</span>
                        <div class="selector-cantidad">
                            <i class="fa-solid fa-minus restar-cantidad"></i>
                            <input type="text" value="2" class="carrito-item-cantidad" disabled>
                            <i class="fa-solid fa-plus sumar-cantidad"></i>
                        </div>
                        <span class="carrito-item-precio">$18.000,00</span>
                    </div>
                    <button class="btn-eliminar">
                        <i class="fa-solid fa-trash"></i>
                    </button>
                </div>

            </div>
            <div class="carrito-total">
                <div class="fila">
                    <strong>Total</strong>
                    <span class="carrito-precio-total">
                        $120.000,00
                    </span>
                </div>
                <button class="btn-pagar">Pagar <i class="fa-solid fa-bag-shopping"></i> </button>
            </div>
        </div>
    </section>
</body>

</html>
