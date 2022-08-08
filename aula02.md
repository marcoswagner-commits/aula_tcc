# Aula 02 - Projeto Final de Curso 1

> Aula 18/08/2022
> 
>  
>  *O que é uma Pesquisa*


## Atividades da aula - roteiro

## Início da implementação do Modelo Conceitual

### Passo 1: criar projeto
#### Criar uma estrutura de monorepositório para GitHub 
- Criar pasta Gestao_Obras_Projeto dentro do Workspace STS - Criar duas subpastas: backend (bckend_gto) e frontend (frtend_gto):

![Pastas do Projeto](https://github.com/marcoswagner-commits/gestao_obras_aula_daw/blob/fe5c2cc8a99cd618a16d1f43c0a6d133d321c865/pastas_projeto.png)


- Acessar página http://start.spring.io e criar projeto Spring Boot no `Spring Initializr` com as seguintes informações:
  - Name/Artifact: bckend_gto 
  - Group/Package: net.ufjnet.gestaobra
  - Description: API de Gestão de Obras
  - Dependências (aba direita)
    - Web (JSON/TOMACAT/WEB/MVC)
    - Data (DATA_JPA/HIBERNATE/JAKARTA)


- Caso o arquivo pom.xml tenha algum erro::
  - Botão direito no projeto -> Maven -> Update project (force update)
  - Menu Project -> Clean
  
- Baixar arquivo gerado e descompactar dentro da pasta Gestao_Obras_Projeto/bckend_gto.

### Passo 2: criar estruturas de pastas no projeto seguindo o modelo de arquitetura abaixo:
![Modelo de Arquitetura](https://github.com/marcoswagner-commits/gestao_obras_aula_daw/blob/947bf8022b213bb7fe183c39dae8c607a6d60212/modelo_camadas.png)

[![Aulas no Youtube](https://github.com/marcoswagner-commits/gestao_obras_aula_daw/blob/cb3e2ea9547f9ddc831277f07919c3e78451eb92/yt-icon.png)](https://www.youtube.com/channel/UCfO-aJxKLqau0TnL0AfNAvA)
####  Os vídeos abaixo mostram uma exposição completa sobre pesquisa científica

[![material complementar aula02](![Captura de Tela 2022-08-08 às 14 16 21](https://user-images.githubusercontent.com/81576640/183476041-9bc36d98-14ac-475c-8845-a29f2ac41497.png)
)](https://www.youtube.com/watch?v=gTWbCV60nsw&feature=youtu.be)

:shipit: Como começar?
```
![Captura de Tela 2022-08-08 às 14 12 28](https://user-images.githubusercontent.com/81576640/183475089-042c76cf-4bd8-4ca6-9718-7d2497f3385a.png)

```


### Passo 3: criar as estruturas necessárias para criar o banco de dados e inserir a dependêcia LOMBOK



:shipit: Configuração do MySQL no arquivo application.properties
```

```

- Veja o vídeo abaixo que mostra a execução do terceiro passo
- 
[![material complementar aula05](https://raw.githubusercontent.com/marcoswagner-commits/gestao_obras_aula_daw/documentos/documentos/Capa_aula05_mod2.png)](https://youtu.be/gDDe2jvv3fk)

### Passo 4: Atualizar o github com os primeiros códigos

- Obs.: 
	- Instalar o LOMBOK: Acessar a pasta na sua pasta de usuários as seguintes pastas em sequência: .m2 = repository = org = projectlombok = lombok 
	- abrir o arquivo "lombok-1.??.??.jar" - terminal: java -jar "lombok-1.??.??.jar"
	- caso não detecte automaticamente a IDE (STS4) fazer a localização manual
	- fechar e abrir novamente a IDE
	- testar uma classe verificando se os métodos getters e setters estão presentes na instância do objeto
