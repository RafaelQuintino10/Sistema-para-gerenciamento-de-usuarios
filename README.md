README: Sistema de Cadastro e Gerenciamento de Alimentos

Este é um sistema simples de cadastro e gerenciamento de usuários e alimentos desenvolvido em Python usando a biblioteca customtkinter para criar a interface gráfica. O sistema permite cadastrar usuários e alimentos, listar os dados cadastrados e calcular a divisão de alimentos entre os usuários.

Funcionalidades

1 - Cadastro de Usuários: Permite o cadastro de usuários, incluindo nome e idade. Os dados são armazenados em um arquivo CSV.

2 - Cadastro de Alimentos: Permite o cadastro de alimentos, incluindo o nome do alimento e a quantidade. Os dados são armazenados em um arquivo CSV.
3 - Listagem de Usuários: Exibe a lista de usuários cadastrados em uma tabela.
4 - Listagem de Alimentos: Exibe a lista de alimentos cadastrados em uma tabela.
5 - Cálculo de Divisão de Alimentos: Calcula e exibe a quantidade de alimentos que cada usuário deve receber, com base na quantidade total de alimentos cadastrados e no número de usuários.



Dependências

Python 3.x
customtkinter
csv (embutido no Python)
os (embutido no Python)
tkinter (embutido no Python)

Estrutura dos Arquivos CSV

usuarios.csv: Armazena os dados dos usuários com as colunas Nome e Idade.
alimentos.csv: Armazena os dados dos alimentos com as colunas Alimento e Quantidade.



Como Usar

1 - Executar o Programa: Execute o arquivo Python para iniciar o aplicativo.

	prototipo.py


2 - Tela Principal: A tela principal oferece botões para acessar as diferentes funcionalidades do sistema:

   Cadastrar Usuário: Abre a tela para cadastrar um novo usuário.
   
   Listar Usuários: Exibe a lista de usuários cadastrados.
   
   Cadastrar Alimentos: Abre a tela para cadastrar novos alimentos.
   
   Listar Alimentos: Exibe a lista de alimentos cadastrados.
   
   Calcular Divisão: Calcula e exibe a divisão dos alimentos entre os usuários.


![interface_usuarios](https://github.com/user-attachments/assets/0cafad4d-a944-4e8b-91f2-3e66cd3b56c2)


3 - Cadastro de Usuários:

   Insira o nome e a idade do usuário;
   Clique em "Cadastrar usuário" para salvar as informações.

   ![telacadastro](https://github.com/user-attachments/assets/c3c62789-ffb2-46ec-9ea8-2baee3e3bf3f)

   
   
4 - Cadastro de Alimentos:

   Insira o nome do alimento e a quantidade.
   Clique em "Cadastrar alimento" para salvar as informações.

   ![cadastro-alimentos](https://github.com/user-attachments/assets/f9bc7698-19e8-49f3-944e-39a11cc27e2a)

   
   
5 - Listagem de Usuários e Alimentos:

   Acesse as respectivas telas para visualizar os dados cadastrados em formato de tabela.


   ![lista-usuarios](https://github.com/user-attachments/assets/c098d312-5c0d-41f0-9c17-99e6090e01fe)
   ![lista-alimentos](https://github.com/user-attachments/assets/6bf5f73a-f417-4d69-9c5f-3e4ac9d576ef)

   
   
6 - Cálculo de Divisão de Alimentos:

   Clique em "Calcular divisão" para calcular a quantidade de alimentos que cada usuário deve receber.


   ![divisao](https://github.com/user-attachments/assets/458f54bd-b222-4033-b32f-969cd9bd8042)

    
   
Exemplo de Arquivo CSV
usuarios.csv

	csv
	Copiar código
	Nome,Idade
	João,30
	Maria,25
	Pedro,40
	alimentos.csv

	csv
	Copiar código
	Alimento,Quantidade
	Arroz,10
	Feijão,5
	Macarrão,8
 
Notas


As telas são gerenciadas usando o método grid do customtkinter.
O sistema atualiza as listas de usuários e alimentos dinamicamente sempre que um novo item é adicionado.
A tela de cálculo verifica se há usuários cadastrados antes de realizar a divisão dos alimentos.
Contribuição
Se você deseja contribuir com o projeto, sinta-se à vontade para enviar um pull request com melhorias ou correções.

Licença
Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.



