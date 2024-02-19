# Laravel CRUD App (Em Construção)

Este é um aplicativo CRUD (Create, Read, Update, Delete) em construção desenvolvido com Laravel, um framework PHP popular para construção de aplicações web.

## Requisitos

- PHP >= 7.4
- Composer
- MySQL ou outro banco de dados suportado pelo Laravel

## Instalação

1. Clone este repositório para sua máquina local:

```
git clone https://github.com/indiamaraeenes/laravel-crud-app.git
```

2. Navegue até o diretório do projeto:

```
cd laravel-crud-app
```

3. Instale as dependências do Composer:

```
composer install
```

4. Copie o arquivo `.env.example` para `.env`:

```
cp .env.example .env
```

5. Configure o arquivo `.env` com suas informações de banco de dados:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=seu_banco_de_dados
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
```

6. Gere a chave de aplicativo Laravel:

```
php artisan key:generate
```

7. Execute as migrações do banco de dados para criar as tabelas necessárias:

```
php artisan migrate
```

8. Inicie o servidor local:

```
php artisan serve
```

Acesse o aplicativo em [http://localhost:8000](http://localhost:8000).

## Uso

Este aplicativo permite que você realize operações CRUD em uma entidade específica. Para começar, você pode:

- Visualizar todos os registros
- Criar um novo registro
- Atualizar um registro existente
- Excluir um registro existente

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para reportar problemas ou sugestões de melhoria.


**Nota:** Este projeto ainda está em desenvolvimento. 
