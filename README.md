# desafio-github-mackdown
Desafio formação DIO, GitHub

# 📌 Mini Resumo: Git e GitHub

## 🧠 O que são?
* **Git:** É um sistema de controle de versão distribuído. Ele roda localmente na sua máquina, registrando o histórico de alterações dos arquivos e permitindo a criação de ramificações (*branches*) para testar novas funcionalidades sem quebrar o código principal.
* **GitHub:** É uma plataforma em nuvem que hospeda repositórios Git. Ele atua como o ponto central para colaboração, permitindo que desenvolvedores trabalhem juntos no mesmo projeto de qualquer lugar.

## ⚙️ Fluxo de Trabalho Básico (Workflow)

O ciclo de vida das alterações no Git geralmente segue três áreas principais: 
**Diretório de Trabalho** ➡️ **Staging Area** (Área de Preparação) ➡️ **Repositório Local** ➡️ **Repositório Remoto**.

### Principais Comandos:

* **`git init`**: Inicializa um novo repositório Git em um diretório local.
* **`git clone [url]`**: Baixa uma cópia de um repositório remoto (do GitHub) para a sua máquina.
* **`git status`**: Mostra o estado atual da sua árvore de trabalho (quais arquivos foram modificados ou adicionados).
* **`git add .`**: Adiciona todas as modificações atuais na *Staging Area*, preparando-as para o commit.
* **`git commit -m "mensagem descritiva"`**: Salva as alterações da área de preparação no histórico do repositório local.
* **`git push`**: Envia os seus commits locais para o repositório remoto.
* **`git pull`**: Busca as alterações do repositório remoto e as mescla automaticamente com o seu repositório local.

## 🌿 Trabalhando com Branches
Branches permitem desenvolver *features* isoladas do código principal (geralmente a branch `main` ou `master`).

* **`git branch`**: Lista todas as branches locais do projeto.
* **`git checkout -b [nome-da-branch]`** (ou `git switch -c`): Cria uma nova branch e já muda para ela.
* **`git merge [nome-da-branch]`**: Junta o código da branch especificada para dentro da branch em que você está no momento..