<h1>Curso: Desenvolvimento de Aplicações Modernas e Escaláveis com Microsserviços</h1>

O projeto se baseia em duas tarefas:

- [X] Você deverá pegar sua aplicação Laravel das fases anteriores e adicioná-la em um pipeline de integração contínua utilizando o Google Cloud Build, para isso terá que:

    Gerar a imagem do docker-compose e fazer o push no seu Container Registry do GCP. 
    Criar uma trigger para ser disparada todas as vezes que um commit entrar no repositório do Github.
    Os steps do Google Cloud Build deverão ser:
        Executar o docker-compose
        Executar o composer
        Copiar o arquivo .env.example para .env
        Rodar um artisan key:generate
        Executar as migrações
        Executar os testes utilizando o PHPUnit


- [X] Você deverá instalar a App do Google Cloud Build disponível no Market Place do Github. Crie um branch develop em seu repositório. Todas as vezes que uma pull request for criada, imediatamente o Google Cloud Build deverá iniciar o processo de CI.
