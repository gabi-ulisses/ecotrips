
# 🌍 [Ecotrips](https://gabi-ulisses.github.io/ecotrips


**Ecotrips** é uma agência de viagens ecológicas desenvolvida com HTML e CSS, como parte do estudo da disciplina *Introdução ao Desenvolvimento de Páginas Web*, no curso de *Sistemas para Internet*.

## 📝 **Descrição**

O projeto **Ecotrips** tem como objetivo oferecer uma plataforma simples e intuitiva para a promoção de viagens ecológicas. Através deste site, os usuários podem explorar pacotes de viagens para diferentes destinos, planejar suas próximas aventuras e conferir a galeria de fotos das viagens realizadas.

## ✨ **Funcionalidades**

- **Página Inicial (index.html)**: Apresentação da agência e dos principais destinos.
- **Destinos (destinos.html)**: Lista de pacotes de viagens e destinos com saídas regulares.
- **Empresas (empresas.html)**: Destaque para a possibilidade de parcerias com empresas.
- **Fotos (fotos.html)**: Galeria de fotos das viagens que a agência já realizou.

## 🛠️ **Tecnologias Utilizadas**

- **HTML**: Estruturação do conteúdo do site.
- **CSS**: Estilização e layout das páginas, com animações utilizando keyframes.

## 📂 **Estrutura do Projeto**

```bash
ecotrips/
├── index.html
├── public/
│   ├── destinos.html
│   ├── empresas.html
│   ├── fotos.html
├── css/
│   ├── styles.css
│   ├── index.css
│   ├── destinos.css
│   ├── empresas.css
│   ├── fotos.css
│   └── keyframes.css
└── img/
    ├── ...
    ├────── icones/
    │     ├── ...
    ├────── titulos/
    │     ├── ...
```

## 🎨 **Animações**

As animações dos títulos são gerenciadas pelo arquivo `keyframes.css`, que é importado nas outras folhas de estilo:

```css
/* Exemplo de importação no arquivo index.css */
@import url('keyframes.css');

/* Outras regras CSS */
```

## 🌐 **Como Acessar**

Você pode acessar o site da Ecotrips através do seguinte link: [Ecotrips](https://gabi-ulisses.github.io/ecotrips/).

## 🤝 **Como Contribuir**

Se você deseja contribuir para o desenvolvimento deste projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch: `git checkout -b minha-branch`.
3. Faça suas alterações e commit: `git commit -m 'Minhas alterações'`.
4. Envie para o repositório remoto: `git push origin minha-branch`.
5. Abra um Pull Request.

## 📧 **Contato**

Para mais informações, entre em contato através do e-mail: [gabrielle.ulissess3@gmail.com](mailto:gabrielle.ulissess3@gmail.com).

---
