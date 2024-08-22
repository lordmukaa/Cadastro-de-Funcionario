# Cadastro de Funcionários

Este é um projeto Java desenvolvido para gerenciar o cadastro de funcionários. O sistema permite a administração de informações contratuais, documentações e dados operacionais dos funcionários por meio de uma interface gráfica intuitiva com múltiplas abas.

## Estrutura do Projeto

O projeto é organizado da seguinte maneira:

- **src/main/java/br/com/cadastrofuncionarios/**: Contém as classes Java principais do projeto.
- **src/main/resources/**: Contém arquivos de texto com anotações e explicações sobre o código.
- **pom.xml**: Arquivo de configuração do Maven.
- **target/**: Diretório gerado pelo Maven que inclui os arquivos compilados e o JAR executável do projeto.

## Classes Principais

- **CadastroFuncionariosApp.java**: Classe principal que inicializa a aplicação.
- **AbaPrincipal.java**: Gerencia a aba principal do sistema, exibindo informações gerais dos funcionários.
- **AbaContrato.java**: Gerencia informações contratuais dos funcionários.
- **AbaDocumentacao.java**: Responsável pela gestão de documentações dos funcionários.
- **AbaOperacional.java**: Administra as informações operacionais, como cargo e departamento.

## Como Executar

### Pré-requisitos

- JDK 8 ou superior
- Maven 3.6 ou superior

### Passos para execução

1. Clone o repositório:

   ```bash
   git clone <url_do_repositorio>

Documentação
Dentro do diretório src/main/resources/ você encontrará dois arquivos de texto que fornecem mais informações sobre o projeto:

anotacoes_projeto.txt: Anotações gerais sobre o desenvolvimento do projeto.
explicacao_codigo_abas.txt: Explicação detalhada do código relacionado às abas da interface gráfica.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do projeto e enviar um pull request com melhorias ou novas funcionalidades.

Segurança
Para informações sobre vulnerabilidades de segurança, consulte o arquivo SECURITY.md.
