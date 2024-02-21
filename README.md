<H1 align="center">Aplicativo simulando RPG estilo Tinder</H1>
<p align="center">🚀 Projeto de criação de uma estrutura de aplicativo utilizando Flutter para referências futuras</p>

## Visão Geral
Este aplicativo foi projetado utilizando Flutter para simular a estrutura de um aplicativo de relacionamentos


## Configuração

### Passo 1: Alterando o canal Flutter

É necessário alterar a versão do Flutter para uma versão específica, neste caso, para a versão 2.0.1. Mas antes de mudar para uma versão específica, é importante garantir que você esteja no canal correto do Flutter. Neste caso, vamos mudar para o canal master.

Digite o seguinte comando no seu terminal:

```
flutter channel master
```

### Passo 2: Alterando a versão do Flutter
Navegue até a pasta onde o Flutter está instalado em seu sistema usando o terminal

```
cd E:\src\flutter
```
Agora, você precisa usar o Git para fazer o checkout para a versão desejada. No nosso caso, queremos a versão 2.0.1:
```
git checkout 2.0.1
```
Este comando fará com que você trabalhe com a versão 2.0.1 do Flutter, onde o aplicativo foi desenvolvido.

### Passo 3: Verificar a Instalação e baixar arquivos necessários
Depois de mudar para a versão desejada, é importante verificar se tudo está configurado corretamente. Para isso, execute o seguinte comando:

```
flutter doctor -v
```

Isso verificará a instalação do Flutter e baixará quaisquer arquivos necessários para a versão selecionada.

Após executar esses passos, você estará pronto para desenvolver ou compilar seu aplicativo usando a versão 2.0.1 do Flutter.


### Passo 4 (Opcional): Solucionando erro de versão de compilação do Java 

```
flutter doctor --android-licenses
```

```
java.lang.UnsupportedClassVersionError: 
com/android/sdklib/tool/sdkmanager/SdkManagerCli has been compiled 
by a more recent version of the Java Runtime (class file version 61.0), 
this version of the Java Runtime only recognizes class file versions up to 52.0’
```

A mensagem de erro específica indica que o arquivo de classe SdkManagerCli foi compilado com uma versão mais recente do Java Runtime (class file version 61.0), enquanto a versão do Java Runtime que você está usando só reconhece versões de arquivos de classe até 52.0.

No caso a versão 52 é a necessária que é correspondente com a versão 8 com base na tabela de versões do Java.

<div align="center">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_Stocks/assets/157809964/35cf45a7-f805-46d1-b101-788c67707930" style="width:50%">
</div>


Agorá vá até o SDK manager do Android Studio e baixe o SDK Command-line correspondente com a versão 52

<div align="center">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_Stocks/assets/157809964/f2668f73-902d-458e-8392-3ecc2ff70605" style="width:50%">
</div>

Após baixar a versão correspondente navegue até a pasta onde SDK esta instalado e altere a versão baixada (8.0) para latest

<div align="center">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_Stocks/assets/157809964/3fa35ce5-6ead-4295-869f-945a3c9cb6bf" style="width:50%">
</div>




### Passo 5 (Opcional): Solucionando erro de Android Studio não encontrado

Comando utilizado para configurar o diretório do Android Studio no ambiente do Flutter caso tenha instalado em um diretório diferente.
```
flutter config --android-studio-dir="caminho\do\Android Studio"
```

### Passo 6 (Opcional): Solucionando erro de Java não encontrado
```
‘Unable to find bundled Java version with flutter doctor.....’
```
O erro "Unable to find bundled Java version" indica que o Flutter não conseguiu encontrar uma versão do Java incluída no pacote. Isso pode ocorrer quando o Flutter não consegue localizar a instalação do Java em seu sistema ou quando a instalação do Java não está configurada corretamente.

Este erro pode estar sendo causado quando a pasta jre dentro do diretório do Android Studio estiver vazia ou com apenas um arquivo, para solucionar basta copiar e colar a pasta jbr e renomea-la para jre

<div align="center">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_Stocks/assets/157809964/a8e5ca2a-dd26-40f2-905d-c38108075edb" style="width:50%">
</div>


## Funcionalidades Principais

### Perfil do Personagem
Perfil de aventureiro, o aplicativo de relacionamentos para exploradores e aventureiros destemidos em busca de companheiros de jornada!:

Perfil 
- Nome de Aventureiro: 
- Classe: 
- Nível de Experiência:
- Equipamento:

Atributos:

- Força: 
- Agilidade: 
- Inteligência: 




<div align="center">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_TinderRpg/assets/157809964/df989e39-4b85-4876-807a-b613aa510b72" style="width:40%">
  <img src="https://github.com/lucasmargui/Flutter_Projeto_TinderRpg/assets/157809964/9f22f9ba-fd25-4e58-80ae-7f5af968348c" style="width:40%">
</div>







