# Barber Shop - API

Este repositório contém o backend do sistema de gerenciamento de uma barbearia.

## 🚀 Funcionalidades

- **Gerenciamento de Agendamentos**: Permite que clientes agendem serviços.
- **Cadastro de Usuários**: Registro de clientes e barbeiros.
- **Controle de Disponibilidade**: Gerencia horários disponíveis.

## 🛠️ Tecnologias Utilizadas

- **Backend**: Java com Spring Boot
- **Banco de Dados**: PostgreSQL
- **ORM**: JPA com Hibernate
- **Migrations**: Flyway
- **Build**: Gradle

## 📂 Estrutura do Projeto

- `src/main/` - Código-fonte principal.
- `gradle/` - Arquivos do Gradle.
- `.gitignore` - Arquivos ignorados pelo Git.
- `Dockerfile` - Criação de imagem Docker.
- `docker-compose.yml` - Configuração de contêineres Docker.
- `build.gradle.kts` - Configuração do Gradle.
- `settings.gradle.kts` - Configurações do Gradle.
- `start-dev.sh` - Script de inicialização do ambiente de desenvolvimento.

## ▶️ Como Executar o Projeto

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/Lucassml-boop/barber-shop-api.git
   ```

2. **Navegue até o Diretório do Projeto**

   ```bash
   cd barber-shop-api
   ```

3. **Configure o Banco de Dados**

   - Certifique-se de que o PostgreSQL está instalado.
   - Crie um banco de dados e ajuste as configurações no `application.properties`.

4. **Execute as Migrações do Banco de Dados**

   ```bash
   ./gradlew flywayMigrate
   ```

5. **Compile e Execute a Aplicação**

   ```bash
   ./gradlew bootRun
   ```

6. **Acesse a API**

   A API estará disponível em `http://localhost:8080/`.

