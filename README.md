# 🔐 *Tela de Login com Conexão ao Banco de Dados*

Este projeto consiste em uma tela de login funcional que verifica credenciais armazenadas em um banco de dados antes de redirecionar o usuário para a página de férias. O objetivo é demonstrar a integração entre **front-end e back-end** usando **HTML, CSS, PHP e MySQL**.  

---

## 📖 **Descrição do Projeto**
1. Criamos um banco de dados chamado **usuarios** com uma tabela **login**.  
2. Desenvolvemos um **formulário de login** com campos para **email** e **senha**.  
3. Implementamos um **script PHP** para validar as credenciais com segurança.  
4. Após o login bem-sucedido, o usuário é **redirecionado para a página das férias**.  

---

## 🗄️ **Banco de Dados**
O banco de dados utilizado é o **MySQL**. Para criar a tabela, execute o seguinte script SQL:

```sql
CREATE DATABASE usuarios;

USE usuarios;

CREATE TABLE login (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(255) UNIQUE NOT NULL,
    senha VARCHAR(255) NOT NULL
);

INSERT INTO login (email, senha) VALUES ('usuario@email.com', '123456');

```

<img width="959" alt="image" src="https://github.com/user-attachments/assets/8294c822-a178-40e5-854d-3d454be3ab1e" />




 
