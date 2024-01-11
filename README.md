# Verificador de PIN

Este é um simples verificador de PIN em JavaScript, apresentado em uma aplicação web básica.

## Funcionalidades

- Gera um PIN aleatório de 4 dígitos.
- Permite que o usuário insira um suposto PIN.
- Fornece feedback sobre se o PIN está correto ou não.
- Dá dicas para indicar se o suposto PIN é muito maior, muito menor, maior ou menor que o PIN gerado aleatoriamente.

## Como Usar

1. Abra o arquivo `index.html` em um navegador da web.
2. Digite um PIN de 4 dígitos no campo de entrada.
3. Clique no botão "Verificar PIN".
4. Observe o feedback apresentado na tela.

## Estrutura do Projeto

- `index.html`: Contém a estrutura HTML para a interface da web.
- `styles.css`: Estiliza a página web.
- `script.js`: Implementa a lógica de verificação do PIN.

## Entendendo o Código

Recebendo o Suposto PIN
A função receberSupostoPin() utiliza um loop do-while para solicitar ao usuário que insira um PIN válido (um número positivo de 4 dígitos).


Verificação do PIN
A função verificarPin(supostoPin, pinPorAdivinhar) compara o suposto PIN inserido pelo usuário com o PIN gerado aleatoriamente. Ela fornece feedback indicando se o PIN está correto ou dá dicas sobre a direção correta.

Integração com a Interface Web
A função verificar() é chamada quando o botão "Verificar PIN" é clicado. Ela obtém o suposto PIN do campo de entrada e chama a função verificarPin(). O resultado é exibido na página web.
## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).