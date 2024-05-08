# Shiny Green Bird
Este repositório contém uma série de cenários de teste de caixa preta para o aplicativo Duolingo, abordando diferentes casos de uso, desde o login bem-sucedido até o registro de novos usuários utilizando diferentes métodos de autenticação, como e-mail, Facebook e Google.

## Aplicativo Escolhido
[Duolingo](https://www.duolingo.com/)

## Descrição da Aplicação Escolhida
O Duolingo é um aplicativo de aprendizado de idiomas que oferece uma ampla variedade de cursos gratuitos para usuários de todo o mundo.

## Pré-requisitos
- Softwares Utilizados:
  - [Selenium IDE](https://www.selenium.dev/selenium-ide/): Extensão para navegador web utilizada para gravação e execução de testes automatizados.
![](https://github.com/AnrryPetrin/shiny-green-bird/blob/main/SELENIUM%20IDE.png)
- Arquivos no Conteúdo do Repositório:
  - Documento README.md
  - Arquivo Selenium IDE com os testes gravados
  - Planilha com os cenários de teste elaborados

## Executando os Testes
- **Ferramenta Utilizada para Execução dos Testes:** Extensão Selenium IDE.
- **Sistema Operacional:** Ubuntu 24.04 LTS.
- **Navegador:** Mozilla Firefox Snap for Ubuntu 125.0.3.

## Pontos de Cobertura de Teste 
Os pontos de cobertura de teste da tela de login incluem:
- Teste de login bem-sucedido
- Teste de tentativa de login com credenciais inválidas
- Teste de login com conta do Facebook
- Teste de login com conta do Google
- Teste de registro de novo usuário
- Teste de tentativa de registro com informações incompletas
- Tesde de registro de novo usuário com conta do Facebook
- Teste de recuperação de senha

## Registro de Teste
![](https://github.com/AnrryPetrin/shiny-green-bird/blob/main/SELENIUM%20IDE%20DUOLINGO.png)
O vídeo gravado para a atividade pode ser acessado [aqui](https://www.example.com).

## Considerações
1. O Selenium IDE não conseguiu efetuar login no site do Duolingo com sucesso, independentemente do método utilizado (login direto, Google e Facebook).
2. Mesmo fora do Selenium IDE, o login via Facebook apresentou problemas consistentes, incluindo a incapacidade de clicar no botão de login/registro com o Facebook e falhas na integração.
3. Mensagens de erro indicaram possível detecção de atividade robótica durante os testes de login, sugerindo medidas de segurança implementadas pelo Duolingo.
4. Todos os testes usando credenciais invalidas ou incompletas funcionaram como esperado, retornando mensagens de erro.  
   
## Autor
- Anrry Petrin De Araujo
  - anrry.petrin@gmail.com
  - 200342
