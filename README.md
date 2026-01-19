<!DOCTYPE html>
<!--
Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
Click nbfs://nbhost/SystemFileSystem/Templates/JSP_Servlet/Html.html to edit this template
-->
<html>
<head>  
    <!--MEU BOOTSTRAP CSS-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!--FIM BOOTSTRAP CSS-->

    <!--MINHA BASE META DADOS-->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="Only Genesis">
    <link rel="apple-touch-icon" href="imagens/icon-192.png">
    <link rel="manifest" href="manifest.json">
    <meta name="theme-color" content="#000000">

    <!--FIM BASE META DADOS\manifest-->
     
    <!--MEU ICON BOOTSTRAP-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <!--FIM ICON BOOTSTRAP-->
      
    <!--GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!-- FIM GOOGLE FONTS --> 

    <!--LINK DO MEU CSS-->
    <link rel="stylesheet" href="style.css" type="text/css"/>
    <!-- FIM LINK DO MEU CSS-->
        
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> agência only.genesis</title>
    </head>
    <body>
     <header class="header-moderno">
        <div class="interface container-fluid px-5"> 
            <div class="d-flex align-items-center justify-content-between">   <div class="interface">
                 <div class="flex">
                 <div class="logo">
                 <a href="#">
                    <img src="imagens/logocasino.jpg" alt="Logo Only Genesis" width="150">
                 </a>
                </div>

            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Projetos</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Serviços</a></li>
                </ul>
            </nav>

            <div class="btn-contato">
                <a href="#">
                    <button class="btn-glow">Contato</button>
                </a>
            </div>
        </div>
    </div>
</header>
<main>
      
 <section class="topo-do-site">
    <div class="interface">
        <div class="flex">
            <div class="txt-topo-site">
                <h1>TRANSFORMANDO IDEIAS EM REALIDADE DIGITAL</h1>
                <p>Criamos soluções de alta performance para empresas que buscam liderar o mercado digital.</p>
                <div class="btn-contato">
                    <a href="#"><button class="btn-glow">Entre em contato</button></a>    
                </div>
            </div>

            <div class="lampada-container">
                <div class="luz-aura"></div>
                <i id="lampada-ideia" class="bi bi-lightbulb"></i>
            </div>
        </div>
    </div>
</section>
            
 <section class="especialidades">
    <div class="interface">
        <div class="especialidades-container">
            <h2 class="titulo-moderno"><span id="typewriter"></span></h2>
        </div>

        <div class="flex-cards">
            <div class="especialidades-box" data-speed="0.1">
                <div class="bg-icon-mov"><i class="bi bi-code-square"></i></div>
                <i class="bi-code-square main-icon"></i>
                <h3>Website</h3>
                <p>Está pronto para impulsionar seu negócio? Somos especialistas em criar websites personalizados.</p>
            </div>

            <div class="especialidades-box" data-speed="0.2">
                <div class="bg-icon-mov"><i class="bi bi-cart"></i></div>
                <i class="bi-cart main-icon"></i>
                <h3>Loja Online</h3>
                <p>Transforme seu negócio com uma loja virtual personalizada e alcance novos clientes de maneira eficiente.</p>
            </div>

            <div class="especialidades-box" data-speed="0.15">
                <div class="bg-icon-mov"><i class="bi bi-whatsapp"></i></div>
                <i class="bi-whatsapp main-icon"></i>
                <h3>WhatsApp & Email</h3>
                <p>Nossa automatização responde seus clientes rapidamente, garantindo comunicação clara 24h por dia.</p>
            </div>
        </div>
    </div>
</section>
<section class="sobre"><!--inicio da minha section sobre os projetos do portifolio-->
    <div class="interface"><!--inicio da minha interface do portifolio-->
        <div class="flex">
            <div class="img-sobre">
                <img src="imagens/casino50.jpg" alt=" " width="250px" height="200px">
            </div>
            <div class="txt-sobre">
                <h2> muito prazer, me chamo <span> julian cesar </span></h2>
                <p>aqui esta meu portfólio de apresentação ,de alguns projetos que ja desenvolvi</p>
                <p></p>
                <div class="btn-social">
                    <a href="#"><button> <i class="bi bi-youtube"></i> </button></a>
                    <a href="#"><button> <i class="bi bi-instagram"></i> </button></a>
                    <a href="#"><button> <i class="bi bi-whatsapp"></i> </button></a>
                </div><!--btn-socil-->
            </div><!--txt-sobre-->   
        </div><!--flex-->
    </div><!--interface-->
</section><!--sobre-->
<section class="portifolio"><!--section imagens do portifolio-->
    <div class="interface"><!--interface das imagens do portifolio-->
        <h2 class="titulo">MEUS PROJETOS</h2><!--titulo do meu portifolio-->
        <div class="flex">
            <div class="img-port" style="background-image: url(imagens/roleta1.jpg);">
                <div class="overlay"> projeto 1</div>
            </div>
            <div class="img-port" style="background-image: url(imagens/roleta1.jpg);">
                <div class="overlay"> projeto 2</div>
            </div>
            <div class="img-port" style="background-image:url(imagens/roleta1.jpg);">
                <div class="overlay"> projeto 3</div>
            </div>
        </div>
            
    </div><!--fim da interface das imagens do portifolio-->
</section><!--fim da section imagens do portifolio-->
<section class="formulario"><!--inicio do meu formulario-->
    <div class="interface"><!--inicio doa minha interface-->
       <h2 class="titulo"> mande uma mensagen para nossa equipe</h2> 
       <form action="">
    <input type="text" name="" id="" placeholder="nome da sua empresa" required="">
    <input type="text" name="" id="" placeholder="seu email" required="">
    <input type="text" name="" id="" placeholder="número de whatsapp">
    <textarea name="" id="" placeholder="deixe sua mensagem para agilizarmos o processo"></textarea>
    <div class="btn-enviar"><input type="submit" value="ENVIAR"></div>
</form>
    </div>
</section>
</main>
    <footer> 
        <div classe="interface"> 
            <div classe="line-footer">
                <div class="flex"> 
                        <div classe="logo-footer">
                    <img src="imagens/poker1.jpg" alt="" width="250px" height="200px"> 
                </div><!--logo-footer-->
           </div><!--btn-socil-->
        </div><!--line-footer-->
        </div><!--fim interface roda pé-->
        <div class="line-footer">
            <p><i class="bi bi-fire"></i> </a></p>
        </div><!--line-footer-->
    </footer>
    <script>
    // Seleciona o elemento H1
    const titulo = document.querySelector('.txt-topo-site h1');
    const textoOriginal = titulo.innerHTML;
    
    // Função para o efeito de digitação
    function typeWrite(elemento) {
        const textoArray = elemento.innerHTML.split('');
        elemento.innerHTML = '';
        textoArray.forEach((letra, i) => {
            setTimeout(() => elemento.innerHTML += letra, 75 * i);
        });
    }
     // Inicia a animação ao carregar
    window.onload = () => {
        typeWrite(titulo);
    };
    document.addEventListener("DOMContentLoaded", () => {
    const containerLampada = document.querySelector('.lampada-container');
    
    // Pequeno delay para o usuário ver a lâmpada apagada antes de ligar
    setTimeout(() => {
        // Efeito de "flicker" (pisca rápido 3 vezes antes de acender)
        let flashes = 0;
        const intervalo = setInterval(() => {
            containerLampada.classList.toggle('lampada-acesa');
            flashes++;
            if (flashes === 6) { // Após 3 piscadas rápidas
                clearInterval(intervalo);
                containerLampada.classList.add('lampada-acesa'); // Fica acesa de vez
            }
        }, 100);
    }, 1500); // Acende 1.5 segundos após carregar
});
    const frases = [
    "Impulsionamento de Conteúdo",
    "Automatização para WhatsApp",
    "Desenvolvimento de Sistemas",
    "Web Sites de Alta Conversão",
    "Aplicativos Mobile",
    "Marketing Digital Estratégico"
];

let fraseIndex = 0;
let charIndex = 0;
let isDeleting = false;
const speed = 100; // Velocidade de escrita
const delayEntreFrases = 2000; // Tempo parado na frase completa
const el = document.getElementById("typewriter");

function type() {
    const currentFullText = frases[fraseIndex];
    
    if (isDeleting) {
        // Removendo caracteres
        el.textContent = currentFullText.substring(0, charIndex - 1);
        charIndex--;
    } else {
        // Adicionando caracteres
        el.textContent = currentFullText.substring(0, charIndex + 1);
        charIndex++;
    }

    let typeSpeed = isDeleting ? speed / 2 : speed;

    if (!isDeleting && charIndex === currentFullText.length) {
        // Pausa no final da frase
        typeSpeed = delayEntreFrases;
        isDeleting = true;
    } else if (isDeleting && charIndex === 0) {
        isDeleting = false;
        fraseIndex = (fraseIndex + 1) % frases.length;
        typeSpeed = 500;
    }

    setTimeout(type, typeSpeed);
}


// INTERATIVIDADE COM O SCROLL:
// Só inicia a animação quando o usuário chegar na seção
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            type(); // Inicia a função de escrita
            observer.unobserve(entry.target); // Para de observar após iniciar
        }
    });
}, { threshold: 0.5 }); // 50% do elemento visível para começar

observer.observe(document.querySelector('.especialidades-container'));
document.addEventListener("DOMContentLoaded", () => {
    // 1. Lógica do Typewriter (conforme solicitado anteriormente)
    // ... (mantenha seu código de typewriter aqui)

    // 2. Lógica de Revelação ao Rolar a Página
    const boxes = document.querySelectorAll('.especialidades-box');
    
    const revealOnScroll = new IntersectionObserver((entries) => {
        entries.forEach((entry, index) => {
            if (entry.isIntersecting) {
                // Adiciona um atraso (delay) baseado no índice para criar o efeito cascata
                setTimeout(() => {
                    entry.target.style.opacity = "1";
                    entry.target.style.transform = "translateY(0)";
                }, index * 200); // 200ms entre cada card
                
                revealOnScroll.unobserve(entry.target);
            }
        });
    }, { 
        threshold: 0.2 // Começa a animar quando 20% do card aparece
    });

    boxes.forEach(box => {
        revealOnScroll.observe(box);
    });
});
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="js/main.js"></script>

</script>

    
    
</body>
</html>
