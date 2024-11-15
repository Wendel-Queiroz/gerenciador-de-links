# Gerenciador de links

Esta é uma criação própria para gerenciar meus links das minhas redes profissionais.

## Índice

- [Visão geral]
- [O desafio]
- [Captura de tela]
- [Links]
- [Meu processo]
- [Construído com]
- [Códigos em Destaque]
- [Agradecimentos]

## Visão geral

### O desafio

- Criar o projeto de acordo com outros modelos que me inspiraram.
- Centralização dos elementos e posicionamentos absoluto.

### Captura de tela

<img src=./src/desing/desktop.png>

### Links

- URL da solução: https://github.com/Wendel-Queiroz/gerenciador-de-links
- URL do site ativo: https://wendel-queiroz.github.io/gerenciador-de-links/

## Meu processo

### Criado com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Grade CSS
- Fluxo de trabalho desktop-first

### Códigos em Destaque

```html
<footer>
                <a href="https://www.linkedin.com/in/wendel-queiroz/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://github.com/Wendel-Queiroz" target="_blank"><i class="fa-brands fa-github"></i></a>
                <a href="https://wendel-queiroz.github.io/portfolio/" target="_blank"><i class="fa-solid fa-address-card"></i></a>
                <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox" target="_blank"><i class="fa-solid fa-envelope-open-text"></i></a>
                <a href="https://www.instagram.com/wendelcqueiroz?igsh=OWxmbnB4MGZmYzQ0" target="_blank"><i class="fa-brands fa-square-instagram"></i></a>
                <a href="https://wa.me/351938460128" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>
            </footer>
```
```css
figure{
    display: flex;
    justify-content: space-between;
    width: 200px;
    height: 45px;
    border: 1px solid #DAA520;
    border-radius: 10px;
    margin-top: 10px;
    align-items: center;
    padding: 10px;
}

figure a{
    color: #8B0000;
}

figure:hover{
    border: 1px solid #F8F8FF;
    background-color: #DAA520;
    box-shadow: 0 5px 15px #8B0000;
    transition: 0.3s ease-in-out;
}
```

Agradecimentos

Sempre seria grato aos irmãoes Ricardo e Roberto, os gêmeos criadores do curso Dev em Dobro!!!