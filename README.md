# **AppCadastro (Cadastro de usuário)**

> Um aplicativo Android desenvolvido para poder cadastrar mais usuários e poder ver cada um listado em uma tela separada.

## Descrição
O **AppCadastro** permite ao usuário poder cadastrar novos usuários com telefone e endereço e podera ver cada usuário cadastro na tela de listagem onde mostra o nome, telefone e endereço e o número de usuários cadastrados,(Se fechar o aplicativo e abrir ele de novo todos os dados serão apagados, isso devido apenas um simples trabalho e não ter mais um desenvolvimento programado para o trabalho futuramente). 

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Cadastro-usu-rio
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal onde os dados serão transportados para os registros assim sendo salvos
   │   │   │   ├── Registro.java # Atividade onde os dados são salvos e são possíveis de serem vistos na listagem
   │   │   │   ├── TelaCadastroUsuario.java # Atividade onde pode ser cadastrado o novo usuário
   │   │   │   ├── TelaListagemUsuario.java # Atividade onde é mostrado os novos usuários listados 
   │   │   │   ├── TelaPrincipal.java # Atividade principal para onde o usuário pode escolher para onde ir
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── cadastro_de_usuario.xml # Layout onde possa cadastrar o novo usuário
   │   │   │   │   ├── listagem de usuarios_cadastrados.xml # Layout onde possa ver todos os usuários cadastrados e listados
   │   │   │   │   ├── tela_principal.xml # Layout da tela principal onde pode acessar os dois Layouts
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/d60eec7b-f876-4586-b59f-fff1c988043d)

Uma tela simples, dois botões para poder trocar te telas para poder cadastrar e ver a lista de maneira simultanea, e no final o TextView para ser usado como titulo para mostar qual tela em especifico você está.

> Tela Cadastro

![image](https://github.com/user-attachments/assets/91c99859-a43b-422c-8574-cba6549e4704)

Uma tela simples, 3 EditText para, Nome do usuário, Telefone do usuário e Endereço do usuário para serem salvos no banco de dados, dois botões para cadastrar na lista e poder ser logado a conta e o outro para volta para a tela inicial para escolher a onde quer ir novamente, e no final o TextView para ser usado como titulo para mostar qual tela em especifico você está, aparecera um alerta que o usuário for cadastrado.

> Tela de listagem de usuário

![image](https://github.com/user-attachments/assets/01969912-7d2a-4756-9489-50ba4c818b3e)

Uma tela simples, 3 botões, dois para ver os usuários listados no servidor e o ultimo botão para voltar para tela principal para novamente poder escolher qual tela o usuário queira entrar, e no final o 4 TextView para ser usado como, Nome, Telefone e Endereço onde cada dado do usuário será msotrado e titulo para mostar qual tela em especifico você está e mostrara quantos usuários estão listados no banco.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
