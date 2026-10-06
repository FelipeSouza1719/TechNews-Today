# TechNews Today 🚀

O **TechNews Today** é um portal de notícias responsivo e dinâmico focado em trazer as últimas novidades do mundo da tecnologia. O projeto apresenta um layout moderno com uma área de destaque para artigos principais, uma seção de conteúdos multimídia (vídeos) e um formulário funcional para inscrição em newsletters.

---

## 💻 Sobre o Projeto

Este site foi desenvolvido para praticar a estruturação semântica, a estilização moderna com layouts responsivos e a introdução à lógica de back-end para captura de dados de formulários.

### Funcionalidades Principais:
* **Destaque de Artigos:** Um card principal adaptativo focado na manchete do momento (*"IA Revoluciona Desenvolvimento"*).
* **Seção Tech em Vídeo:** Integração de conteúdos de vídeo diretamente no corpo da página para engajamento do usuário.
* **Newsletter Dinâmica:** Um formulário lateral de captura de e-mails segmentado por área de interesse (Ex: *Inteligência Artificial*), contendo caixas de seleção de termos de aceite e validações básicas.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando uma stack simples e eficiente para a web:

* **HTML5:** Utilizado para a marcação semântica e estruturação do site (artigos, formulários, inputs e seções).
* **CSS3:** Responsável por toda a identidade visual, incluindo:
  * Paleta de cores moderna (tons escuros de azul e roxo com gradientes vibrantes).
  * Design Responsivo utilizando **Flexbox** e/ou **CSS Grid** para posicionar os cards e o formulário lateral de maneira harmônica.
  * Efeitos visuais e estilização personalizada de inputs e botões de chamada para ação (CTA).
* **PHP:** Empregado no back-end para processar os comandos do formulário, tais como:
  * Coleta dos dados enviados via método `POST` ou `GET`.
  * Estruturas de validação inicial dos campos (verificação de e-mail e checagem do checkbox de termos de uso).

---

## 🚀 Como Executar o Projeto

Como o projeto utiliza scripts em PHP, ele precisa ser executado em um ambiente de servidor local.

1. **Instale um servidor local** como [XAMPP](https://apachefriends.org), [WampServer](https://wampserver.com) ou [Laragon](https://laragon.org).
2. **Clone este repositório** para a pasta de arquivos públicos do seu servidor (ex: `htdocs` no XAMPP):
   ```bash
   git clone https://github.com
   ```
3. **Inicie os serviços do Apache** através do painel de controle do seu servidor local.
4. **Abra o navegador** e digite o endereço:
   ```text
   http://localhost/technews-today/
   ```

---

## 📦 Estrutura de Arquivos

```text
├── css/
│   └── style.css          # Toda a estilização e responsividade do portal
├── index.php              # Página principal estruturada em HTML e PHP
├── README.md              # Documentação do projeto
└── assets/                # Imagens e mídias locais (opcional)
```

---

## 📝 Próximos Passos (Melhorias Futuras)
* [ ] Conectar o formulário PHP a um banco de dados MySQL para armazenar os leads da newsletter.
* [ ] Implementar envio automático de e-mail de confirmação usando a biblioteca *PHPMailer*.
* [ ] Tornar o feed de notícias dinâmico, puxando os artigos diretamente do banco de dados.

---
Desenvolvido com 💜 por [Felipe de Souza Ferreira](https://github.com).
