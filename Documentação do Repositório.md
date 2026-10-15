# 🧺 Da Roça — Alimentos Frescos Direto do Produtor

> Plataforma web moderna e responsiva voltada para a comercialização de kits de frutas, legumes e verduras diretamente de pequenos produtores rurais para o consumidor final, com pagamento na entrega e gestão completa para o produtor.

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-emerald?style=for-the-badge)
![Tecnologia](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20JavaScript-blue?style=for-the-badge)
![Arquitetura](https://img.shields.io/badge/Arquitetura-Single--Page%20Application%20(SPA)-orange?style=for-the-badge)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-green?style=for-the-badge)

---

## 🌾 Sobre o Projeto

O **Da Roça** foi desenvolvido para aproximar o campo da cidade, cortando intermediários e garantindo alimentos recém-colhidos com preço justo. 

A plataforma funciona 100% no navegador (Client-Side), sem dependência obrigatória de servidor back-end ou banco de dados externo para ser executada em testes ou demonstrações, utilizando **LocalStorage** para persistência total dos dados.

### 🌟 Diferenciais
- **12 Kits Prontos** categorizados (Legumes & Verduras, Frutas, e Mistos Completos).
- **Grid Compacto 2x2:** Navegação moderna de 2 em 2 kits lado a lado.
- **Gaveta Lateral de Carrinho (Slide-over Cart):** Adicione múltiplos kits, controle quantidades e visualize subtotais em tempo real.
- **Desconto de Assinatura Semanal:** Opção de 10% OFF recalculada automaticamente no carrinho.
- **Pagamento Presencial no Portão:** Sem necessidade de gateways de pagamento caros. O cliente escolhe pagar via **Pix no QR Code**, **Maquininha de Cartão** ou **Dinheiro com troco**.
- **Notificação Direta para o WhatsApp:** Ao finalizar o pedido, o cliente pode enviar a comanda formatada diretamente para o WhatsApp do entregador/produtor com 1 clique.
- **Painel Executivo do Produtor:** Gráficos interativos com **Chart.js**, métricas de faturamento por período (Hoje, 7 dias, 30 dias), ranking de produtos mais vendidos, CRUD de kits e exportação de relatórios em CSV.

---

## 🚀 Como Executar

Você pode rodar este projeto em menos de 10 segundos:

1. Baixe o arquivo `index.html`.
2. Dê um duplo clique no arquivo para abrir em qualquer navegador (Google Chrome, Mozilla Firefox, Safari ou Microsoft Edge).
3. Pronto! Não é necessário instalar Node.js, Python ou extensões adicionais.

---

## 💻 Perfis de Acesso para Testes

O sistema já vem com contas pré-configuradas no armazenamento local:

| Perfil | E-mail | Senha | O que pode fazer |
| :--- | :--- | :--- | :--- |
| **Produtor Rural** | `produtor@daroca.com` | `123456` | Acessar painel gerencial, editar preços, criar kits, ver gráficos e exportar CSV. |
| **Cliente / Consumidor** | `mariana@email.com` | `123456` | Navegar, assinar desconto semanal, colocar na cesta e fazer pedidos. |

*Você também pode criar novos usuários a qualquer momento pela tela de cadastro.*

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação acessível e rápida.
- **Tailwind CSS (CDN):** Estilização utilitária de ponta, responsiva para celulares, tablets e computadores.
- **JavaScript Moderno (ES6+):** Lógica reativa da aplicação, carrinho, filtros e controle de rotas SPA.
- **Chart.js (CDN):** Renderização visual de gráficos de barra para o faturamento do produtor.
- **LocalStorage API:** Persistência de usuários, catálogo de kits, carrinho e histórico de pedidos.

---

## 📂 Estrutura do Repositório

```text
da-roca/
├── index.html        # Aplicação completa (HTML, Tailwind e JavaScript)
├── README.md         # Documentação completa do projeto
├── LICENSE           # Licença MIT
└── .gitignore        # Arquivos ignorados pelo Git
```

---

## 🌐 Como Publicar no GitHub Pages

Para colocar o site no ar gratuitamente pelo GitHub:

1. Crie um repositório no seu GitHub (exemplo: `da-roca`).
2. Suba os arquivos do projeto para a branch principal (`main`).
3. No repositório, vá em **Settings** > **Pages** (no menu lateral esquerdo).
4. Em **Branch**, selecione `main` e a pasta `/ (root)`.
5. Clique em **Save**. Em instantes seu link estará ativo (ex: `https://seu-usuario.github.io/da-roca/`).

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE). Sinta-se livre para utilizar, modificar e distribuir conforme necessário.