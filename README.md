# Rewards Bing Script
O Rewards Bing Script (RBS), é um script de execução em lote, para abrir vários links com um pequeno delay entre cada link.

Para quem não conhece, o Microsoft Rewards é um projeto da Microsoft, onde o usuário acumula pontos que podem ser trocados por dinheiro, por produtos da empresa ou podem ser doados.

Acontece que um dos desafios semanais do Microsoft Rewards, consiste em navegar por 50 buscas no Bing, e foi através disso que surgiu a ideia desse script.

## Recursos

- Script que contém 50 buscas no Bing
- A cada busca, um delay de 2 segundos
- A cada 10 buscas, uma pausa no script para não sobrecarregar a memória RAM ou o navegador
- Script feito com linguagem para Batch (Windows) e Shell Script (Unix-Like, como Macintosh e distros Linux)
- Abaixo um detalhamento sobre cada versão do script:

Nome do Script  | Extensão | Descrição
------------- | ------------- | -------------
linux_gnome-open | sh | Script para distribuições com base no GNOME
linux_open | sh | Script que usa o comando padrão open
linux_python | sh |  Script que usa python para abrir o navegador padrão
linux_xdg | sh |  Script que usa XDG (X Development Group, antigo Free Desktop)
macintosh | sh |  Script que usa o comando padrão open
windows | bat |  Batch que utiliza o Microsoft Edge

## Como usar

1. Acesse a pasta source na raiz desse projeto do GitHub
2. Baixe a versão para seu Sistema Operacional
3. No navegador padrão do seu S.O., faça login com sua conta do HotMail / Outlook / Microsoft (se você utiliza o Windows, leia a Observação abaixo)
4. Certifique-se ao acessar o Bing, que sua conta está logada
5. Execute o script com duplo clique ou se seu S.O. não tiver suporte a duplo clique em script, execute via Terminal, por exemplo:
```
$> cd pasta-do-download
$> sh linux_open.sh
```

**Obs.:** A versão de Windows, roda exclusivamente em cima do Microsoft Edge, então deixe sua conta logada nesse navegador
