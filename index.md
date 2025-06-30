---
layout: default
title: Início
---

# Olá, eu sou [Seu Nome] 👋

Bem-vindo ao meu portfólio de desenvolvedor! Aqui você encontra meus principais projetos, um pouco sobre mim e como entrar em contato.

## Projetos em Destaque

<ul>
  {% for project in site.data.projects %}
    <li>
      <strong>{{ project.title }}</strong><br>
      {{ project.description }}<br>
      <a href="{{ project.link }}">Ver projeto</a>
    </li>
  {% endfor %}
</ul>

## Sobre Mim

Sou desenvolvedor com experiência em [suas tecnologias principais]. Apaixonado por resolver problemas e criar soluções inovadoras.

## Contato

- Email: seu@email.com
- [LinkedIn](https://linkedin.com/in/seuusuario)
- [GitHub](https://github.com/seuusuario)
