# 🛒 Loja Virtual E-commerce

Aplicação full stack de e-commerce com painel administrativo, cadastro de produtos, controle de pedidos e integração com sistemas externos como Mercado Pago, transportadoras e marketplaces. Hospedagem e armazenamento via Amazon S3 e infraestrutura preparada para produção.

---

## 🚀 Tecnologias Utilizadas

### 🔷 Front-End
- React
- Vite
- TypeScript
- Tailwind CSS
- Axios
- React Router

### 🔶 Back-End
- Laravel 11
- PHP 8.2
- PostgreSQL
- Laravel Sanctum ou JWT
- RESTful APIs

### 🌐 Integrações
- Mercado Pago
- Transportadoras (ex: Melhor Envio, Frenet)
- Marketplaces (Mercado Livre, Shopee)
- AWS S3 (armazenamento de imagens)

### ⚙️ DevOps
- Docker
- Amazon EC2 / S3 / RDS
- GitHub Actions (CI/CD)

---

## 📦 Funcionalidades

- [x] Cadastro de produtos, categorias e banners
- [x] Carrinho e checkout com cálculo de frete
- [x] Pagamento via Mercado Pago (checkout transparente)
- [x] Painel administrativo com login e controle de permissões
- [x] Integração com marketplaces (produtos e pedidos)
- [x] Upload de imagens para Amazon S3
- [x] Responsividade mobile

---

## 🧪 Como rodar localmente

### 🔧 Pré-requisitos
- Node.js 18+
- PHP 8.2+, Composer
- PostgreSQL
- Git

### 🔹 Clone o projeto
```bash
git clone https://github.com/seu-usuario/ecommerce-loja-virtual.git
cd ecommerce-loja-virtual
```

### 🔹 Front-end
```bash
cd client
npm install
npm run dev
```

### 🔹 Back-end (Laravel)
```bash
cd ../server
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

---

## 📂 Estrutura

```
ecommerce-loja-virtual/
├── client/    # Aplicação React
├── server/    # API Laravel
├── infra/     # Docker, AWS, Scripts
└── README.md
```

---

## 📄 Licença

Este projeto está sob a licença MIT.  
Feito com 💻 por **Cleverson Tiago Rosa Ramos**
