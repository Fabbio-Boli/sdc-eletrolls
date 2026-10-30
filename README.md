# 🛒 SDC-Eletrolls | ATS "Shopping do Cidadão" (2021)

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

Plataforma de recrutamento (ATS - *Applicant Tracking System*) desenvolvida para a empresa **Shopping do Cidadão**.

## 📌 Descrição do Projeto

O SDC-Eletrolls é uma plataforma de recrutamento desenvolvida para otimizar o processo de seleção e contratação do "Shopping do Cidadão". O objetivo central foi eliminar tarefas administrativas redundantes e melhorar três métricas fundamentais de contratação: **velocidade, orçamento e valor líquido agregado dos candidatos**.

Através de um sistema integrado de front-end e back-end, o projeto oferece uma solução completa de triagem baseada em perfis (Match), gestão de vagas pelos Recursos Humanos, processos de *Hackathons* e iniciativas de capacitação técnica (*Educa Cidadão*).

---

## 🚀 Funcionalidades e Jornadas de Utilização

A plataforma está estruturada em torno de duas jornadas principais: **Candidatos** e **Funcionários (Recursos Humanos)**.

### 👔 Painel do Funcionário (RH)
* 🔐 **Controlo de Acesso Seguro:** Apenas funcionários autenticados (ou registados por um administrador interno) têm acesso à área de gestão.
* 📊 **Gerenciamento de Vagas:** Dashboard interativo (com base em DataTables/CloudTables) para manipulação completa das vagas (leitura, atualização, eliminação)[cite: 20].
* 🔍 **Filtros e Pesquisas Avançadas:** Capacidade de filtrar vagas por "Centro", "Cargo", "Data de Abertura" ou alterar o volume de registos (10, 25, 50, 100)[cite: 20].
* 📋 **Relatórios de Candidatos:** Ao clicar numa vaga, o RH visualiza imediatamente os candidatos inscritos, ordenados por padrão de acordo com o seu **Score de Match** com a vaga[cite: 20]. Contactos em destaque agilizam a comunicação[cite: 20].

### 🎓 Jornada do Candidato
* 📝 **Inscrição Multi-modal:** Registo em **Processos Seletivos** (vagas regulares) ou **Hackathons** (eventos de seleção técnica que avaliam capacidade analítica e agilidade)[cite: 20].
* 🎯 **Algoritmo de Match:** O dashboard do candidato mostra as vagas em aberto organizadas pelo percentual de compatibilidade com o perfil preenchido (pesos atribuídos a cada atributo da vaga vs. currículo)[cite: 20].
* 📚 **Educa Cidadão (Programa de Capacitação):** Incentivo ao desenvolvimento de *Soft Skills* e *Hard Skills*. Os candidatos que concluam estes cursos ganham prioridade nas listas de processos seletivos[cite: 20].
* ⚙️ **Área Pessoal Integrada:** Acesso a candidaturas ativas ("Minhas Aplicações"), estado dos processos ("Aberta", "Agendada entrevista", etc.), edição de perfil e um sistema interno de mensagens[cite: 20].

<details>
<summary><b>📸 Capturas de Ecrã (Telas da Aplicação)</b> (Clique para expandir)</summary>
<br>

| Página Principal | Menu de Login / Cadastro |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/29809108/131199430-0a363fcd-2402-412d-a73e-e08e112f98e4.png" width="400"/> | <img src="https://user-images.githubusercontent.com/29809108/131236927-3bf173e5-6e3d-478e-8ef2-7dac62b11505.png" width="400"/> |

| Dashboard RH (Tabela de Vagas) | Formulário Multi-Step (Candidato) |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/29809108/134224541-f4074695-cb6b-4f92-a7f6-ac61ac0f3c28.png" width="400"/> | <img src="https://user-images.githubusercontent.com/29809108/131236951-98ebf5df-4e7c-46e9-ad98-bb9400281be3.png" width="400"/> |

| Sistema de Vagas com \% de Match | Dashboard do Candidato |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/29809108/134245810-b559c5d3-25af-4684-98be-949fc53360fe.png" width="400"/> | <img src="https://user-images.githubusercontent.com/29809108/134249319-58a3a7a4-2aaa-49e6-81c6-b1083db44424.png" width="400"/> |

</details>

---

## 🛠️ Tecnologias Utilizadas

* **Front-end:** HTML5, CSS3, JavaScript, jQuery[cite: 20].
* **Back-end:** PHP (autenticação, CRUD, rotas, lógica de Match)[cite: 20].
* **Banco de Dados:** MySQL (estruturação relacional e armazenamento)[cite: 20].
* **Frameworks & Bibliotecas:** Bootstrap (estilização e modais responsivos), CloudTables/DataTables (tabelas dinâmicas)[cite: 20].

---

## ⚙️ Guia de Instalação (Servidor Local)

Para correr a plataforma SDC-Eletrolls na tua máquina, é necessário configurar um ambiente de servidor local utilizando o **XAMPP**:

1. Descarrega e instala o [XAMPP](https://www.apachefriends.org/download.html)[cite: 20].
2. Inicia o painel do XAMPP e liga os módulos **Apache** e **MySQL**[cite: 20].
3. Testa a ligação acedendo a `http://localhost/dashboard/` no teu navegador[cite: 20].
4. Faz o clone do repositório para o diretório `/htdocs` do XAMPP (por norma em `C:\xampp\htdocs\`)[cite: 20]:
   ```bash
   git clone [https://github.com/Fabbio-Boli/SDC-Eletrolls.git](https://github.com/Fabbio-Boli/SDC-Eletrolls.git)
