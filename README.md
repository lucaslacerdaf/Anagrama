# Anagrama
Projeto acadêmico do 1º Semestre: Jogo de Anagrama  

Exemplo tirado do site Racha Cuca: https://rachacuca.com.br/palavras/anagramas/

    No exemplo foram utilizadas as variáveis:
char letras []= {'O','N','C','C','E','N','M','T','H','O','E','I'};
char palavra [13];
char BancoPalavras [20][13] = {"CONHECIMENTO","CIMENTO","CINTO","NETO","OI","MENTE","CONTO"};
char BancoAcertos [20][13];

    Descrição:

Conjunto de letras (partir de uma palavra com mais de 5 letras embaralhadas) – sugestão: utilizar um vetor de caracteres contendo as letras;
Banco de Palavras possíveis, formadas pelas letras do conjunto (pelo menos 10 palavras) – sugestão: utilizar um VETOR de STRING;
Sugestão: utilizar outro Vetor de String: Banco de Acertos, para registrar as palavras já encontradas. Livre para escolherem outra forma de controlar os acertos.
 
    INÍCIO:

- uma palavra é digitada:

Verificar se a palavra digitada pertence ao Banco de Palavras:
Se sim, verificar no Vetor de String: Acertos, se a palavra já foi digitada:
Se sim, ignorá-la e ir para nova leitura de palavra;
Se não, incluí-la em Acertos e ir para nova leitura;
Se não, ignorá-la e ir para nova leitura de palavras.
 
    Observações:

-manter sempre visíveis: AS LETRAS e os Acertos;

- a divisão do programa em módulos, fica a cargo de cada equipe.

    Avaliação:

deverá executar corretamente;
deverá atender o que se pede;
deverá ter uma boa apresentação;
as notas serão atribuídas comparativamente, com a apresentação do melhor para o pior. Programas com apresentações inéditas/únicas, receberão maior nota;
receberão nota zero todos os programas (entre alunos) com partes semelhantes, demostrando cópias;
receberão nota zero os programas que contenham, mesmo que apenas um pequeno trecho, copiados de fontes externas – livros, internet;
na identificação de recursos da linguagem que extrapolem os assuntos desenvolvidos no curso, os alunos poderão ser arguidos para explicações deles. Caso não expliquem os recursos utilizados, os trabalhos receberão nota zero;
não serão aceitos trabalhos que façam uso de variáveis globais e/ou comando de desvio- goto;
em caso de dúvida, procurem os monitores ou o professor!!!

