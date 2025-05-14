# Banco Digital Simulator

Um simulador de banco digital desenvolvido em Java para praticar conceitos de programação orientada a objetos.

## 📋 Sobre o Projeto

Este projeto simula as operações básicas de um banco digital, permitindo a criação de diferentes tipos de contas, realização de transações financeiras e gerenciamento de investimentos.

## 🚀 Funcionalidades

- Cadastro de clientes (pessoa física e jurídica)
- Abertura de contas (corrente, poupança e investimento)
- Operações bancárias:
    - Depósito
    - Saque
    - Transferência
    - Consulta de saldo
    - Extrato de transações
- Investimentos:
    - Aplicações em renda fixa e variável
    - Simulação de rendimentos
    - Resgate de investimentos
- Regras específicas por tipo de conta:
    - Taxa de manutenção para conta corrente
    - Limite de cheque especial
    - Rendimento para poupança

## 🛠️ Tecnologias Utilizadas

- Java 8+
- Maven
- JUnit 5

## 📦 Estrutura do Projeto

banco-digital/
├── src/
│   ├── main/java/com/bancodigital/
│   │   ├── config/      # Configurações da aplicação
│   │   ├── model/       # Classes de domínio
│   │   ├── repository/  # Camada de acesso a dados
│   │   ├── service/     # Regras de negócio
│   │   ├── exception/   # Exceções personalizadas
│   │   ├── util/        # Classes utilitárias
│   │   └── Main.java    # Ponto de entrada da aplicação
│   └── test/           # Testes unitários
└── pom.xml             # Configuração do Maven

## 🏁 Como Executar

### Pré-requisitos
- JDK 8 ou superior
- Maven

### Passos para Execução

1. Clone o repositório:
   git clone https://github.com/seu-usuario/banco-digital.git

2. Navegue até o diretório do projeto:
   cd banco-digital

3. Compile o projeto:
   mvn clean compile

4. Execute a aplicação:
   mvn exec:java -Dexec.mainClass="com.bancodigital.Main"

## 🧪 Executando os Testes

mvn test

## 📝 Conceitos Aplicados

- Encapsulamento
- Herança
- Polimorfismo
- Classes abstratas
- Interfaces
- Injeção de dependência
- Tratamento de exceções
- Princípios SOLID

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

- **Willian Bruno** - [https://github.com/Sinnisterr](https://github.com/Sinnisterr)

---

Desenvolvido como projeto educacional para prática de conceitos de programação orientada a objetos em Java.