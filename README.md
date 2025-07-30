
# 🔍 Aplicação de Linha de Comando em Go

Este é um projeto simples escrito em Go que permite buscar **IPs** e **servidores (NS)** de um domínio na internet diretamente pelo terminal.

## 📦 Funcionalidades

- Obter os **endereços IP** de um domínio.
- Obter os **servidores de nomes (NS)** de um domínio.

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/linha-de-comando.git
cd linha-de-comando
```

### 2. Instale as dependências

Este projeto utiliza a biblioteca [urfave/cli](https://github.com/urfave/cli).

Para instalá-la:

```bash
go get github.com/urfave/cli
```

> Certifique-se de ter o Go instalado em sua máquina.

### 3. Compile e execute

```bash
go run main.go comandos --host=dominio.com
```

### Exemplos de uso

#### 🔹 Buscar IPs

```bash
go run main.go ip --host=google.com
```

#### 🔹 Buscar servidores (NS)

```bash
go run main.go servidores --host=google.com
```

## 🧠 Estrutura do Projeto

```
.
├── go.sum
├── go.mod
├── main.go       // Ponto de entrada da aplicação
└── app/
    └── app.go    // Definição dos comandos e lógica de busca
```

## 🛠️ Tecnologias

- **Go (Golang)**
- **CLI com urfave/cli**

## 📄 Licença

Este projeto está sob a licença MIT.

