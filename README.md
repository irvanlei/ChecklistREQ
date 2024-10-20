# Aplicação de Checklist para Engenharia de Requisitos (REQ)

Esta é uma aplicação web que permite realizar um checklist de conformidade para Engenharia de Requisitos (REQ) seguindo as diretrizes do MPS.BR. A aplicação coleta respostas para cada pergunta e gera uma classificação com ações corretivas para os itens não conformes, além de exibir indicadores e um gráfico de aderência.

## Funcionalidades

- **Formulário Dinâmico:** Um checklist com perguntas específicas sobre Engenharia de Requisitos.
- **Classificação e Ações Corretivas:** Exibe uma classificação detalhada e ações corretivas para cada pergunta respondida com "Não".
- **Indicadores:** Exibe indicadores de conformidade, como número total de perguntas, perguntas aplicáveis, respostas "Sim" e "Não", e a porcentagem de aderência.
- **Gráfico de Aderência:** Um gráfico de pizza que visualiza a proporção de respostas "Sim" e "Não".
- **Nova Consulta:** Um botão para iniciar um novo checklist, limpando os dados anteriores.

## Tecnologias Utilizadas

- **HTML5:** Estruturação e apresentação das páginas.
- **CSS3:** Estilização e layout.
- **JavaScript (ES6+):** Manipulação dos dados, lógica do checklist e interatividade.
- **Chart.js:** Biblioteca para visualização de gráficos de pizza.
- **LocalStorage:** Armazenamento temporário dos dados do formulário para persistência entre páginas.

## Estrutura da Aplicação

- **index.html:** Página principal que contém o checklist com perguntas para Engenharia de Requisitos.
- **classificacao.html:** Página de classificação que exibe os resultados do checklist, incluindo ações corretivas, indicadores e gráfico de aderência.

## Como Usar

1. Clone este repositório para o seu ambiente local:
2. Navegue até o diretório do projeto
3. Abra o arquivo index.html em seu navegador para acessar o checklist.
4. Preencha o checklist com as respostas ("Sim", "Não" ou "Não se aplica") e clique em "Enviar".
5. Após o envio, você será redirecionado para a página de classificação (classificacao.html), onde poderá visualizar:
    - Perguntas respondidas com "Não" e suas respectivas ações corretivas.
    - Indicadores de conformidade.
    - Um gráfico de pizza mostrando a proporção de respostas "Sim" e "Não".
6. Para iniciar uma nova consulta, clique no botão "Nova consulta". Isso limpará os dados e redirecionará para o checklist inicial.

## Customização

Você pode personalizar as perguntas e as ações corretivas diretamente no arquivo index.html. As classificações, tempos estimados e ações corretivas são definidos em um objeto JavaScript para fácil manutenção.

## Contribuição
Sinta-se à vontade para contribuir com melhorias, sugestões ou reportar problemas. Para isso:

 - Faça um fork do projeto.
 - Crie uma nova branch com sua funcionalidade: 
    ```bash
     git checkout -b minha-nova-funcionalidade.
 - Faça commit de suas mudanças: 
    ```bash
     git commit -m 'Adicionando uma nova funcionalidade'.
 - Envie para a branch principal: 
    ```bash
     git push origin minha-nova-funcionalidade.
 - Abra um Pull Request.

##
Desenvolvido por Irvanlei de Abreu.
