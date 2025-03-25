#### O que foi feito até agora, sem commitar:

Adicionei o atributo edicao no formulario, pra filtrar os campos que apareceriam na parte de edição de formulario, por exemplo pra nao aparecer o toggle de enviar email

```
bool edicao = false;
// ai cria o formulario com os campos, entre eles o edicao, se quiser falar que é um campo editavel -> na pasta de InserirCampos, adicionei esse atributo em todos os arquivos e


bool edicao = true;

Map<String, dynamic> campo = {

        'name': name,

        'tipo': 'texto',

        'tamanho': quantity,

        'valor_inicial': initialValue,

        'obrigatoriedade': obrigatoriedade,

        'edicao': edicao,

      };


```