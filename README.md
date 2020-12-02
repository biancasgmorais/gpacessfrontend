# GPACESS (Frontend)
* Sistema da Aplicação GPACESS desenvolvida como Trabalho de Conclusão de Curso afim de obter o titulo de bacharel em Engenharia de Computação na Universidade Federal Rural do Semi-Árido (UFERSA) no campus Pau dos Ferros;
* Orientado pela Profa. Dra. Verônica Maria Lima Silva.

# Linguagem Utilizada
* React.js

# Resumo do Sistema
Esse sistema foi desenvolvido para obter dados com controle de acesso a ambientes, neste caso o laboratório do Grupo de Pesquisa em Sistemas Críticos de Segurança (GPSiCS). O controle é gerenciado pelo sistema Web, onde é possivel listar dados de acesso de uso (tag, nome do usuário associado a tag, hora, data), assim que o usuário acessar a sala com a tag do sistema de hardware feito com a antena RFID, Arduino e NodeMCUESP8266. Também é possivel associar uma tag a um usuário com o cadastro de tags. Nesse sistema é possivel editar, excluir, listar, adicionar dados de usuários. Apenas usuários administradores, previamente cadastrados no banco, podem utilizar o sistema.

# Descrição
* A validação de dados é feita por protocolo Yup
* Só usuários administradores podem logar
* Usuários podem se cadastrar apenas para obter a liberação do seu acesso ao ambiente solicitado.

# Rodando o projeto
* É necessário ter o postgres;
* O gerenciador de pacotes Yarn deve estar instalado e habilitado;
* Para a instação dos pacotes necessários, na pasta onde o arquivo foi baixado, pelo prompt de comando usar o comando: yarn install
* Para a instação dos pacotes necessários, usar o comando: yarn
* Para rodar o código do frontend em modo desenvolvedor, usar o comando: yarn start
