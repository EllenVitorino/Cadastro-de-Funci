# 🧑‍💼 Sistema de Gestão de Funcionários

Desenvolvido por **Ellen Vitorino** como parte de um mini sistema web utilizando PHP puro e PostgreSQL. O sistema permite autenticação de usuários, gerenciamento completo de funcionários (cadastro, edição, visualização, exclusão) além de busca e paginação.

---

## ✅ Funcionalidades do Sistema

- 🔐 Login seguro com sessão
- 🚪 Logout
- 🔄 Recuperação de senha (orientativa)
- ➕ Cadastro de novos funcionários
- ✏️ Edição de dados
- 👁️ Visualização detalhada
- ❌ Exclusão com confirmação
- 🔍 Busca por nome, cargo ou e-mail
- 📄 Paginação (5 registros por página)
- 🎨 Layout responsivo sem frameworks externos

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão |
|------------|--------|
| PHP | 5 (com extensão `pgsql`) |
| PostgreSQL | Qualquer versão compatível |
| HTML5 | - |
| CSS3 | - |
| pgAdmin4 | Gerenciamento do banco |

---

### 2. Configurar conexão
Edite `config/config.php`:
```php
return array(
    'db_host' => 'localhost',
    'db_port' => '5432',
    'db_name' => 'sistema_ellen',
    'db_user' => 'postgres',
    'db_password' => 'sua_senha'
);

