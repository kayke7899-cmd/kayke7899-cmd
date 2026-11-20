<!--
  README de perfil — kayke7899-cmd
  Tema: Cyberpunk Neon | Terminal futurista / *nix
  Dica: personalize os links de contato antes de publicar.
-->

<div align="center">

# `KAYKE AUGUSTO`

### `BACK-END JAVA` · `ADS` · `LINUX`

<a href="https://www.linkedin.com/in/kayke-augusto-473264413">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/kayke7899-cmd?tab=repositories">
  <img src="https://img.shields.io/badge/Projetos-181717?style=flat-square&logo=github&logoColor=white" alt="Meus repositórios">
</a>
<img src="https://img.shields.io/badge/Status-Aberto%20a%20estágio-0aff00?style=flat-square" alt="Aberto a estágio em TI">
<img src="https://img.shields.io/badge/Tema-Cyberpunk%20Neon-00f3ff?style=flat-square" alt="Tema Cyberpunk Neon">

<img src="https://readme-typing-svg.herokuapp.com/?font=JetBrains+Mono&color=00F3FF&size=24&center=true&vCenter=true&width=550&height=45&lines=HELLO+WORLD;I+AM+KAYKE+AUGUSTO" alt="Hello World — I am Kayke Augusto">

</div>

---

## `$ whoami --verbose`

```text
kayke@dev:~$ whoami --verbose

🎓 Estudante de Análise e Desenvolvimento de Sistemas.
☕ Foco em Java e Programação Orientada a Objetos.
🐧 Interessado em Linux, redes e segurança.
🎯 Em busca de uma oportunidade de estágio em TI.
```

Gosto de entender como as coisas funcionam por trás do código. Tenho estudado Java, orientação a objetos, organização de projetos em camadas e modelagem de sistemas com UML.

Meu objetivo é desenvolver uma base sólida em back-end, aprender boas práticas de programação e transformar conhecimento em projetos práticos.

<details>
  <summary><code>$ cat Desenvolvedor.java</code></summary>

```java
import java.util.List;

public final class Desenvolvedor {

    private final String nome;
    private final String foco;
    private final List<String> estudandoAgora;

    public Desenvolvedor() {
        this.nome = "Kayke Augusto";
        this.foco = "Back-end com Java";
        this.estudandoAgora = List.of(
            "Collections",
            "Spring Boot",
            "JUnit"
        );
    }

    public String apresentar() {
        return "%s | %s | estudando %s".formatted(
            nome,
            foco,
            String.join(", ", estudandoAgora)
        );
    }

    public boolean disponivelParaEstagio() {
        return true;
    }
}
```

</details>

## `$ cat ~/.config/stack.cyber`

```ini
[linguagens]
principal = Java
secundarias = Python, JavaScript
markup = HTML5, CSS3

[ambiente]
sistema_operacional = Linux
editor = VS Code
controle_de_versao = Git e GitHub

[conceitos]
poo = encapsulamento, herança, polimorfismo
sobrecarga = métodos e construtores
arquitetura = model, repository, service
modelagem = UML e regras de negócio

[proximos_passos]
backend = Spring Boot, APIs REST, JUnit, Maven
dados = SQL e modelagem relacional
infra = Shell Script, redes e administração Linux
```

## `$ ls ~/tecnologias/`

<div align="center">

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code">

</div>

**Na fila de estudos:**

<div align="center">

<img src="https://img.shields.io/badge/Spring_Boot-414868?style=flat-square&logo=spring&logoColor=white" alt="Spring Boot — em estudo">
<img src="https://img.shields.io/badge/Maven-414868?style=flat-square&logo=apachemaven&logoColor=white" alt="Maven — em estudo">
<img src="https://img.shields.io/badge/JUnit-414868?style=flat-square&logo=junit5&logoColor=white" alt="JUnit — em estudo">
<img src="https://img.shields.io/badge/SQL-414868?style=flat-square&logo=mysql&logoColor=white" alt="SQL — em estudo">

</div>

## `$ ls -la ~/projetos/`

### 🧪 Sistema de Laboratório

**Java · POO · UML · Projeto em equipe de 5 pessoas**

Sistema acadêmico para a rotina de um laboratório de enfermagem: da reserva da sala pelo professor até a liberação dos materiais pela equipe técnica.

```text
sistema-laboratorio/
├── model/         # Entidades do domínio
├── repository/    # Acesso e persistência dos dados
├── service/       # Casos de uso, regras e validações
└── Main.java      # Interface de console
```

**Casos de uso implementados (UC01–UC05):**

| Código | Caso de uso | Ator |
|:---:|---|---|
| UC01 | Agendar aula prática, bloqueando horários duplicados (RN02) | Professor |
| UC02 | Solicitar kit de insumos vinculado à aula agendada | Professor |
| UC03 | Checklist de preparação e liberação da sala | Equipe de laboratório |
| UC04 | Controle de estoque: entrada, saída e baixa | Equipe de laboratório |
| UC05 | Aprovar cadastros e solicitações fora do prazo | Coordenação |

**Decisões de projeto:** regras de negócio concentradas em `service/`, quatro perfis de acesso com permissões distintas e modelagem UML com pré-condições e fluxos alternativos documentados antes da implementação.

**Meu papel:** desenvolvimento e documentação, em uma equipe de cinco pessoas.

- [Código-fonte do projeto](https://github.com/kayke7899-cmd/Sistema-de-laboratorio-)
- [Documentação UML](https://github.com/kayke7899-cmd/Sistema-de-laboratorio-#readme)

### Outros projetos

| Repositório | Descrição | Tecnologias |
|---|---|---|
| [Biblioteca](https://github.com/kayke7899-cmd/Biblioteca) | Cadastro e controle de acervo em console; encapsulamento e sobrecarga de construtores e métodos. | Java · POO |
| [Funcion-rios](https://github.com/kayke7899-cmd/Funcion-rios) | Reajuste salarial por percentual ou valor fixo, com registro do motivo de cada alteração. | Java · POO |
| [Lura_Tenis](https://github.com/kayke7899-cmd/Lura_Tenis) | Site de quatro páginas com CSS puro, design system em `:root`, CSS modular, layout fluido com `clamp()`, WebP e `prefers-reduced-motion`. | HTML5 · CSS3 |
| [Login_e_Cadastro](https://github.com/kayke7899-cmd/Login_e_Cadastro) | DevSchool — telas de cadastro e login, HTML semântico, Flexbox e estados de foco. | HTML5 · CSS3 |
| [sistema_de_cadastro_de_usuario](https://github.com/kayke7899-cmd/sistema_de_cadastro_de_usuario) | Cadastro e validação de usuários em console. | Python |
| [Sistema-de-Acesso-Administrativo](https://github.com/kayke7899-cmd/-Sistema-de-Acesso-Administrativo) | Controle de acesso e autenticação de administrador. | Python |
| [Projetos-de-cadastros](https://github.com/kayke7899-cmd/Projetos-de-cadastros) | Exercícios de lógica, laços e estruturas de decisão. | Python |

[ Ver todos os repositórios ](https://github.com/kayke7899-cmd?tab=repositories)

## `$ git status --future`

**Legenda:** `+` concluído · `!` em andamento · `-` na fila

- [x] Fundamentos de Java
- [x] POO: encapsulamento, herança e polimorfismo
- [x] Sobrecarga de métodos e construtores
- [x] Arquitetura em camadas (`model` / `repository` / `service`)
- [x] Modelagem UML e regras de negócio
- [x] HTML5, CSS3 e layout responsivo
- [x] Git e GitHub
- [x] Fundamentos de Linux
- [ ] Java Collections
- [ ] Maven e organização de build
- [ ] JavaScript e manipulação do DOM
- [ ] Spring Boot e APIs REST
- [ ] Testes automatizados com JUnit
- [ ] SQL e modelagem de dados
- [ ] Shell Script e redes
- [ ] Administração Linux
- [ ] Segurança de aplicações

## `$ github --stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kayke7899-cmd&show_icons=true&hide_border=true&theme=github_dark&bg_color=0a0e1a&title_color=00f3ff&text_color=ffffff&icon_color=ff00ff" alt="Estatísticas do GitHub de Kayke Augusto">

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kayke7899-cmd&layout=compact&langs_count=6&hide_border=true&theme=github_dark&bg_color=0a0e1a&title_color=00f3ff&text_color=ffffff" alt="Linguagens mais utilizadas nos repositórios">

</div>

## `$ ping kayke --estagio`

<div align="center">

**Aberto a oportunidades de estágio em TI e a trocar ideias sobre Java, Linux e back-end.**

<a href="https://www.linkedin.com/in/kayke-augusto-473264413">
  <img src="https://img.shields.io/badge/LinkedIn-Vamos%20conversar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Vamos conversar pelo LinkedIn">
</a>
<a href="https://github.com/kayke7899-cmd">
  <img src="https://img.shields.io/badge/GitHub-Meus%20projetos-181717?style=for-the-badge&logo=github&logoColor=white" alt="Meus projetos no GitHub">
</a>

<br>

<sub>Markdown · ☕ Java · Linux · <a href="https://github.com/enkia/tokyo-night-vscode-theme">Tokyo Night</a></sub>

```bash
kayke@dev:~$ echo "A melhor maneira de aprender programação é transformar conhecimento em projetos."

A melhor maneira de aprender programação é transformar conhecimento em projetos.

kayke@dev:~$ logout
Connection to github.com closed.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,100:00f3ff&height=100&section=footer" alt="">

</div>
