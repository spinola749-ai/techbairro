# Registro de testes da TechBairro

Versão testada: 3.3.2 · Data: 27/10/2026 · Responsável: Gabriel Spinola dos Santos
Sistema operacional e versão do Python: Windows, versão do python 3.12.0


| ID | Requisito | Passos e dados | Esperado | Obtido | Status |
|---|---|---|---|---|---|
| CT01 | RF01 | Cadastrar um cliente com todos os campos certos | Cliente cadastrado | Cliente cadastrado | Clinte cadastrado:1 |
| CT02 | RF01 | Salvar com Nome e Endereço vazios | Seja cadastrado | Preencha os campos que estão faltando | Clinte cadastrado:1 |
| CT03 | RF02 | Telefone 61 9999 0000 (com espaços) | Cadastrar o cliente | Cliente não cadastrado | Clinte cadastrado:1 |
| CT04 | RF03 | E-mail ana@email (sem ponto) | Cadastrar o cliente | Precisa seguir a regra | Clinte cadastrado:1 |
| CT05 | RF05 | Editar um cliente, trocar o telefone e salvar | Cliente cadastrado | cliente cadastrado com sucesso | Clinte cadastrado: 2 |
| CT06 | RF06 | Excluir um cliente: responder Não, depois Sim | Não conseguir excluir e depois excluir | Feita com sucesso | Clinte cadastrado: 1 |
## Testes automáticos
Saída do `python testar_validacao.py`: 
OK teste_cliente_valido
OK teste_endereco_vazio
OK teste_telefone_com_letras
OK teste_email_sem_ponto
OK teste_nome_e_telefone_vazios
OK teste_email_sem_usuario
Todos os testes passaram.



## Defeitos encontrados
nenhum 