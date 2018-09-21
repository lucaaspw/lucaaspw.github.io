Este é o meu primeiro projeto feito com HTML5 e CSS3.
 






/*
NAVEGAÇÂO
*/

nav > a {
    list-style-type: none;
    text-decoration: none;
    color:#f2f2f2;
    font-weight: 700;
    font-style: 30px;
    font-family: "Roboto Slab", serif;
    padding: 10px; 
    font-size: 30px;
}

nav ol {
    list-style: none;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
}

.submenu {
    width: 140px;
    background-color: #4d4d4d;
    display: none;
    position: absolute;
    border-radius: 3px;
}
.submenuitem {
    width: 140px;
    height: 30px;
    line-height: 30px;
    text-align: center;
}
.submenuitem:hover {
    background-color: #878588;
    widows: 140px;
}
nav ol li a {
    display: inline-block;
    padding: 10px 0;
    width: 100%;
    text-decoration: none;
    color:#f1f1f1;
}
.fundo {
    background-color: #77777a;
    display: inline-block;
    flex-direction: column;
    align-items: center;
    padding: 5px;
}

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
}

.sob-sobre p {
    margin-bottom: 1em;
}
/*
SOBRE
*/

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
/*
EDUCAÇÃO
*/
#educacao  {
    
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        padding: 20px;
        background-color: #878588;
        color: #000000;
    
}

#educacao >li{
    display: flex;
    flex-direction: column;
    padding: 10px ;
    text-align: center;
    position: relative;
    background-color: #f1f1f1;
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
/*
Layout criado na versão mobile, mas tornaremos a versão desktop
*/
/*
MEDIA QUERIES
*/
@media screen and (min-width: 800px) {
  
     /*
    SOBRE
    */
    #sobre {
        height: 200px;
        height: 20vh;
        justify-content: center;
        min-height: 200px;
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
    }
    .mudar {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around;
        margin: 0 auto;
     
    }
}