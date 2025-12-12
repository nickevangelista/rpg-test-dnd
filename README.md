# 📜 Grimório do Bardo (D&D 5e Spell Manager)

![GitHub Pages](https://img.shields.io/badge/status-online-success?style=for-the-badge&logo=github)
![Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-blue?style=for-the-badge)

Um gerenciador de magias web, leve e responsivo, focado na classe **Bardo** para Dungeons & Dragons 5ª Edição. Desenvolvido para substituir o papel e lápis, permitindo o controle de slots de magia e grimório diretamente pelo celular.

---

### 🔗 [Acesse o Grimório Online Aqui](https://nickevangelista.github.io/rpg-test-dnd/)

---

## ✨ Funcionalidades

* **🎲 Controle Visual de Slots:** Sistema de "bolhas" para marcar slots gastos e disponíveis intuitivamente.
* **💾 Persistência de Dados:** Usa `LocalStorage` do navegador. Você pode fechar a aba ou reiniciar o celular e sua ficha continua salva (sem necessidade de banco de dados).
* **📖 Grimório Dinâmico:** Adicione e remova magias personalizadas com nome, nível e descrição.
* **💤 Descanso Longo:** Botão único para recuperar todos os slots e HP.
* **📱 Design Responsivo:** Interface escura (Dark Mode) otimizada para uso em smartphones durante as sessões de RPG.
* **🚫 Validação de Regras:** Impede o gasto de slots se não houver disponíveis e trata Truques (Cantrips) como custo zero.

## 🛠️ Tecnologias Utilizadas

Projeto construído com **Vanilla JS** (JavaScript Puro), sem dependência de frameworks pesados, garantindo carregamento instantâneo.

* **HTML5** (Estrutura Semântica)
* **CSS3** (Variáveis CSS, Flexbox e Design Responsivo)
* **JavaScript (ES6+)** (Manipulação de DOM e LocalStorage)

## 🚀 Como usar localmente

Se quiser rodar ou modificar o projeto no seu computador:

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/nickevangelista/rpg-test-dnd.git](https://github.com/nickevangelista/rpg-test-dnd.git)
    ```
2.  Entre na pasta:
    ```bash
    cd rpg-test-dnd
    ```
3.  Abra o arquivo `index.html` em qualquer navegador.

## 🔮 Próximos Passos (Roadmap)

* [ ] Adicionar rolagem de dados (d20, d6, d8) integrada.
* [ ] Implementar sistema de "Upcasting" (usar slot de nível superior).
* [ ] Permitir exportar/importar ficha em JSON.

---

Feito com 🎶 e ☕ por [Nick Evangelista](https://github.com/nickevangelista)
