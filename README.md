# iScrev Notes

Bem-vindo ao **iScrev Notes**, uma aplicação web *local-first* de diário digital e caderno de anotações. O projeto une a clareza do texto digitado, a liberdade do desenho manual e a precisão da notação matemática em uma única experiência acolhedora e focada.

![Mulher na cafeteria usando iScrev Notes App](images/woman_coffee_shop_notes.png)

## Sobre o Projeto

O **iScrev Notes** não é apenas mais um bloco de notas. Ele foi concebido com uma filosofia de **computação acolhedora**, desenhado para parecer um objeto de escrita pessoal e não um painel administrativo frio. 

Ele opera de forma totalmente **local-first**, garantindo total privacidade: seus dados vivem localmente no seu dispositivo, reduzindo fricções e dispensando completamente a necessidade de criação de conta ou login.

## Funcionalidades Principais

- **Modos de Uso Híbridos**: Alterne perfeitamente entre Edição (texto), Caneta (desenho livre) e Preview (visualização).
- **Suporte a Markdown & LaTeX**: Formate seus textos de maneira rica e utilize o poder do KaTeX para renderizar equações e fórmulas matemáticas rapidamente.
- **Desenho Manual**: Faça anotações manuscritas, destaques ou esboços livremente por cima de suas notas usando a camada vetorial (SVG), com suporte a mouse, toque e stylus.
- **Persistência Local Confiável**: Suas notas são salvas de forma automática e segura no navegador utilizando IndexedDB (com fallback para `localStorage`).
- **Exportação e Importação**: Exporte seus cadernos em Markdown (preservando até mesmo os traços visuais em base64) e gere arquivos PDF fiéis à interface original da aplicação.
- **Internacionalização**: Interface nativa disponível em Português (PT-BR) e Inglês (EN).

## Tecnologias Utilizadas

Este projeto segue uma abordagem intencionalmente enxuta (Vanilla) para garantir máxima autonomia tecnológica, performance e simplicidade operacional:

- **HTML5 & CSS3**: Estrutura limpa, utilizando CSS moderno (variáveis e propriedades como `backdrop-filter`) para criar a identidade tátil e editorial de um "caderno e tinta".
- **JavaScript Puro**: Lógica do cliente sem frameworks e sem necessidade de ferramentas de *build*.
- **KaTeX**: Solução para renderização fluida da matemática.
- **IndexedDB**: Backend nativo do navegador para armazenamento veloz.
- **SVG / Pointer Events**: Utilizados no motor de caneta manuscrita em vez de Canvas, permitindo traços independentes e que mantêm total fidelidade para exportação ou impressão.

---

Para mais informações, ler detalhes técnicos profundos ou utilizar a aplicação, acesse nosso site oficial:  
**[www.iscrev.com](https://www.iscrev.com)**