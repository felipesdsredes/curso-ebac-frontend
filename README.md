# curso-ebac-frontend

# exercicio solicitado

Na atividade prática deste módulo, você irá praticar todos os conceitos aprendidos. Se tiver dúvidas, retome o passo a passo nas aulas.

1) Crie um formulário HTML que possua dois campos numéricos:
campo A
campo B

2) Insira um botão para submeter o formulário.

3) Crie uma validação no JavaScript, na qual o formulário será válido caso o número B seja maior que o número A.

4) Exiba uma mensagem positiva para o usuário quando o formulário for válido e uma mensagem negativa quando for inválido.

5) Suba no Github no repositório do curso em uma branch chamada exercicio_html_js.

6) Copie o link do repositório na plataforma da EBAC que a equipe de tutoria dará o feedback.


#programa criado: 
1 - HTML:
Um formulário com ID meuFormulario é criado contendo dois campos de entrada numéricos (campoA e campoB) e um botão de submissão.

2 - JavaScript:
- Um event listener é adicionado ao formulário para capturar o evento de submissão (submit).
- Dentro da função de callback do event listener:
- e.preventDefault() é chamado para evitar o envio padrão do formulário, o que recarregaria a página.
- Os valores dos campos campoA e campoB são obtidos e convertidos para números flutuantes usando parseFloat().
- Uma verificação condicional é realizada para determinar se o valor de campoB é maior que o valor de campoA.
- Se a condição for verdadeira, uma mensagem de alerta é exibida indicando que o formulário é válido.
- Se a condição for falsa, uma mensagem de alerta é exibida indicando que o formulário é inválido e que o valor de campoB deve ser maior que o valor de campoA.

