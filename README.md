# Documentação do Sistema "Xadrez Console"

O "Xadrez Console" é um jogo de xadrez desenvolvido em .NET Core 3.1 que permite aos usuários jogar xadrez diretamente no console (CMD). Este jogo é uma demonstração de diversos conceitos relacionados à programação orientada a objetos (POO) e oferece uma experiência simples, mas desafiadora, para os entusiastas do xadrez.

## Requisitos Prévios

Antes de iniciar o jogo "Xadrez Console", certifique-se de que você possui os seguintes requisitos prévios em sua máquina:

- [.NET Core 3.1 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1) instalado.

## Instalação e Execução

Siga os passos abaixo para instalar e executar o jogo "Xadrez Console" em sua máquina:

1. **Clonar o Repositório**:

   Clone o repositório do jogo "Xadrez Console" para o seu ambiente local:

   ```bash
   git clone https://github.com/seu-usuario/xadrez-console.git
   ```

   Substitua `seu-usuario` pelo seu nome de usuário no GitHub, se necessário.

2. **Navegar para o Diretório do Jogo**:

   Navegue até o diretório onde o jogo "Xadrez Console" está localizado:

   ```bash
   cd xadrez-console
   ```

3. **Compilar e Executar o Jogo**:

   Compile e execute o jogo usando o comando `dotnet run`:

   ```bash
   dotnet run
   ```

4. **Jogar Xadrez**:

   Após executar o jogo, você poderá jogar xadrez diretamente no console. Siga as instruções exibidas para fazer seus movimentos e aproveitar o jogo.

## Funcionalidades e Conceitos

O jogo "Xadrez Console" demonstra diversos conceitos relacionados à programação orientada a objetos, incluindo:

- **Herança**: A hierarquia de peças de xadrez é implementada por meio de classes que herdam de uma classe base.

- **Polimorfismo**: As peças de xadrez são representadas como objetos polimórficos que têm comportamentos específicos de acordo com sua classe.

- **Encapsulamento**: Os objetos de peça de xadrez encapsulam seu estado e comportamento para manter a integridade do jogo.

- **Abstração**: As classes abstratas são usadas para definir comportamentos comuns a várias peças de xadrez.

- **Composição**: O tabuleiro de xadrez é composto por casas que contêm as peças, demonstrando o uso de composição.

- **Tratamento de Erros**: O jogo lida com erros de movimentos inválidos e outros problemas para garantir uma experiência de jogo suave.

## Comandos do Jogo

- As coordenadas das casas do tabuleiro são representadas por pares de letras e números, como "a1", "e4", etc.

- Use os comandos exibidos no console para fazer seus movimentos. Por exemplo, para mover uma peça de "e2" para "e4", você pode digitar "e2 e4".

- Siga as instruções do jogo para jogar e aproveitar a partida.

## Notas Finais

O "Xadrez Console" é uma demonstração simples, mas educativa, de programação orientada a objetos e xadrez. Você pode estudar o código-fonte do jogo para entender como os conceitos de POO foram aplicados.

Lembre-se de que este é um projeto de demonstração e pode não oferecer todas as funcionalidades avançadas de um jogo de xadrez completo. No entanto, é uma ótima maneira de aprender e praticar programação orientada a objetos enquanto desfruta de uma partida de xadrez no console.

Para qualquer dúvida ou problema específico relacionado ao jogo, consulte o código-fonte ou entre em contato com o desenvolvedor do projeto. Divirta-se jogando xadrez no console!
