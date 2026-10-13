# 🗳️ Sistema de Urna Eletrônica

Um sistema web completo de votação e apuração de votos, desenvolvido com inspiração na **Urna Eletrônica da Justiça Eleitoral Brasileira**. O projeto simula o processo de votação, controle administrativo de urnas, além de relatórios e apuração detalhada dos votos.

---

## 📌 Sumário

- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Interface e Design](#-interface-e-design)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Executar](#-como-executar)
- [Licença](#-licença)

---

## 🔍 Visão Geral

O objetivo principal deste projeto é recriar a experiência visual e funcional da Urna Eletrônica, permitindo:
- Registro de candidatos e configuração da eleição.
- Interface tátil/teclado para digitação de números de candidatos com retorno de voz/som.
- Painel LCD realista com fotos, nome e número dos candidatos.
- Área administrativa protegida por senha para controle de turnos e encerramento.
- Módulo de **Urna Mestra / Apuração**, que gera relatórios visuais com gráficos de desempenho, posições dos candidatos e contagem de votos válidos, brancos e nulos.

---

## ✨ Funcionalidades

### 1. Votação (Interface da Urna)
* **Teclado Físico Interativo:** Teclas numéricas de `0` a `9` com botões funcionais:
  * **BRANCO:** Para votação em branco.
  * **CORRIGE:** Limpa os números digitados para reiniciar o voto.
  * **CONFIRMA:** Grava o voto e emite o sinal sonoro clássico.
* **Visor LCD Digital:** Exibe foto, nome e número do candidato selecionado.
* **Tela de Encerramento:** Mensagem clássica de **"FIM"** ao concluir a votação.

### 2. Controle Administrativo & Segurança
* Proteção por senha em áreas de gerenciamento e encerramento da eleição.
* Modais interativos de confirmação para liberação de eleitores e controle de acesso.

### 3. Relatórios e Apuração de Votos
* **Tabela de Ranking Destacada:** Exibe a classificação dos candidatos, porcentagem de votos e badge para eleitos.
* **Resumo de Votos Gerais:** Indicadores visuais dos totais de votos Válidos, Brancos, Nulos e Total Geral.
* **Card do Vencedor:** Destaque visual com foto e nome do candidato mais votado.
* **Suporte à Impressão:** Formatação pronta para impressão/exportação em PDF do boletim de apuração.

---

## 🎨 Interface e Design

A interface foi desenvolvida focando na precisão visual do modelo real:
- **Painel LCD:** Tom verde clássico com tipografia monoespaçada.
- **Teclado:** Gradientes de iluminação, sombras 3D e efeitos de animação ao clicar nos botões.
- **Relatório de Resultados:** Design moderno e limpo com alto contraste para leitura de estatísticas e dados numéricos.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica dos componentes e telas.
- **CSS3:** Estilização avançada com Flexbox, CSS Grid, gradientes, sombras e responsividade.
- **JavaScript (Vanilla):** Lógica do sistema de votação, armazenamento em memória/localStorage e manipulação do DOM.

---

## 📂 Estrutura do Projeto

```text
.
├── index.html       # Estrutura das telas (Configuração, Votação e Apuração)
├── style.css        # Estilização completa do projeto e temas da urna
└── script.js        # Lógica de votação, validação e contagem de votos
```

---

## 🚀 Como Executar

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/urna-eletronica.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd urna-eletronica
   ```
3. Abra o arquivo `index.html` em qualquer navegador web moderno (Chrome, Firefox, Edge, Safari).

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE) - sinta-se à vontade para usá-lo, modificá-lo e distribuí-lo.