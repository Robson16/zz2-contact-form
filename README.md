# ZZ2: Formulário de Contato

Este é um formulário de contato simples desenvolvido com HTML, CSS e JavaScript. Ele permite aos usuários enviar suas informações de nome, email, telefone e mensagem, que são processadas por uma API configurada na AWS (API Gateway e Lambda).

## Descrição

O projeto utiliza um formulário responsivo para coletar informações de contato, incluindo:

- Nome
- E-mail
- Telefone
- Mensagem

Após o envio, o formulário interage com uma API para armazenar os dados e fornece feedback ao usuário, como a exibição de um spinner enquanto os dados são enviados e uma mensagem de sucesso ou erro.

## Tecnologias Utilizadas

- **HTML5**: Para estruturar o formulário.
- **CSS3**: Para estilizar o formulário, incluindo um design responsivo.
- **JavaScript**: Para validar e enviar os dados via fetch API para a AWS.
- **AWS Lambda + API Gateway**: Para processar os dados do formulário.
- **Inputmask**: Para adicionar máscara de telefone.

## Instalação e Uso

### Clonando o repositório

Se você deseja testar o projeto localmente, siga os passos abaixo para clonar o repositório e configurá-lo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/zz2-contact-form.git
   cd zz2-contact-form
   ```

````
2. Instale as dependências do projeto:
 ```bash
 npm install
````

3. Para monitorar e compilar o Sass em tempo real, execute:

```bash
npm run sass
```

4. Para compilar o Sass para CSS e aplicar o Autoprefixer, execute:

```bash
npm run build
```

## Executando o Formulário

Para testar localmente, abra o arquivo index.html em um navegador de sua escolha.
O formulário está configurado para enviar os dados para uma API na AWS. Certifique-se de que a API esteja configurada corretamente antes de enviar o formulário.

## Scripts

npm run sass: Observa as mudanças no arquivo Sass e gera o CSS correspondente.
npm run build: Compila os arquivos Sass para CSS comprimido e aplica o Autoprefixer.
Contribuição
Se você quiser contribuir para o projeto, fique à vontade para fazer um fork e abrir um pull request. Qualquer contribuição é bem-vinda!

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
