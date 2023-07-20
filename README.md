# Pomodoro Timer

Este é um programa simples de timer Pomodoro implementado em Python usando a biblioteca `tkinter`. O timer Pomodoro é uma técnica de gerenciamento de tempo que alterna períodos de trabalho intenso com pausas curtas e regulares. O objetivo é melhorar a produtividade e a concentração durante as sessões de trabalho.

![Pomodoro Timer Screenshot](pomodoro_timer_screenshot.png)

## Funcionalidades

- Timer para períodos de trabalho de duração configurável (padrão: 25 minutos).
- Intervalos de pausa curta (padrão: 5 minutos) e pausa longa (padrão: 20 minutos).
- Indicação visual dos diferentes estágios (trabalho, pausa curta, pausa longa) por meio de cores e rótulos.
- Contagem das sessões de trabalho concluídas exibida como marcas de verificação (✔).

## Requisitos

Para executar o programa, é necessário ter o Python instalado na sua máquina, juntamente com a biblioteca `tkinter`, que geralmente é incluída por padrão na instalação do Python.

## Como Usar

1. Clone o repositório ou faça o download dos arquivos do programa.

2. Execute o arquivo `pomodoro_timer.py` em um ambiente Python.

3. O programa abrirá uma janela com o timer Pomodoro e uma imagem de um tomate (o ícone tradicional do Pomodoro).

4. Clique no botão "Start" para iniciar o timer. Ele começará com um período de trabalho de 25 minutos (ajustável no código).

5. Após o término do período de trabalho, o timer mudará para uma pausa curta de 5 minutos (também ajustável no código). Durante a pausa curta, o rótulo indicará "Break" e a cor será rosa.

6. Depois da pausa curta, o timer retornará a um novo período de trabalho de 25 minutos. Esse padrão se repetirá até que o timer tenha concluído 4 sessões de trabalho.

7. Após a quarta sessão de trabalho, o timer fará uma pausa longa de 20 minutos (ajustável no código). Após a pausa longa, o ciclo recomeçará.

8. Clique no botão "Reset" a qualquer momento para interromper o timer e reiniciar a contagem.

## Customização

O programa pode ser personalizado de acordo com as preferências do usuário. Abaixo estão algumas variáveis que podem ser ajustadas no código:

- `WORK_MIN`: Duração em minutos do período de trabalho padrão (padrão: 25 minutos).
- `SHORT_BREAK_MIN`: Duração em minutos da pausa curta padrão (padrão: 5 minutos).
- `LONG_BREAK_MIN`: Duração em minutos da pausa longa padrão (padrão: 20 minutos).
- `FONT_NAME`: Nome da fonte usada no rótulo do timer (padrão: "Courier").
- Cores utilizadas no programa (padrão: PINK, RED, GREEN, YELLOW).

## Contribuições

Este é um projeto simples e de código aberto, e as contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para enviar um pull request.

## Autor

Este projeto foi desenvolvido por [Tiago Ary](https://github.com/seu-usuario-github) como parte do curso [100 Days of Code: The Complete Python Pro Bootcamp for 2023](https://www.udemy.com/course/100-days-of-code/)

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
