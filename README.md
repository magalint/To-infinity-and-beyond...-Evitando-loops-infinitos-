# ♾Loop Infinito♾

Em Python, um loop infinito ocorre quando  um laço (e.g. _while_ ou _for_) continua a executar indefinidamente, sem nunca encontrar uma condição que o faça parar. Isso pode acontecer, por exemplo, se a condição de término do laço nunca se tornar falsa ou se houver um erro na lógica do laço. 

## 🎯 Exemplo de Loop Infinito com _while_
![image](https://github.com/user-attachments/assets/eb675f29-c703-4df5-9d91-53cef18c1fce)
[https://github.com/magalint/To-infinity-and-beyond...-Evitando-loops-infinitos-/issues/1#issuecomment-2282775804]

![image](https://github.com/user-attachments/assets/35b861eb-a2d9-4442-97b9-71da089206e2)

No exemplo acima, o valor de contador nunca é incrementado, o que significa que a condição contador < 5 permanecerá verdadeira para sempre😱, fazendo com que o laço _while_ nunca termine.

> [!WARNING]
> Loops infinitos podem causar problemas, como travamentos de programa ou consumo excessivo de recursos do sistema.
> 

## 🆘 Como Evitar Loops Infinitos  
| Estratégias    | Detalhamento |
| ------ | ---------|
✅ **Certifique-se de que a condição se torne falsa**| Ao usar _while_, garanta que a condição de término seja atingida em algum momento. Isso geralmente envolve modificação de variáveis dentro do loop para que a condição seja satisfeita.  [https://github.com/magalint/To-infinity-and-beyond...-Evitando-loops-infinitos-/issues/2#issue-2459295591] |
✅ **Use _break_ para sair do loop** | O comando _break_ pode ser usado para sair de um loop antecipadamente, independentemente da condição. Isso é útil se você estiver esperando uma condição específica que não seja facilmente expressa na própria condição do _while_. [https://github.com/magalint/To-infinity-and-beyond...-Evitando-loops-infinitos-/issues/3#issue-2459296807]  |
✅ **Limite iterações com contadores** | Em alguns casos, é útil incluir um contador que limite o número máximo de iterações, mesmo que a condição principal do loop não tenha sido atendida. [https://github.com/magalint/To-infinity-and-beyond...-Evitando-loops-infinitos-/issues/4#issue-2459297696] |
✅ **Evite dependências externas descontroladas** | Se o loop depende de fatores externos, como a leitura de dados de um arquivo ou uma entrada do usuário, certifique-se de que há uma condição de escape clara.

[![magalint's GitHub stats](https://github-readme-stats.vercel.app/api?username=magalint)](https://github.com/magalint/github-readme-stats)









