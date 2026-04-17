# 🚀 Jornada Dev — Criação de Sites do Zero

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)


[**👉 Acesse a Demo ao Vivo 👈**](https://meu-projeto.netlify.app)  
</div>

---

## 📖 Sobre o Projeto

**Jornada Dev** é uma landing page interativa desenvolvida para apresentar um curso presencial de criação de sites. Mais do que um simples site informativo, ele oferece uma **experiência guiada** onde o visitante é conduzido por um tour virtual pelas aulas, podendo abrir detalhes do cronograma, escolher um projeto final e até gerar um certificado personalizado ao concluir o tour.

O design combina elegância tipográfica com animações suaves, efeito neon, confetes leves e um sistema de missões que torna a exploração do conteúdo divertida e envolvente.

---

## ✨ Funcionalidades Principais

### 🎯 Tour Guiado com Missões
- Barra de progresso fixa que orienta o usuário a explorar cada seção.
- Missões do tipo **scroll** (com confirmação após 5 segundos de leitura) e **click** (abrir detalhes das aulas).
- Feedback visual com destaque pulsante e toast de confirmação.

### 📅 Cronograma Interativo (Acordeões)
- Cada aula pode ser expandida para revelar objetivos, momentos detalhados e desafios.
- Auto‑scroll inteligente ao abrir um bloco.

### 🎨 Efeitos Visuais Sofisticados
- **Roleta de palavras** no hero com animação de queda e cores vibrantes.
- **Certificado 3D** gerado dinamicamente com nome do aluno, baixável como PNG.
- **Confetes leves** (DOM‑based) que sobem e descem em parábola sem travar dispositivos móveis.
- Efeito neon nos textos destacados e cursor personalizado (opcional).

### 📱 Totalmente Responsivo
- Layout adaptável para desktop, tablet e celular.
- Inclusão de media queries e fallbacks para dispositivos de toque.

### 🧠 Estratégias de Ensino Embutidas
- Seção dedicada a dicas de mentalidade e técnicas de aula (líder da turma, cronômetro, IA como copiloto).

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5**  | Estrutura semântica e acessível |
| **CSS3**   | Estilização avançada (variáveis, flex/grid, animações keyframe, backdrop blur) |
| **JavaScript (ES6)** | Lógica do tour, observadores de interseção, geração de certificado, confetes, roleta de palavras |
| **html2canvas** | Captura do certificado para download |
| **Google Fonts** | Tipografia premium (Fraunces, Syne, DM Sans, Caveat) |

---

## 🚀 Como Executar Localmente

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/jornada-dev.git
   cd jornada-dev
   ```

2. **Abra o arquivo `index.html`**  
   Basta dar duplo clique no arquivo ou usar uma extensão como *Live Server* no VS Code.

> 💡 **Nota:** O projeto não requer dependências externas (exceto as fontes e a biblioteca html2canvas, já carregadas via CDN). Tudo funciona offline.

---

## 📁 Estrutura do Projeto

```
jornada-dev/
├── index.html              # Todo o HTML, CSS e JavaScript em um único arquivo auto-contido
├── README.md               # Este arquivo
└── (imagens/ se necessário)
```

> O projeto foi desenvolvido como **Single File Application** para facilitar o deploy e a portabilidade.

---

## 🧩 Personalizações Possíveis

- **Palavras da roleta:** edite o array `words` no JavaScript.
- **Cores dos confetes:** altere o array `colors` na função `lightConfetti`.
- **Missões do tour:** modifique o array `tasks` para adicionar/remover etapas.
- **Dados do certificado:** a função `atualizarQRValidacao` pode ser ajustada para gerar QR Codes dinâmicos.

---

## 🤝 Contribuição

Contribuições são bem‑vindas! Sinta‑se à vontade para abrir uma **issue** ou enviar um **pull request** com melhorias, correções ou novas ideias.

1. Faça um fork do projeto
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Adiciona nova feature'`
4. Push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

---

## 📄 Licença

© Difalls — Todos os direitos reservados.

Este projeto é disponibilizado **apenas para visualização e referência**.  
Nenhuma parte deste código, design, texto ou funcionalidade pode ser:

- Copiada, reproduzida ou redistribuída;
- Utilizada para fins comerciais ou não comerciais;
- Modificada, adaptada ou incorporada em outros projetos;
- Publicada ou distribuída em qualquer meio,

**sem a autorização prévia, expressa e por escrito do autor.**

Para solicitar permissão de uso, entre em contato nas redes descritas abaixo.
- 

---

## 👨‍🏫 Autor

Feito com ❤️ e código por **Difalls ~ask Pedro V.**  
- LinkedIn: [Pedrovictors](https://www.linkedin.com/in/pedrovictors/)
- GitHub: [@Difalls](https://github.com/DiFalls)
- Email: ctt.pedrov@gmail.com

---

<div align="center">

✨ *“Todo mundo pode aprender a criar sites. Basta começar do zero.”* ✨

</div>
```

---
