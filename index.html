<!DOCTYPE html>
<html lang="pt-BR">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>System Failure</title>

<style>

*{
    box-sizing:border-box;
}

body{
    margin:0;
    height:100vh;
    background:black;
    color:#00ff00;
    font-family:"Courier New", monospace;
    overflow:hidden;
}


/* chuva de código */

canvas{
    position:absolute;
    top:0;
    left:0;
    z-index:-1;
}


/* terminal */

#terminal{

    padding:25px;
    font-size:18px;

}


.alerta{

    display:none;
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;

    background:rgba(120,0,0,.85);

    color:white;

    justify-content:center;
    align-items:center;
    flex-direction:column;

    text-align:center;

}


h1{

    font-size:45px;
    color:red;
    animation:pisca .3s infinite;

}


button{

    margin-top:30px;

    padding:18px 35px;

    background:#900;
    color:white;

    border:2px solid white;

    font-size:20px;

    cursor:pointer;

}


button:hover{

    background:red;

}



@keyframes pisca{

    50%{
        opacity:.2;
    }

}



.treme{

animation:tremer .08s infinite;

}


@keyframes tremer{

0%{transform:translate(2px,2px);}
50%{transform:translate(-2px,-2px);}
100%{transform:translate(2px,-2px);}

}



</style>

</head>


<body>
<audio id="teclado" loop>
    <source src="digitacao.mp3" type="audio/mpeg">
</audio>

<audio id="alarme">
    <source src="alarme.mp3" type="audio/mpeg">
</audio>

<canvas id="matrix"></canvas>


<div id="terminal">

> Inicializando núcleo...<br>
> Conectando servidor desconhecido...<br>
> Carregando protocolo ████████ 100%<br><br>

<span id="texto"></span>

</div>



<div class="alerta" id="alerta">

<h1>⚠ SISTEMA INVADIDO ⚠</h1>

<h2>ANOMALIA DETECTADA</h2>

<p id="contador">
Verificando ambiente...
</p>

<button onclick="remover()">
REMOVER AMEAÇA
</button>


</div>




<script>


// MATRIX

let canvas=document.getElementById("matrix");

let ctx=canvas.getContext("2d");

canvas.height=window.innerHeight;
canvas.width=window.innerWidth;


let letras="0101010101ABCDEFGHIJKLMNOPQRSTUVWXYZ";

let tamanho=16;

let colunas=canvas.width/tamanho;

let gotas=[];


for(let i=0;i<colunas;i++){

gotas[i]=1;

}


function matrix(){

ctx.fillStyle="rgba(0,0,0,.08)";
ctx.fillRect(0,0,canvas.width,canvas.height);


ctx.fillStyle="#00ff00";

ctx.font=tamanho+"px monospace";


for(let i=0;i<gotas.length;i++){

let texto=letras[Math.floor(Math.random()*letras.length)];


ctx.fillText(texto,i*tamanho,gotas[i]*tamanho);


if(gotas[i]*tamanho>canvas.height && Math.random()>0.97){

gotas[i]=0;

}


gotas[i]++;

}


}


setInterval(matrix,50);




// TERMINAL

let mensagens=[

"Executando varredura...",
"Encontrando atividade desconhecida...",
"Processando dados criptografados...",
"Falha no protocolo de segurança...",
"Presença detectada...",
"Preparando alerta..."

];


let i=0;


function escrever(){

document.getElementById("teclado").play();

if(i<mensagens.length){


document.getElementById("texto").innerHTML +=
"<br>"+mensagens[i];


i++;

setTimeout(escrever,1200);


}

else{


setTimeout(()=>{


document.getElementById("alerta").style.display="flex";

document.getElementById("teclado").pause();

document.getElementById("alarme").play();

document.body.classList.add("treme");

let n=10;


let intervalo=setInterval(()=>{


document.getElementById("contador").innerHTML=
"Tempo restante: "+n+"s";


n--;


if(n<0){

clearInterval(intervalo);


// ação quando o tempo acaba

document.querySelector(".alerta").innerHTML=

`

<h1 style="color:red">
⚠ ACESSO PERDIDO ⚠
</h1>

<h2>
Seus dados foram comprometidos!
</h2>

<p>
Conexão encerrada pelo sistema.
</p>

`;

}


},1000);



},1500);



}



}


setTimeout(escrever,1500);





function remover(){


document.querySelector(".alerta").innerHTML=

`

<h1 style="color:#00ff00">
ACESSO CANCELADO
</h1>

<h2>
Sistema estabilizado.
</h2>

<p>
Nenhuma ação real foi executada.
</p>

`;


document.body.classList.remove("treme");


}


</script>


</body>
</html>
