# Minimalist Skin Android Studio
Criando uma skin para emulador Android Studio

## Skin
Efetue o download deste projeto e extraia em uma pasta qualquer.

Você deverá procurar a pasta Android contendo a SDK em seu sistema.

Dentro dela deverá copiar o conteúdo extraído do projeto, diretamente na pasta *skin*.

```bash
cd ~/Android/Sdk/skins
```

## Android Studio
Na tela inicial do **Android Studio**, clica em **Configure**, em seguida **AVD Manager**.
<h1 align="center">
  <img width="350px" src="/assets/Android Studio.png" />
</h1>
A seguir teremos acesso a todos os *devices* já configurados. Selecionaremos **Create Virtual Device**.

## Hardware
Definiremos aqui as configurações de hardware do nosso sistema Android.

Iremos em **New Hardware Profile**, para que possamos buscar nosso novo modelo.
<h1 align="center">
  <img width="500px" src="/assets/New hardware.png" />
</h1>
Informe um novo nome, configurações de resolução de tela e memória RAM, em seguida na opção **Default Skin** procure no diretório **Android** nossa pasta **Minimalist** que extraímos anteriormente.
<h1 align="center">
  <img width="500px" src="/assets/Configuration.png" />
</h1>
Feito isso, **Finish**.

## Device
Iremos aplicar configurações da funcionalidade do sistema

Selecionamos, o agora presente, *device* **Minimalist** (ou nome criado anteriormente) e depois, **Next**.
<h1 align="center">
  <img width="500px" src="/assets/Device Minimalist.png" />
</h1>
A tela exibida diz respeito a versão do Android a ser utilizada. Escolha uma.
<h1 align="center">
  <img width="500px" src="/assets/Image.png" />
</h1>

- [Defina um nome]
- [Clica em **Show Advanced Settings**]
- [Em **Device Frame** selecione novamente a pasta corresponde a *skin* **Minimalist**]
- [Docker]
- [TypeORM]

**Finish**.

Tendo realizados os passos anteriores, basta clicar em **Launch** e executar a aplicação.

<h1 align="center">
  <img width="400px" src="/assets/Android.png" />
</h1>