# Git & GitHub: Os 20% Essenciais para Uso Diário

Git e GitHub são ferramentas absolutamente indispensáveis para versionamento de código e colaboração eficaz. Nesta postagem, vamos nos concentrar nos 20% mais cruciais de funcionalidades que cobrem 80% do trabalho no dia a dia de qualquer desenvolvedor, garantindo uma experiência prática e produtiva.

---

## 1. Inicializando e Configurando Git

Antes de mais nada, precisamos configurar o Git localmente para trabalharmos de maneira personalizada. Aqui estão os comandos essenciais:

```bash
git init
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```
Esses comandos configuram o Git no seu ambiente local e inicializam um novo repositório, permitindo que você comece a monitorar todas as mudanças em seu projeto.

## 2. Ciclo de Vida dos Arquivos
O ciclo mais comum de trabalho com Git é simples, mas extremamente poderoso:

Modificar arquivos: Edite seus arquivos conforme necessário.
Adicionar ao Staging:
```bash

git add .
```
Adiciona todas as alterações ao estágio para preparar o commit.
Commitar as mudanças:
```bash

git commit -m "Mensagem explicativa"
```
Salva permanentemente as mudanças no histórico do projeto.
Enviar para GitHub:
```bash

git push origin main
```
Envia as alterações locais para o repositório remoto no GitHub.
## 3. Clonando e Atualizando Repositórios
Se você deseja clonar um repositório existente para começar a trabalhar nele, aqui está o comando que você usará:

```bash

git clone <URL>
```
Para baixar as últimas atualizações do repositório remoto, utilize:

```bash

git pull
```
Dessa forma, você mantém seu ambiente de desenvolvimento sincronizado com o repositório remoto.

## 4. Trabalhando com Branches
Branches são a espinha dorsal do desenvolvimento colaborativo. Elas permitem que você trabalhe em novas funcionalidades sem interferir no código principal.

Criar uma nova branch:

```bash

git checkout -b minha-nova-branch
```
Verificar branches existentes:

```bash

git branch
```
Fazer merge de uma branch:

```bash

git merge minha-nova-branch
```
Essas operações garantem que você consiga trabalhar de forma isolada e depois integrar suas mudanças ao código principal, de maneira suave e organizada.

## 5. Resolvendo Conflitos de Merge
Infelizmente, conflitos podem ocorrer ao tentar fazer merge de branches. Felizmente, resolvê-los é simples com o Git:

Verifique o status dos conflitos:
```bash

git status
```
Resolva os conflitos manualmente nos arquivos marcados pelo Git.
Adicione os arquivos resolvidos:
```bash

git add <arquivo>
```
Finalize o merge com um commit:
```bash

git commit
```
Embora possa parecer um pouco assustador à primeira vista, resolver conflitos com o Git se tornará uma parte natural do seu fluxo de trabalho.

## 6. Pull Requests e Colaboração no GitHub
O GitHub brilha em ambientes colaborativos, facilitando a contribuição de vários desenvolvedores para um único projeto. O fluxo de trabalho com pull requests segue alguns passos simples:

Crie um fork do repositório no GitHub para sua própria conta.
Clone seu fork localmente:
```bash

git clone <URL-do-seu-fork>
```
Sincronize seu fork com o repositório original para manter-se atualizado:
```bash

git remote add upstream <URL-do-repo-original>
```
Após fazer suas mudanças, crie um pull request no GitHub, propondo que suas modificações sejam mescladas ao repositório original. Simples, mas extremamente poderoso!

Conclusão
Com esses comandos e operações, você está equipado para lidar com a maioria das interações diárias envolvendo Git e GitHub. Este conjunto de ferramentas vai agilizar drasticamente seu fluxo de trabalho e garantir que você possa colaborar de forma eficiente e organizada em todos os seus projetos.