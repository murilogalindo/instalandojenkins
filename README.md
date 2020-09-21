# instalandojenkins

## não está completo (apenas o básico)

#E acesse https://www.jenkins.io/
- Clicar em download;
- Escollher a plataforma de sua preferencia;
- Seguir as instruções de instalação: https://pkg.jenkins.io/debian-stable/
- Adicionar a chave para o repositório;
- Adicionar o repositório do Jenkins no Mint;
- Rodar o comendo de atualização de repositório (apt-get update);
- Rodar o comando para instalar o Jenkins (apt-get install jenkins);
- Abrir o Jenkins utilizando o endereço padrão http://localhost:8080;
- Aguardar o Jenkins inicializar;
- Destravar o Jenkins obtendo a chave de acesso inicial;
- Selecionar os plugins padrões para instalação;
- Criar um usuário admin;
- Finalizar a instalação do Jenkins no Linux Ubuntu

## No Jenkins 
- Click no link Novo Job
- Enter an item name
- Escolha a forma que quer construir o projeto ex: Construir um projeto de software free-style
- Em Gerenciamento de código fonte
- Em Repository URL insira a URL do git (do projeto)
- Em construir periodicamente: H 0,12 * * 0-6 (executar 2x por dia)
- Salve as aterações
- Na tela inicial do Jenkins onde fica os projetos (Jobs)
- Click na seta no Job e escolhar Construir Agora
- Veja a execução no Histórico de builds 



