# Manual do Launcher Web Boberto

### PORTUGUÊS

Nesse arquivo, você aprenderá os conceitos básicos de como a parte web do launcher boberto funciona e uma breve explicação sobre cada implementação importante


1. Clone o projeto https://github.com/brutalzinn/boberto-launcher-web
2. Altere o nome de .env.example para .env
3. Configure a variável de ambiente com suas configurações. Não se preocupe com senhas de banco ou coisas desse tipo. O docker baixará todos os serviços que o projeto precisa pra rodar. Então, apenas se preocupe em configurar o arquivo .env com seus dados.
4. Execute o comando docker-compose up
5. Acesse http://127.0.0.1/teste.php no navegador
6. Veja se recebeu um OK
7. Teste a api http://127.0.0.1:5000 com a ferramenta postman. A coleção está disponível nesse mesmo repositório. Essa api será usada pelo gerenciador de modpacks.
8. Baixe algum cliente para o Redis e verifique se ele está funcionando corretamente.
9. Abra o launcher e verifique se ele está respondendo.
