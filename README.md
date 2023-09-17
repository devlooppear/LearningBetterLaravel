# LearningBetterLaravel
Este é um projeto de gerenciamento de eventos desenvolvido em Laravel, projetado para ajudar na organização e administração de eventos, como palestras, conferências e workshops. O intuito principal foi entender mais sobre os comandos fundamentais do Laravel. Apesar deu ter realizado sua confecção este projeto foi idealizado em uma aula d desenvolvedor Matheus Battisti. Caso queiram acessar para também treinar o fundamental de Laravel: https://www.youtube.com/watch?v=qH7rsZBENJo.

## Requisitos
Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

- PHP >= 8.1
- Composer
- Laravel CLI
- Banco de dados (por exemplo, MySQL)
- Instalação

Se quiserem clonar o repositório:

```
git clone https://github.com/devlooppear/LearningBetterLaravel.git
```

Instale as dependências do Composer:

```
composer install
```

Se não der certo, dá um:

```
composer update
```

depois dá o `composer install`

- Copie o arquivo de configuração do ambiente e configure suas variáveis de ambiente:

```
cp .env.example .env
```

Certifique-se de configurar seu banco de dados no arquivo .env., tipo, recomendo botar no de db `test` do MySQL antes de implementar algo para ver direitinho como tá estruturado o DB.

Gere uma chave de aplicativo:

```
php artisan key:generate
```

- Execute as migrações do banco de dados para criar as tabelas necessárias:

```
php artisan migrate
```

Inicie o servidor de desenvolvimento:

```
php artisan serve
```

O aplicativo estará disponível em http://localhost:8000 por definição. Tenta ver se a porta não tá sendo usada.

Se quiser ver se as migrations deram certo dá um:

```
php artisan migrate:status
```

### Uso

Acesse o aplicativo em seu navegador e comece a gerenciar seus eventos. Você pode criar, visualizar, editar e excluir eventos conforme necessário.

## Mais algumas considerações:

Se quiserem complementar ou ajuda com, só chamar, tem minhas redes aqui no GitHub. Se você estiver usando uns PHP mais antigos, ou atualiza ou usa uma imagem de versão mais atual com docker, ou então vai no `composer.json` e tenta mudar pra uma compatível com a sua versão do php. Belezinha? Recomendo o canal Hora de Codar, muito daora.