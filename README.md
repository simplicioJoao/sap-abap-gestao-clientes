# SAP ABAP – Module Pool para Gestão de Clientes

O programa desenvolvido neste repositório trata-se de um pool de módulos para gerenciamento de clientes, com registros armazenados em uma tabela criada no Dicionário de Dados (DDIC), e que tem como funções possíveis a inserção, atualização, exclusão e consulta nessa tabela. Foi desenvolvido um CRUD completo para colocar em prática os conceitos aprendidos sobre programação ABAP, banco de dados no SAP e programação de eventos de tela criada através do ScreenPainter no SAP GUI.

Os arquivos do programa encontram-se na pasta `src/`, acompanhados do arquivo de metadados (.xml) gerado pelo abapGit, que contém as informações presentes nos módulos `PAI` e `PBO`, além dos `INCLUDE_TOP` e `INCLUDE__FORM`.

---

## Z944620GESTAO_CLIENTES
A seguir encontram-se imagens do resultado obtido com o desenvolvimento do programa e a posterior criação de uma transação para acesso facilitado aos usuários do SAP ERP.
Pode-se observar que, apesar de o layout ser único, o design muda em poucos detalhes de acordo com o tema configurado pelo usuário logado.

<div align="center">
<img src="https://github.com/simplicioJoao/sap-abap-gestao-clientes/blob/main/transaction-sap-signature-theme.png" alt="Resultado no tema SAP Signature Theme" width="400" />
<img src="https://github.com/simplicioJoao/sap-abap-gestao-clientes/blob/main/transaction-sap-quartz-dark-theme.png" alt="Resultado no tema Quartz Dark Theme" width="400" />
</div>

---

## 🛠 Requisitos

- SAP ERP com suporte a ABAP 7.4+  
- Autorização para usar SE38/SE80  
- Permissão para leitura nas tabelas Z utilizadas  
- Opcional: acesso ao abapGit para importação automatizada  

---

## 🚀 Como executar

1. Importe o repositório via abapGit ou copie cada programa via SE38.  
2. Ative o objeto (`Ctrl + F3`).  
3. Execute via SE38 / SE80.  
4. Preencha os parâmetros de seleção (quando houver).  
5. Execute o relatório.  

---

## 📄 Licença

Projeto disponibilizado para fins educacionais.  
Autor: **João Paulo Simplicio**
