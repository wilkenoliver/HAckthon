# µCommunity 🚀

> **Manhã e noite, uma comunidade só.**

O **µCommunity** é um protótipo desenvolvido para o **µHackathon do Centro Universitário Braz Cubas**, com o objetivo de aproximar alunos de diferentes turmas e egressos da área de tecnologia.

A plataforma reúne uma **vitrine de projetos acadêmicos** e uma **rede de mentoria**, permitindo que estudantes descubram projetos, interesses e pessoas com conhecimentos complementares.

---

## 🎯 Problema

Projetos, conhecimentos e contatos dos alunos de tecnologia muitas vezes ficam restritos às suas próprias turmas.

Além disso, oportunidades de colaboração e mentoria podem ser perdidas porque alunos da manhã, noite e antigos alunos da instituição acabam tendo pouco contato entre si.

O µCommunity foi pensado para criar uma ponte entre essas pessoas.

---

## 💡 Solução

O µCommunity centraliza em um único espaço:

* 👥 Alunos de diferentes turmas
* 🎓 Egressos da instituição
* 💻 Projetos desenvolvidos pelos estudantes
* 🤝 Oportunidades de mentoria
* 🔎 Busca por áreas de interesse
* 🌐 Conexões entre alunos da manhã e da noite

A proposta é transformar projetos acadêmicos em oportunidades de **aprendizado, colaboração, networking e desenvolvimento profissional**.

---

## ✨ Funcionalidades

### 📂 Vitrine de projetos

A plataforma apresenta projetos desenvolvidos pelos alunos, permitindo filtrar por:

* Turma da manhã
* Turma da noite
* Tecnologia utilizada

Tecnologias disponíveis no protótipo:

`Web` · `Mobile` · `IA` · `Dados` · `Design` · `Jogos` · `IoT` · `Segurança`

Cada projeto apresenta:

* Nome
* Autor
* Turma
* Descrição
* Tecnologias utilizadas
* Opção para solicitar mentoria

---

### 🤝 Rede de mentoria

O usuário informa:

1. Nome
2. Turma
3. Área de interesse

A plataforma então procura mentores compatíveis com o interesse selecionado.

O sistema prioriza pessoas da **turma oposta** e egressos, buscando justamente aproximar pessoas que normalmente não teriam contato.

---

### 🔎 Sistema de Match

O protótipo possui uma lógica simples de recomendação.

O sistema verifica a área de interesse do estudante e procura mentores que possuam essa mesma área.

Também existe uma priorização relacionada à turma:

* Mentor de outra turma → maior prioridade
* Mentor disponível para qualquer turma → prioridade intermediária
* Mentor da mesma turma → menor prioridade

Os dois primeiros resultados compatíveis são apresentados ao usuário.

---

## 🧩 Como funciona

```text
                 µCOMMUNITY
                     │
          ┌──────────┴──────────┐
          │                     │
     Vitrine de              Mentoria
      Projetos                  │
          │                     │
    ┌─────┴─────┐        ┌─────┴─────┐
    │           │        │           │
  Manhã       Noite    Interesse    Turma
    │           │        │           │
    └─────┬─────┘        └─────┬─────┘
          │                    │
          └──────────┬─────────┘
                     │
                  MATCH 🤝
                     │
                  Mentor
```

---

## 🛠️ Tecnologias utilizadas

O protótipo foi desenvolvido utilizando tecnologias web básicas:

* **HTML5**
* **CSS3**
* **JavaScript**
* **Google Fonts**

O projeto utiliza HTML para estruturar a aplicação, CSS para a interface visual e JavaScript para os filtros, renderização dos projetos e sistema de match de mentoria.

---

## 🎨 Interface

A interface utiliza uma identidade visual moderna e tecnológica, com:

* 🌑 Tema escuro
* 🟢 Destaques em verde/mint
* 🟠 Elementos relacionados à turma da manhã
* 🟣 Elementos relacionados à turma da noite
* 📱 Layout responsivo
* ✨ Animações e efeitos de interação
* 🎯 Navegação por seções

A aplicação também possui adaptação para diferentes tamanhos de tela.

---

## 📱 Estrutura da aplicação

O projeto possui três áreas principais:

### 1. A ideia

Apresenta os cinco pilares da comunidade:

* Pessoas
* Interesse comum
* Interação
* Valor
* Continuidade

Esses pilares representam a proposta de criar uma comunidade contínua, e não apenas uma plataforma de acesso.

### 2. Vitrine

Área destinada à descoberta dos projetos desenvolvidos pelos estudantes.

O usuário pode filtrar os projetos por turma e tecnologia.

### 3. Mentoria

Área destinada à busca de pessoas que possam ajudar o estudante em determinada área.

O protótipo utiliza dados simulados para demonstrar o funcionamento do sistema de match.

---

## 📁 Estrutura do projeto

```text
ucommunity/
│
├── index.html
└── README.md
```

No protótipo atual, toda a estrutura HTML, CSS e JavaScript está concentrada no arquivo HTML.

---

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone SEU_LINK_DO_REPOSITORIO
```

### 2. Entre na pasta

```bash
cd ucommunity
```

### 3. Execute o projeto

Como o projeto é um protótipo web estático, basta abrir o arquivo:

```text
index.html
```

Você também pode utilizar o **Live Server** no VS Code para executar o projeto localmente.

---

## 🧪 Dados do protótipo

Atualmente, os projetos e mentores são **dados ilustrativos**, utilizados para demonstrar a navegação e o funcionamento do sistema de recomendação.

Alguns exemplos de projetos presentes no protótipo:

* TrilhaCerta
* BikeShare Campus
* EstudaJunto
* SegurAlerta
* DadosBC
* PixelQuest
* TutorIA
* AcessoFácil

O código também possui exemplos de mentores, como egressos e alunos veteranos de diferentes áreas.

---

## 🚀 Próximos passos

A versão apresentada é um **MVP/protótipo**.

Algumas evoluções possíveis:

* [ ] Sistema de cadastro e login
* [ ] Banco de dados real
* [ ] Perfil dos estudantes
* [ ] Perfil dos projetos
* [ ] Upload de projetos
* [ ] Sistema real de mensagens
* [ ] Convites de mentoria
* [ ] Notificações
* [ ] Avaliação de mentores
* [ ] Sistema de autenticação institucional
* [ ] Integração com GitHub
* [ ] Integração com LinkedIn
* [ ] Dashboard de projetos
* [ ] Sistema de recomendação mais avançado
* [ ] Área exclusiva para egressos

---

## 🏆 µHackathon

Projeto desenvolvido para o:

**µHackathon — Centro Universitário Braz Cubas**

### Proposta

> **Conectar pessoas, projetos e conhecimento que normalmente ficariam separados.**

O objetivo do protótipo é demonstrar como uma comunidade acadêmica pode aproximar alunos de diferentes turnos e egressos, criando oportunidades de colaboração, mentoria e networking.

---

## 👥 Equipe

**Equipe µCommunity**

Projeto desenvolvido para o µHackathon do Centro Universitário Braz Cubas.

---

## 📌 Status

🟡 **Protótipo / MVP**

A aplicação atualmente demonstra o fluxo principal da experiência, utilizando dados fictícios. A próxima etapa seria conectar o projeto a cadastros e dados reais dos estudantes.

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e de apresentação no µHackathon.

---
