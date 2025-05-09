🌍 ViaLume Turismo - Site Profissional

Este é um site completo de turismo desenvolvido com HTML, CSS, JS, PHP e MySQL. O projeto simula uma agência de viagens com funcionalidades como carrinho de compras, pagamento, painel administrativo e login de usuários.

 🚀 Funcionalidades

- Página inicial com carrossel e destinos em destaque
- Listagem de destinos turísticos
- Pacotes de viagem com reserva
- Carrinho de compras com cálculo de total
- Formulário de pagamento funcional
- Integração com banco de dados (pedidos e usuários)
- Login de administrador
- Painel administrativo com listagem de pedidos
- Página de blog com artigos e dicas
- Página de contato e sobre a agência

 🛠️ Tecnologias Utilizadas

- HTML5 / CSS3 / JavaScript
- Bootstrap 5
- PHP 7+
- MySQL

## ⚙️ Como Instalar

1. Clone ou extraia os arquivos do repositório.
2. Crie um banco de dados MySQL com o nome `vialume`.
3. Execute os arquivos SQL encontrados na pasta `/sql`:
   - `criar_tabela_usuarios.sql`
   - `criar_tabela_pedidos.sql`
4. Configure o servidor local (XAMPP, WAMP ou similar) com os arquivos dentro da pasta `htdocs`.
5. Acesse `http://localhost/site_turismo/index.html`.

## 🔐 Login Administrativo

- Crie um usuário manualmente com senha criptografada (use `password_hash()` do PHP) ou adicione via SQL.
- Login acessível por `login.html`.

## 📁 Estrutura de Pastas

```
site_turismo/
├── admin/              # Painel administrativo
├── assets/             # Imagens, CSS, JS
├── php/                # Scripts PHP (conexão, login, salvar pedido)
├── sql/                # Scripts SQL para o banco de dados
├── index.html          # Página principal
├── pacotes.html        # Pacotes de viagem
├── destinos.html       # Lista de destinos
├── blog.html           # Página de blog
├── contato.html        # Contato
├── sobre.html          # Sobre a agência
├── carrinho.html       # Carrinho de compras
├── pagamento.html      # Pagamento
└── login.html          # Tela de login do admin
```

## 📞 Suporte

Para dúvidas, entre em contato via e-mail (marih.bianchini97@gmail.com).

---

Desenvolvido com ❤️ para projetos profissionais de turismo.
