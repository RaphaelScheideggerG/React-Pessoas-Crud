# Crud de pessoas com React
## Funcionalidades exploradas no projeto

###**PF: Data de nascimento**
- Implementado na classe (PF.mjs) com setters/getters coerentes.
- Campo no formulário PFForm.jsx com DatePicker. 
- atribuição de data de nascimento ao objeto pessoa utilizando os valores do formulário (linha 36 em PessoaForm)
- Persistência via DAO (chamando método em PessoaForm.jsx).

###**PJ: Data de registro da IE**
- Inscrição Estadual Implementada na classe (PJ.mjs) com setters/getters coerentes.
- Formulário PJForm.jsx com campos “Inscrição Estadual”, “Estado” e “Data de Registro”.
- instanciando IE e depois usando método setIE de pessoa para depois armazenar PJ com o DAO (linha 41:45 em PessoaForm.jsx)
- Persistência via DAO (chamando método de salvar em PessoaForm.jsx linha 62)

## Como executar
- Clone o repositório
- Instale as dependências: `npm install`
- Rode o projeto: `npm run dev`
