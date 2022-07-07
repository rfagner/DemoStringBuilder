# DemoStringBuilder
Demonstração do uso da classe StringBuilder
<br><br>
O objeto String é imutável. Sempre que usa um dos métodos na classe System.String, você cria um novo objeto de cadeia de caracteres na memória, 
o que requer uma nova alocação de espaço para esse novo objeto. Em situações em que você precisa realizar repetidas modificações em uma cadeia de caracteres, 
a sobrecarga associada à criação de um novo objeto String pode ser dispendiosa. A classe System.Text.StringBuilder pode ser usada quando você deseja modificar 
uma cadeia de caracteres sem criar um novo objeto. Por exemplo, o uso da classe StringBuilder pode melhorar o desempenho ao concatenar várias cadeias de 
caracteres em um loop.
