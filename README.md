# HABIT — Blog & Plataforma de Conteúdo

> Projeto desenvolvido para a disciplina de Interação Humano-Computador (IHC).

---

## Índice

- [Sobre](#sobre)
- [Páginas do Projeto](#páginas-do-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Usadas](#tecnologias-usadas)
- [Como Visualizar](#como-visualizar)
- [Contribuição](#contribuição)
- [Autores](#autores)
- [Agradecimentos](#agradecimentos)

---

## Sobre

O **HABIT** é um protótipo de plataforma de blog e curadoria de conteúdo, desenvolvido como atividade prática da disciplina de IHC. O projeto explora conceitos de design de interface, usabilidade e responsividade, contemplando tanto a experiência do leitor quanto a área administrativa da plataforma.

---

## Páginas do Projeto

### Públicas
| Página | Descrição |
|---|---|
| `index.html` | Página inicial |
| `categorias.html` | Listagem de posts por categoria |
| `destaques.html` | Posts em destaque |
| `results.html` | Resultados de busca |
| `newsletter.html` | Assinatura de newsletter |
| `login.html` | Login de usuário |
| `cadastro.html` | Cadastro de usuário |
| `perfil.html` | Perfil do usuário |

### Administrativas
| Página | Descrição |
|---|---|
| `admin-categoria.html` | Gerenciar categorias |
| `admin-criarpost.html` | Criar novo post |
| `admin-escolhas-editor.html` | Gerenciar escolhas do editor |
| `admin-usuarios.html` | Gerenciar usuários |
| `admin-fila-revisao.html` | Fila de revisão de posts |
| `admin-fila-comentrarios.html` | Fila de moderação de comentários |

---

## Estrutura do Projeto

```
IHC-Atividade/
│
├── index.html
├── categorias.html
├── destaques.html
├── results.html
├── trabalho-remoto.html
├── newsletter.html
├── login.html
├── cadastro.html
├── perfil.html
│
├── admin-categoria.html
├── admin-criarpost.html
├── admin-escolhas-editor.html
├── admin-usuarios.html
├── admin-fila-revisao.html
├── admin-fila-comentrarios.html
│
├── css/
│   ├── global.css               # Reset, header, footer e estilos globais
│   ├── style.css                # Estilos da página inicial
│   ├── cards-shared.css         # Cards reutilizáveis (categorias, destaques, results)
│   ├── admin-shared.css         # Layout compartilhado do painel admin
│   ├── admin-categoria.css      # Estilos específicos de categorias
│   ├── admin-criarpost.css      # Estilos específicos de criar post
│   ├── admin-escolhas-editor.css
│   ├── admin-table-shared.css   # Tabelas do painel admin
│   ├── categoria.css
│   ├── destaques.css
│   ├── login.css
│   ├── cadastro.css
│   ├── newsletter.css
│   ├── perfil.css
│   ├── results.css
│   └── trabalho-remoto.css
│
└── img/
    ├── hamburguer.png
    └── imgf2.png
```

---

## Tecnologias Usadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Como Visualizar

O projeto está disponível via GitHub Pages:

🔗 **[Acessar o projeto](https://matheussps.github.io/IHC-Atividade/)**

Ou clone o repositório e abra o `index.html` diretamente no navegador:

```bash
git clone https://github.com/MatheussPS/IHC-Atividade.git
```

---

## Contribuição

Cada integrante do grupo contribuiu com commits individuais registrados no histórico do repositório.

## Autores

| Nome |
|---|
| Matheus Pinter Silva |
| Gabriel Tomazine Torres |
| Gabriel Mendes Dias Santos |
| Vinicius Chen Li |

---

## Agradecimentos

Agradecemos ao professor pela orientação e pelo modelo de repositório disponibilizado como referência para organização e documentação deste projeto.
