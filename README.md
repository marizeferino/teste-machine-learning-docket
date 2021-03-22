# Teste Machine Learning Docket

Teste realizado como parte do processo seletivo para vaga de Desenvolvedor Machine Learning Jr. na Docket.

## Requisitos

O desafio que a Docket propõe, é a extração de pelo menos o CPF de um documento CNH, através de inteligência artificial.

REQUISITOS OBRIGATÓRIOS <br>
● Através do processamento de texto e/ou imagem, extrair o número de CPF de um documento CNH; <br>
● Desenvolver o próprio dataset.

REQUISITOS OPCIONAIS (diferenciais) <br>
Extrair outras informações padrões da CNH, como por exemplo data de validade, RG e Nome.

# Planejamento

0. Como esse problema já foi resolvido anteriormente?
> Leitura de artigos e análise de repositórios no GitHub

1. Criação do dataset
> 1.1 Digitalizar e tirar foto da minha CNH <br>
> 1.2 Usar a CNH aberta ou fechada? <br>
> 1.3 Editar foto com antecedência pode ajudar a reconhecer os caracteres? <br>
> 1.4 Ocultar informações privadas da CNH e alterar número do RG e CPF <br>
> 1.5 Existe dataset público?

2. Reconhecimento Ótico de Caracteres (OCR)
> 2.1 Qual biblioteca usar? <br>
> 2.2 Como melhorar o reconhecimento?

3. Processamento do texto
> 3.1 Qual biblioteca usar? <br>
> 3.2 Extrair as informações usando REGEX ou NLP? <br>
> 3.3 Qual é o máximo de padronização e escalabilidade que consigo alcançar?

4. Teste com CNH diferente
> Encontrou CPF corretamente, não identificou o nome, extraiu dois números de RG e três datas de nascimento.  <br>
> Obs: Tirada da análise final para não expor os dados.

