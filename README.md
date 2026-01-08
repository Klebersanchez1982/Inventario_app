Inventário de Produtos

Este projeto é um sistema simples de controle de inventário com leitura de código de barras. Ele foi desenvolvido para facilitar o registro, controle e atualização de produtos em estoque. A principal funcionalidade é a leitura do código de barras, que preenche automaticamente as informações do produto, permitindo que o usuário apenas insira a quantidade.

Funcionalidades

Leitura de código de barras: O sistema preenche automaticamente as informações do produto (descrição, modelo, cor, tamanho) ao escanear o código de barras.

Controle de quantidade: O usuário pode ajustar a quantidade dos itens no estoque.

Verificação de duplicidade: Se o código de barras for repetido, a linha do produto será pintada de vermelho para facilitar a identificação.

Salvamento rápido: O sistema permite que as informações sejam salvas de forma eficiente, sem bloquear a interface do usuário, permitindo que o próximo item seja adicionado imediatamente.

Busca por nome ou código: Permite buscar facilmente um produto no inventário, seja pelo código de barras ou pela descrição.

Tecnologias Usadas

Frontend:

HTML

CSS

JavaScript

Backend:

Google Apps Script

Banco de Dados:

Google Sheets (para armazenar os dados de inventário)




Como Usar
1. Preparação

Clone o repositório para o seu computador:

git clone https://github.com/username/inventory-system.git


Abra a planilha Google Sheets e crie a aba "CADASTRO_PRODUTOS" com as colunas:

CODIGO_BARRAS

DESCRICAO

MODELO

COR

TAMANHO

QUANTIDADE

2. Configuração do Google Apps Script

Abra o Google Apps Script vinculado à planilha.

Copie o código do Apps Script e cole no seu projeto do Apps Script.

Implemente as funções de leitura, escrita e controle de duplicidade conforme descrito no código.

3. Deploy do Sistema

O sistema pode ser hospedado em qualquer servidor estático, como o Netlify ou GitHub Pages.

Faça o deploy da pasta contendo o index.html e as configurações de estilo e script.

4. Usando o Sistema

Abra o aplicativo em seu navegador.

Ao escanear um código de barras, os dados do produto são automaticamente preenchidos.

Insira a quantidade no campo correspondente.

O sistema automaticamente marcará em vermelho qualquer código de barras repetido.

Contribuição

Faça um fork do repositório.

Crie uma branch (git checkout -b minha-nova-funcionalidade).

Faça suas alterações.

Envie as alterações para o repositório original com um pull request.

Licença

Este projeto é de uso livre. Sinta-se à vontade para usá-lo, adaptá-lo e distribuí-lo conforme necessário.

💬 Feedback

Se você tiver sugestões ou encontrou algum bug, sinta-se à vontade para abrir uma issue ou enviar um pull request.