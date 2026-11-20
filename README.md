<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=620&height=60&lines=Kayke%20Augusto;Back-end%20Java%20%7C%20ADS%20em%20curso;Aberto%20a%20est%C3%A1gio%20em%20TI" alt="Kayke Augusto — Back-end Java, estudante de Análise e Desenvolvimento de Sistemas, aberto a estágio em TI" />

**Estudante de Análise e Desenvolvimento de Sistemas · Foco em Back-end com Java**

<!-- TODO: troque SEU-EMAIL@exemplo.com pelo seu e-mail real nos 2 badges abaixo (aqui e no fim do arquivo) -->
<a href="https://www.linkedin.com/in/kayke-augusto-473264413"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Kayke Augusto" /></a>
<a href="mailto:SEU-EMAIL@exemplo.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Enviar e-mail para Kayke Augusto" /></a>
<a href="https://github.com/kayke7899-cmd?tab=repositories"><img src="https://img.shields.io/badge/Reposit%C3%B3rios-181717?style=flat-square&logo=github&logoColor=white" alt="Repositórios de Kayke Augusto no GitHub" /></a>
<img src="https://img.shields.io/badge/Aberto_a_est%C3%A1gio_em_TI-9ECE6A?style=flat-square" alt="Aberto a oportunidades de estágio em TI" />

</div>

---

## 🧠 Sobre mim

```java
import java.util.List;

public final class Desenvolvedor {

    private final String nome;
    private final String foco;
    private final List<String> estudandoAgora;

    public Desenvolvedor() {
        this.nome = "Kayke Augusto";
        this.foco = "Back-end com Java";
        this.estudandoAgora = List.of("Collections", "Spring Boot", "JUnit");
    }

    public String apresentar() {
        return "%s | %s | estudando %s"
                .formatted(nome, foco, String.join(", ", estudandoAgora));
    }

    public boolean disponivelParaEstagio() {
        return true;
    }
}
```

- 🎓 Cursando **Análise e Desenvolvimento de Sistemas**, com foco em desenvolvimento de software.
- ☕ Estudo **Java e Programação Orientada a Objetos** construindo sistemas de verdade: arquitetura em camadas (`model` → `repository` → `service`), regras de negócio e validações.
- 🐧 Tenho interesse em **Linux, redes e segurança da informação** — quero entender o caminho que o código percorre até rodar em produção.
- 🎯 **Busco um estágio em TI** para aplicar o que estudo, aprender com um time e evoluir como profissional.

---

## ⚙️ Tecnologias e ferramentas

<div align="center">

<img src="https://skillicons.dev/icons?i=java,python,html,css,js&theme=dark" alt="Linguagens: Java, Python, HTML, CSS e JavaScript" />

<img src="https://skillicons.dev/icons?i=linux,git,github,vscode&theme=dark" alt="Ferramentas e ambiente: Linux, Git, GitHub e VS Code" />

</div>

**Conceitos que aplico nos projetos:** POO (encapsulamento, herança e polimorfismo) · sobrecarga de métodos e construtores · estruturas de dados e Collections · organização em camadas · modelagem UML e regras de negócio · versionamento com Git e GitHub.

---

## 🚀 Projetos

### 🧪 Destaque — Sistema de Gestão de Laboratório de Enfermagem

`Java` `POO` `UML` `Arquitetura em camadas` `Projeto em equipe`

Projeto acadêmico desenvolvido em uma **equipe de 5 pessoas** para gerenciar a rotina de um laboratório de enfermagem: da reserva da sala pelo professor até a liberação dos materiais pela equipe técnica.

**O que o sistema resolve**

- 📅 **Agendamento de aulas práticas** com bloqueio de horário duplicado (regra de negócio RN02).
- 📦 **Solicitação de kits de insumos** vinculada a uma aula previamente agendada.
- ✅ **Checklist de preparação** — conferência de materiais, teste de equipamentos e liberação da sala.
- 📊 **Controle de estoque** com entrada, saída e baixa de materiais.
- 🔐 **Aprovação de cadastros e exceções** pela coordenação, com 4 perfis de acesso: professor, equipe de laboratório, coordenação e aluno.

**Como foi construído**

- Separação de responsabilidades em camadas: `model/` → `repository/` → `service/` → `Main.java`.
- Modelagem UML com **5 casos de uso documentados (UC01–UC05)**, atores, pré-condições e fluxos principal e alternativos.
- Regras de negócio e validações concentradas na camada de serviço, fora da interface.

**Meu papel:** desenvolvimento e documentação, junto com os outros 4 integrantes.

📂 **[Ver código](https://github.com/kayke7899-cmd/Sistema-de-laboratorio-)** · 📄 **[Ver documentação e casos de uso](https://github.com/kayke7899-cmd/Sistema-de-laboratorio-#readme)**

---

### ☕ Outros projetos em Java

#### 📚 Biblioteca — controle de acervo

Aplicação de console para cadastro e gerenciamento de livros, com controle de exemplares disponíveis. Usei **encapsulamento** para proteger os dados do acervo e **sobrecarga de construtores e métodos** para permitir diferentes formas de cadastrar um livro.

📂 **[Ver código](https://github.com/kayke7899-cmd/Biblioteca)**

#### 👨‍💼 Funcionários — reajustes salariais

Aplicação para cadastro de funcionários e aplicação de reajustes salariais **por percentual ou por valor fixo**, registrando o motivo de cada alteração para manter o histórico rastreável.

📂 **[Ver código](https://github.com/kayke7899-cmd/Funcion-rios)**

---

### 🌐 Front-end

#### 👟 Lura Tênis — site institucional

Site estático de 4 páginas (home, catálogo, sobre e suporte) feito com **HTML5 e CSS3 puro**, sem frameworks. Tema inteiro centralizado em variáveis CSS (`:root`), CSS modularizado por página, layout fluido com `clamp()` / `min()` / `aspect-ratio`, imagens em WebP e suporte a `prefers-reduced-motion` para acessibilidade.

📂 **[Ver código](https://github.com/kayke7899-cmd/Lura_Tenis)**

#### 🎓 DevSchool — cadastro e login

Interface de cadastro e login de uma plataforma de ensino de programação. HTML semântico, layout de duas colunas em **Flexbox**, responsivo, com estados de `hover` e `focus` nos campos do formulário.

📂 **[Ver código](https://github.com/kayke7899-cmd/Login_e_Cadastro)**

---

### 🐍 Python — lógica e estruturas de controle

| Projeto | O que pratica |
| --- | --- |
| [Sistema de cadastro de usuário](https://github.com/kayke7899-cmd/sistema_de_cadastro_de_usuario) | Cadastro e validação de dados em console |
| [Sistema de acesso administrativo](https://github.com/kayke7899-cmd/-Sistema-de-Acesso-Administrativo) | Controle de acesso e autenticação de administrador |
| [Projetos de cadastro](https://github.com/kayke7899-cmd/Projetos-de-cadastros) | Exercícios de lógica, laços e estruturas de decisão |

📁 **[Todos os repositórios →](https://github.com/kayke7899-cmd?tab=repositories)**

---

## 🎯 Foco de estudo

| ☕ Agora | 🚀 Em seguida | 🧭 Mais adiante |
| --- | --- | --- |
| Java Collections | Spring Boot e APIs REST | Segurança de aplicações |
| Maven e organização de build | Testes automatizados com JUnit | Administração de Linux |
| JavaScript e manipulação do DOM | Banco de dados e SQL | Shell Script e redes |

**Base já construída:** fundamentos de Java · POO (encapsulamento, herança e polimorfismo) · lógica de programação · HTML e CSS · Git e GitHub · fundamentos de Linux.

---

## 📊 Linguagens que mais uso

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kayke7899-cmd&layout=compact&langs_count=6&hide_border=true&theme=tokyonight&bg_color=1A1B26&title_color=7AA2F7&text_color=A9B1D6" alt="Linguagens mais usadas: Java 59%, CSS 14%, HTML 13%, Python 12% e JavaScript 3%" />

</div>

<!-- Os cards de stats, streak e gráfico de atividade estão comentados no arquivo SETUP.md.
     Reative quando os números ajudarem a contar sua história. -->

---

## 📫 Vamos nos conectar?

<div align="center">

Estou aberto a **oportunidades de estágio em TI** e a conexões com pessoas da área.

<a href="https://www.linkedin.com/in/kayke-augusto-473264413"><img src="https://img.shields.io/badge/LinkedIn-Vamos_conversar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn de Kayke Augusto" /></a>
<a href="mailto:SEU-EMAIL@exemplo.com"><img src="https://img.shields.io/badge/E--mail-Fale_comigo-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Enviar e-mail para Kayke Augusto" /></a>
<a href="https://github.com/kayke7899-cmd"><img src="https://img.shields.io/badge/GitHub-Meus_projetos-181717?style=for-the-badge&logo=github&logoColor=white" alt="Perfil de Kayke Augusto no GitHub" /></a>

<br><br>

> "A melhor maneira de aprender programação é transformar conhecimento em projetos."

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7AA2F7,100:1A1B26&height=100&section=footer" alt="" />

</div>
