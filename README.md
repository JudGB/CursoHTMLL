# Clone da Página Inicial do Google (Projeto de Estudos)

Este repositório contém uma réplica da interface clássica da página inicial do Google. Desenvolvido do zero, o projeto tem como objetivo **consolidar conhecimentos fundamentais em desenvolvimento Web front-end**, aplicando conceitos de estruturação semântica, estilização moderna e práticas de design responsivo.

---

## Sobre o Projeto

Este projeto foi construído **exclusivamente para fins didáticos e de estudo**. A proposta foi recriar visualmente a interface de um dos mecanismos de busca mais famosos do mundo para praticar a lógica de marcação do HTML5 e a organização de folhas de estilo com CSS3. 

A página foi planejada para se adaptar a diferentes tamanhos de tela, oferecendo componentes específicos para navegação móvel e áreas que reproduzem as seções reais do site, como o cabeçalho de navegação, a barra de pesquisa interativa com múltiplos ícones e o rodapé institucional.

---

## Demonstração Visual

<div align="center">
  
  ### Versão Desktop
  <img src="https://github.com/JudGB/CursoHTMLL/blob/main/assets/img/imagemprojetodesk.png" alt="Versão Desktop" />

  ### Versão Mobile
  <img src="https://github.com/JudGB/CursoHTMLL/blob/main/assets/img/imagemprojetomob.png" alt="Versão Mobile" />
</div>

---

## Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias nativas da web, priorizando a semântica e a performance:

* **HTML5:** Estruturação semântica de todo o documento (tags como `<header>`, `<main>`, `<nav>`, e `<footer>`).
* **CSS3:** Estilização geral, importação de fontes personalizadas, gerenciamento de layouts e redefinições com `normalize.css`.
* **Design Responsivo:** Uso de classes utilitárias (como `.hide-on-desktop`) para adaptar a interface entre dispositivos móveis e desktops.
* **JavaScript:** Arquivo de scripts configurado de forma assíncrona (`defer`) para manipulação de ações futuras na página.

---

## O Que Foi Aprendido Neste Estudo

O desenvolvimento deste clone permitiu a compreensão prática de conceitos essenciais de Front-end:

* **Uso de IDs vs. Classes:** Aplicação de `id` para elementos únicos na página (como o botão `#btn-tres` ou o campo de perfil `#profile`) e `class` para componentes reutilizáveis (como as variantes de botões e seletores de ocultação).
* **Estruturação Semântica:** Substituição do uso excessivo de `<div>` por tags que indicam o real significado do conteúdo para navegadores e leitores de tela.
* **Manipulação de Formulários:** Integração do campo de busca com a URL real de pesquisa do Google usando o atributo `action="https://google.com"` e o `name="q"` no campo de texto.

---

## Como a Responsividade Foi Configurada

A adaptação para telas menores foi implementada através de uma abordagem baseada em classes utilitárias no CSS:

* **Classes de Ocultação Dinâmica:** Criação da classe `.hide-on-desktop` que controla quais elementos aparecem apenas em celulares (como o menu hambúrguer, o carrossel de abas "Todas/Imagens" e a lista de "Pesquisas em alta").
* **Uso de Flexbox:** Organização dos menus e da barra de busca de forma flexível, garantindo que os ícones internos (teclado, microfone, câmera e lupa) se alinhem perfeitamente de forma proporcional ao tamanho da tela.

---

## Estrutura de Arquivos

Abaixo está o mapeamento da organização dos arquivos utilizados neste estudo:

```text
├── assets/
│   ├── css/
│   │   ├── fonts.css         # Importação e configuração de tipografia
│   │   └── normalize.css     # Reset padrão para consistência entre navegadores
│   ├── img/
│   │   ├── foto.png          # Avatar simulado de perfil
│   │   └── googleon.png      # Imagem da logomarca principal
│   ├── js/
│   │   └── scripts.js        # Lógica de scripts do projeto
│   └── svg/                  # Ícones utilizados na interface (lupa, microfone, câmera, etc)
├── judson-google/
│   └── css/
│       └── style.css         # Folha de estilo principal com as regras de layout
└── index.html                # Arquivo principal de marcação estrutural
```

---

## Como Executar o Projeto Localmente

Para visualizar e testar o projeto no seu computador, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone github.com/JudGB/CursoHTMLL
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd CursoHTMLL
   ```

3. **Abra o arquivo principal:**
   Basta dar um duplo clique no arquivo `index.html` ou utilizar a extensão **Live Server** no seu editor de código (como o VS Code) para visualizar as alterações em tempo real.

---

## Como Hospedar Este Projeto de Graça (GitHub Pages)

Caso queira colocar este projeto online para exibir em seu portfólio de estudos, siga estes passos usando o **GitHub Pages**:

1. No seu repositório aqui no GitHub, clique na aba **Settings** (Configurações) na barra superior.
2. No menu lateral esquerdo, navegue até a seção **Pages** (dentro do grupo *Code and automation*).
3. Na seção **Build and deployment**, mude a opção *Source* para **Deploy from a branch**.
4. Logo abaixo, no campo *Branch*, selecione a sua branch principal (`main`) e a pasta raiz (`/root`).
5. Clique em **Save**.
6. Aguarde alguns minutos. O GitHub gerará um link público (ex: `https://github.io`) onde qualquer pessoa poderá interagir com a sua página!
7. Segue meu próprio site: https://judgb.github.io/CursoHTMLL/

---

## Considerações Finais

Projeto desenvolvido por **Judson** como parte do repositório de aprendizado `CursoHTMLL`. O código reflete o progresso prático em estilização CSS, uso correto de seletores e boas práticas iniciais de desenvolvimento web.
