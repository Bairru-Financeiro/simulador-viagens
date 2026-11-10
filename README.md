# Simulador de Viagens – BairrU

Simulador de custos de viagens corporativas, com base na Política de Viagens Corporativas e na Política de Reembolso e Transferência da BairrU.
O gestor usa o simulador para montar o orçamento de viagens da área e exportá-lo para Excel.

**Link do simulador:** https://bairru-financeiro.github.io/simulador-viagens/

## Como usar

1. Abra o link acima no Chrome ou no Edge. Também dá para baixar o `index.html` e abrir direto no computador: o arquivo é independente, não instala nada, não precisa de login e funciona sem internet.
2. Preencha os campos obrigatórios (*). Campo obrigatório vazio fica em amarelo.
3. Escolha a **Área / Centro de Custo** e o **Projeto** e clique em **+ Adicionar viagem ao orçamento**. Repita para cada viagem prevista.
4. Clique em **Baixar Excel**. O arquivo vai para a pasta **Downloads** do usuário (a pasta padrão de downloads do navegador). O Excel tem 4 abas:
   - **Orçamento por mês:** Área > Projeto > Categoria > Abertura × meses.
   - **Base de dados:** uma linha por viagem × abertura × mês, pronta para Tabela Dinâmica.
   - **Viagens:** as viagens previstas.
   - **Critérios:** os valores da política usados no cálculo.

A lista de viagens fica salva só no navegador de quem está usando. Baixe o Excel ao terminar.

## Como atualizar

O simulador é gerado na pasta da Controladoria no Google Drive (`Projeto Cibele/Viagens BairrU (novo)`), onde fica o script `atualizar_simulador.bat`, que lê as políticas.
Depois de atualizar lá, copie `Simulador_Viagens_BairrU.html` para este repositório com o nome `index.html` e faça o commit. O link é atualizado em cerca de 1 minuto.

> Repositório público: qualquer pessoa com o link pode abrir o simulador. Não inclua aqui dados pessoais ou confidenciais.
