
# Solar Panel Calculator

Aplicativo interativo para calcular a quantidade certa de placas solares necessárias. O app permite que o usuário selecione opções, visualize a quantidade de placas solares recomendadas e receba as informações por WhatsApp ou e-mail. Também inclui uma apresentação da empresa e funciona como um catálogo de e-commerce com capacidade de gerar uma simulação.

## Funcionalidades

- **Interatividade**: Usuário seleciona opções x, y ou z.
- **Cálculo**: Sistema calcula a quantidade de placas solares necessárias.
- **Contato**: Usuário insere contato (WhatsApp ou e-mail).
- **Apresentação da Empresa**: Informações sobre a empresa e produtos.
- **Simulação**: Geração de uma simulação do resultado.

## Tecnologias Utilizadas

- **Front-End**: React Native, Flutter, ou HTML/CSS/JavaScript
- **Back-End**: Node.js, Firebase
- **Banco de Dados**: Firestore, MongoDB
- **Envio de Mensagens**: Twilio (para WhatsApp), EmailJS (para e-mail)

## Estrutura do Projeto

1. **Tela de Boas-Vindas**: Com uma breve apresentação da empresa.
2. **Tela de Seleção**: Onde o usuário escolhe as opções x, y ou z.
3. **Tela de Resultados**: Mostra a quantidade de placas solares necessárias.
4. **Tela de Contato**: Para o usuário inserir WhatsApp ou e-mail.
5. **Tela de Confirmação**: Mensagem de confirmação e agradecimento.

## Funções Essenciais

### Cálculo de Placas Solares

```javascript
function calcularPlacas(opcao) {
  let quantidadePlacas;
  switch (opcao) {
    case 'x':
      quantidadePlacas = // cálculo para opção x;
      break;
    case 'y':
      quantidadePlacas = // cálculo para opção y;
      break;
    case 'z':
      quantidadePlacas = // cálculo para opção z;
      break;
    default:
      quantidadePlacas = 0;
  }
  return quantidadePlacas;
}

function enviarContato(tipoContato, contato) {
  if (tipoContato === 'WhatsApp') {
    // Código para enviar mensagem via WhatsApp
  } else if (tipoContato === 'Email') {
    // Código para enviar e-mail
  }
}
Contribuição
Sinta-se à vontade para contribuir com o projeto. Sugestões, melhorias e correções são sempre bem-vindas.

