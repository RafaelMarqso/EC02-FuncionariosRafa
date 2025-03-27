 ## Sistema de Gestão de Funcionários - Startup de Tecnologia

Este é um projeto simples desenvolvido com HTML e JavaScript para gerenciar o cadastro de funcionários em uma startup. Permite o cadastro, edição, exclusão, listagem e relatórios usando funcionalidades modernas do JavaScript.

## Funcionalidades

- Cadastro de funcionários via formulário HTML
- Listagem dinâmica em tabela
- Edição e exclusão com botões por linha
- Geração de relatórios com:
  - Funcionários com salário > R$ 5000
  - Média salarial
  - Lista de cargos únicos
  - Lista de nomes em maiúsculo

##  Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)

##  Como Executar Localmente

### 1. Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/funcionarios-startup.git
cd funcionarios-startup
```

### 2. Abrir o `index.html`
Abra o arquivo `index.html` diretamente no navegador ou siga o passo com Docker abaixo.

---

## Executar com Docker

### 1. Criar o Dockerfile
```Dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
```

### 2. Build e Run
```bash
docker build -t funcionarios-app .
docker run -d -p 8080:80 funcionarios-app
```

Acesse no navegador: [http://localhost:8080](http://localhost:8080)

---

## Exercícios Atendidos

- [x] Cadastro e Listagem de Funcionários
- [x] Excluir e Alterar Funcionários
- [x] Uso de Funções Anônimas e Arrow Functions
- [x] Relatórios com map, filter, reduce
- [x] Versionamento com Git
- [x] Containerização com Docker



