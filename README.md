# Loop infinito♾

Em Python, um loop infinito ocorre quando  um laço (e.g. 'while' ou 'for') continua a executar indefinidamente, sem nunca encontrar uma condição que o faça parar. Isso pode acontecer, por exemplo, se a condição de término do laço nunca se tornar falsa ou se houver um erro na lógica do laço. 

## 📌Exemplo de Loop Infinito com while
![Captura de tela 2024-08-10 170459](https://github.com/user-attachments/assets/64045260-3d5e-49a7-b0de-8958db31d857)

![image](https://github.com/user-attachments/assets/35b861eb-a2d9-4442-97b9-71da089206e2)

No exemplo acima, o valor de contador nunca é incrementado, o que significa que a condição contador < 5 permanecerá verdadeira para sempre😱, fazendo com que o laço _while_ nunca termine.

### 🚨Loops infinitos podem causar problemas, como travamentos de programa ou consumo excessivo de recursos do sistema🚨

## 🆘 Como Evitar Loops Infinitos
| Estratégias    | Detalhamento |
| ------ | ---------|
🧩 **Certifique-se de que a condição se torne falsa**| Ao usar _while_, garanta que a condição de término seja atingida em algum momento. Isso geralmente envolve modificação de variáveis dentro do loop para que a condição seja satisfeita. Issue#2|
🧩 **Use _break_ para sair do loop** | O comando _break_ pode ser usado para sair de um loop antecipadamente, independentemente da condição. Isso é útil se você estiver esperando uma condição específica que não seja facilmente expressa na própria condição do _while_. Issue#3 |
🧩 **Limite iterações com contadores** | Em alguns casos, é útil incluir um contador que limite o número máximo de iterações, mesmo que a condição principal do loop não tenha sido atendida. #Issue#4|
🧩 **Evite dependências externas descontroladas** | Se o loop depende de fatores externos, como a leitura de dados de um arquivo ou uma entrada do usuário, certifique-se de que há uma condição de escape clara.




