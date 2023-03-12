### Muito prazer, eu sou a Gabi ✌️
##### Me siga nas redes sociais :)

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielli-katherin/) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_gabcat_/)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=GabiiKatherin&layout=compact)](https://github.com/gabiikatherin/github-readme-stats)

### Tecnologias que aprendo no meu dia a dia:

<div style="display: inline_block"><br/>
    <img align="center" alt="SGBD" src="https://img.shields.io/badge/-SGBD-red" />
    
    SELECT nom_materia, nom_conteudo, count(distinct c.cod_conteudo) as qtd_topicos_estudados, count(distinct r.cod_conteudo) as qtd_topicos_revisados
    FROM _Materia m
    INNER JOIN _Conteudos c on c.cod_materia = m.cod_materia
    LEFT JOIN _Estudados e on e.cod_conteudo = c.cod_conteudo 
    LEFT JOIN _Revisado r on r.cod_conteudo = e.cod_conteudo  AND CAST(r.data_revisao AS DATE) >= CAST(e.data_estudo AS DATE)
    WHERE CAST(s.EventDate AS DATE) >= CAST(GETDATE()-7 AS DATE)
    GROUP BY nom_materia, nom_conteudo, count(distinct c.cod_conteudo) as qtd_topicos_estudados, count(distinct r.cod_conteudo) as qtd_topicos_revisados
    ORDER BY count(distinct c.cod_conteudo) ASC

</div>

<div style="display: inline_block"><br/>
    <img align="center" alt="FRONTEND" src="https://img.shields.io/badge/-FRONTEND-green" />

    <!DOCTYPE html>
     <html>
      <head>

       <title> Olá mundo, sejam bem vindos! ;) </title>

      </head>
     <body>

       <h1> Vejam minha página pessoal!
       <p> <a href="https://github.com/GabiiKatherin/pagina_pessoal"> Acesse meu repositorio</a> </p>

      </body>
     </html>

<div style="display: inline_block"><br/>
    <img align="center" alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

    EM BREVE!

</div>
         

</div>

<div style="display: inline_block"><br/>
    <img align="center" alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />

    public class Main {
    public static void main(String[] args) throws Exception {
        System.out.println("Olá, mundo, sejam bem vindos!");

        //Ainda estou aprendendo, mas vejam meu projeto em Java! ;)
        Projeto Xadrez = new Xadez();
      }
    }
</div>


