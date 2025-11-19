# decsfinder-wizard-wp-plugin

Plugin wordpress, será utilizado no website do DeCS.

## Função

O plugin consiste em uma sequência de janelas que irão auxiliar usuários inicantes a utilizar o motor de indexação DeCS Finder IA.

A sequência de janelas apresenta três passos, que são os seguintes:

### 1º Passo: Inserção do texto a ser analisado.

<img width="716" height="729" alt="image" src="https://github.com/user-attachments/assets/5bda069d-1baa-4abc-a3ff-15bd7a5b96e5" />

### 2º Passo: Passo onde será informado em qual idioma o texto a ser analisado se encontra.

<img width="554" height="490" alt="image" src="https://github.com/user-attachments/assets/55f22992-7990-4ca0-a282-91bb4057d794" />

### 3º Passo: Definição do idioma no qual a ferramenta deverá retornar os descritores propostos.

<img width="632" height="536" alt="image" src="https://github.com/user-attachments/assets/9f5266b8-2aff-4888-abba-f8403bafa48a" />

### Resultado ou Etapa Final: Apresentação dos resultados.

Ao final dos três passos, o plugin irá realizar uma requisição para a seguinte url: https://decsfinder.bvsalud.org/dmf , que apresentará um resultado conforme os dados enviados, como ilustrado abaixo:

<img width="1911" height="947" alt="image" src="https://github.com/user-attachments/assets/e9ec2646-52e2-40b4-9efd-8b85078446f6" />

## Instalação:

### 1ª Opção: Como a maioria dos plugins pode ser instalado pela interface do wordpress seguindo os seguintes passos:

faça o upload do arquivo através do menu Plugins > Adicionar Novo no painel administrativo, clicando em Carregar plugin. Em seguida, selecione o arquivo .zip do seu computador, clique em Instalar Agora e, por fim, em Ativar


### 2ª Opção:

Clone o repositório do plugin para o diretório de plugin do seu Wordpress, que geralmente pode ser encontrado em <instalação_do_wordpress>/wp-content/plugins/

## Configuração: 

### 1º Passo: Após ser instalado ou por meio de um .zip(na própia interface do Wordpess) ou por meio da clonagem do repositório(dentro da pasta de plugins), basta adicionar o seguinte short-code, na página em qual o wizard deverá ser exibido:


~~~

[formulario_wizard_modal]

~~~


<img width="404" height="170" alt="image" src="https://github.com/user-attachments/assets/75a42da8-7190-40a7-8120-34c778e60804" />

### 2º Passo: Após o shortcode devidamente inserido, realizar a chamada da função que apresentara o código:

~~~

abrirFormWizard()

~~~

No exemplo ilustrado abaixo, a função está sendo chamada no clique de um botão, mas poder ser chamada da maneira que preferir.


<img width="488" height="239" alt="image" src="https://github.com/user-attachments/assets/5b3d68e4-98d1-4b29-b7b1-e6eeb40fe595" />




