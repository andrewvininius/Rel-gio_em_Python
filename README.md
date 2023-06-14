# Relógio em Python 🕑

Este é um programa em Python que cria uma janela contendo um relógio analógico usando a biblioteca Tkinter. O relógio exibe a hora atual do sistema e atualiza-se a cada segundo.

>Status: concluído ✔️
## Requisitos

- Python 3.x instalado no sistema.
- Biblioteca Tkinter.

## Como executar o programa

1. Abra um editor de código ou IDE Python.
2. Copie e cole o código fornecido em um novo arquivo.
3. Salve o arquivo com uma extensão ".py", por exemplo, "clock.py".
4. Abra o terminal ou prompt de comando.
5. Navegue até o diretório onde o arquivo "clock.py" foi salvo.
6. Uma janela será aberta exibindo o relógio analógico.

## Funcionamento do programa

O programa usa a biblioteca Tkinter para criar uma janela e um canvas (área de desenho) para exibir o relógio. Ele define as dimensões da janela e do canvas e também configura o título da janela.

A função `update_clock` é responsável por atualizar o relógio a cada segundo. Ela limpa o canvas, obtém a hora atual do sistema usando o módulo `time`, calcula os ângulos para posicionar corretamente os ponteiros e desenha os elementos do relógio usando as funções da biblioteca Tkinter.

O programa desenha o contorno do relógio, os números das horas, as linhas dos minutos e os ponteiros das horas, minutos e segundos. O ponteiro dos segundos é destacado em vermelho.

Depois de desenhar o relógio, a função `update_clock` chama a si mesma novamente após 1 segundo usando o método `after` do canvas. Isso cria um loop que mantém o relógio atualizado continuamente.

O programa continua a ser executado até que a janela seja fechada pelo usuário.

## Personalização

Você pode personalizar a aparência do relógio alterando as configurações como as dimensões, as cores, o tamanho e o estilo da fonte, entre outros. Você pode experimentar diferentes valores para obter o resultado desejado.

Além disso, você pode adicionar recursos adicionais ao programa, como exibir a data, adicionar interatividade ou criar botões para iniciar/parar o relógio.

Divirta-se explorando e personalizando este programa de relógio em Python!

## Tecnologias Usadas:
<table>
  <tr>
    <td>PYTHON</td>
  </tr>
 
</table>

