Este é o meu primeiro projeto feito com HTML5 e CSS3.



index.html

 <section id="sobre">
                <h1>Sobre mim</h1>
                <p> Cresci em uma cidadezinha no interior de MG, sem recursos e sem faculdade,
                    me mudei para São Paulo (SP), para mudar minha vida, conheci a programação,
                    amei, e é isso que eu quero para minha vida agora.
                </p>
                        <a href="#contato" class="botao">Entre em contato</a>
            </section>
            <section id="educacao">
                   <h2> Educação</h2>
                    <ol>
                        <h3>PHP do zero ao profissional-B7Web</h3>
                        <p>O curso fornece diversas linguagens, mas essas são as que eu me identifico
                            mais.
                        </p>
                        <li class="fundo">Bootstrap v4</li>
                        <li class="fundo">HTML e HTML5</li>
                        <li class="fundo">CSS e CSS3</li>
                        <li class="fundo">JavaScript</li>
                        <li class="fundo">jQuery</li>
                        </ol>

            </section>
            
               
            <section id="contato" >
                <h2 class="lks">Contato</h2>
                <div>

                    <img src="imagens/auricular-phone-symbol-in-a-circle.png" alt="telefone">
                    <p class="mudar"><a href="tel:11942021791">(11) 94202-1791</a></p>
                    
                </div>
                <div>

                        <img src="imagens/whatsapp.png" alt="whatsapp">
                        <p class="mudar"><a href="tel:11942021791">Whatsapp</a></p>
                        
                    </div>
                    <div>

                            <img src="imagens/gmail.png" alt="gmail">
                            <p class="mudar"><a href="https://mail.google.com/mail/u/0/?tab=mm#inbox">Gmail</a></p>
                            
                        </div>
                        
                        <div>

                                <img src="imagens/twitter.png" alt="twitter">
                                <p class="mudar"><a href="https://twitter.com/lucaaspw">Twitter</a></p>
                                
                            </div>
                            <div>

                                    <img src="imagens/github-sign.png" alt="github">
                                    <p class="mudar"><a href="https://github.com/lucaaspw">GitHub</a></p>
                                    
                                </div>
                                <div>

                                        <img src="imagens/linkedin.png" alt="linkedin">
                                        <p class="mudar"><a href="https://www.linkedin.com/in/lukas-gon%C3%A7alves-9b3802166/">Linkedin</a></p>
                                        
                                    </div>
                                    <div>

                                            <img src="imagens/instagram.png" alt="instagram">
                                            <p class="mudar"><a href="https://www.instagram.com/_lugoncalves_/">@lugoncalves</a></p>
                                            
                                        </div>
            </section>
            <footer>
                <h4>Desenvolvido por Lucas Gonçalves</h4>
            </footer>







/*estilo.css*/



/*
CABEÇALHO
*/

.sob-sobre {
    background-color: #000000;
    color: #f2f2f2;
    display: flex;
    flex-direction: column;
    align-items: center; 
    text-align: center;
    padding: 30px;
    margin-top: 10px;
}

.sob-sobre p {
    margin-bottom: 1em;
}

#sobre {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 20px;
    color: #f1f1f1;
    background-color: rgb(2, 0, 0);
   
}

#sobre p{
    margin-bottom: 2.5em;
    max-width: 1000px;
}
.botao {
    color: #000000;
    text-decoration: none;
    padding: 8px 17px;
    background-color: #ffffff;
    border-radius: 5px;
    font-size: .9em;
}
nav ol {
    list-style: none;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
}

nav ol li a {
    display: inline-block;
    padding: 10px 0;
    width: 100%;
    text-decoration: none;
    color:#f1f1f1;
}

/*
EDUCAÇÃO
*/

#educacao {
    
     display: flex;
     flex-direction: column;
     align-items: center;
     text-align: center;
     padding: 20px;
     background: #878588;
     color: #000000;
       
}

#educacao >ol li{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 10px ;
    text-align: center;
    position: relative;
    background: #878588;
    text-decoration: none;
    float: left;
}

/*
CONTATO
*/
#contato {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 20px;  
    background-color: #323233;
    color: #f1f1f1;
}
.lks {
    margin-bottom: 10px;
    font-size: 32px;

}
#contato a {
    text-decoration: none;
    text-align: center;
    margin-top: 10px; 
    color: #f1f1f1;
}

.mudar {
    text-align: initial;
    position: initial;
    
}

/*
FOOTER
*/
footer{
    text-align: center;
    padding: 5px;
    background-color: #4d4d4d;
    color: #f1f1f1;

}

@media screen and (min-width: 1000px) {
  
    /*
   SOBRE
   */
   #sobre {
       height: 200px;
       height: 20vh;
       justify-content: center;
       min-height: 300px;
   }
     /*
    CONTATO
   */
   #contato  {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around;
        margin: 0 auto;
     
   }
   #contato h2,
   #contato p {
       width: 100%;
       padding: 20px;
       margin-top: 0;
   }
   .mudar {
       flex-direction: row;
       flex-wrap: wrap;
       justify-content: space-around;
       margin: 0 auto;
    
   }
}

@media screen and (min-width: 800px) {
  
    /*
   SOBRE
   */
   #sobre {
       height: 200px;
       height: 20vh;
       justify-content: center;
       min-height: 300px;
   }
     /*
    CONTATO
   */
   #contato  {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around;
        margin: 0 auto;
     
   }
   #contato h2,
   #contato p {
       width: 100%;
       padding: 20px;
       margin-top: 0;
   }
   .mudar {
       flex-direction: row;
       flex-wrap: wrap;
       justify-content: space-around;
       margin: 0 auto;
    
   }
}
