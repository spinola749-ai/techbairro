# TechBairro
A techbairro é  eum sistema de gerenciamento de clientes desenvolvido em Python com interface gráfica Tkinter e banco de dados SQLite, voltado para facilitar o controle de cadastros de pequenos estabelecimentos e projetos comunitários. 
**Versão atual:** 3.3.2 · Histórico de mudanças no [CHANGELOG](CHANGELOG.md)
## Funcionalidades
- Cadastrar, listar, editar e excluir informações de clientes com validação de e-mail e dados.
- Interface gráfica com suporte a tema escuro, busca e persistência local via banco de dados SQLite.
## Requisitos para execução
| Item | Requisito |
|---|---|
| Sistema operacional | Windows, Linux ou macOS |
| Python | 3.12.0 (versão testada: 3.3.2) |
| Tkinter | Incluído na biblioteca padrão do Python |
| Bibliotecas externas | Nenhuma (utiliza apenas a biblioteca padrão do Python) |
| Internet | Não necessária (execução 100% local) |
## Instalação
1. Clone ou baixe este repositório para o seu computador.
2. Certifique-se de que o Python 3.11 (ou superior) está instalado no sistema.
3. Abra o terminal na pasta do projeto e execute o arquivo principal com o comando python main.py (ou python3 main.py).
4. o requimerents.txt se o projeto tem dependencias e que biblioteca ele usa
## Configuração do banco de dados
O banco de dados relacional é armazenado no arquivo local techbairro.db, criado automaticamente na raiz do projeto na primeira execução da aplicação. A aplicação conecta-se diretamente a este arquivo SQLite local. O arquivo .db foi adicionado ao .gitignore e não é enviado ao repositório para proteger dados pessoais (conforme a LGPD) e evitar conflitos de versão no Git. Para fazer uma cópia de segurança (backup), basta copiar o arquivo techbairro.db para um local seguro com o aplicativo fechado. 

## Como usar
O passo a passo está no [Manual de uso](docs/manual_de_uso.md).
## Estrutura do projeto
- techbairro.py: Ponto de entrada da aplicação, responsável por inicializar a interface gráfica e carregar as rotinas do sistema.

- techbairro.db: Banco de dados SQLite local onde os registros de clientes são armazenados (gerado automaticamente).

- CHANGELOG.md: Registro histórico de versões, melhorias e correções efetuadas no projeto.

- docs/manual_de_uso.md: Documentação funcional com o passo a passo ilustrado para o usuário final.

- .gitignore: Arquivo de configuração que especifica quais arquivos e pastas (como arquivos binários .db) não devem ser versionados pelo Git.


## Autor
Gabriel Spinola dos Santos, Desenvolvimento de sistemas e Senac.