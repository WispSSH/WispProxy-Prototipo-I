# WispProxy-Prototipo-I

```
_ _ _ _ ____ ___    ___  ____ ____ _  _ _   _
| | | | [__  |__]   |__] |__/ |  |  \/   \_/    
|_|_| | ___] |      |    |  \ |__| _/\_   |
```

- Primeiro projeto experimental feito para checar os status dos proxys.
- Versão liberada gratuitamente.

## Instalação

Aplicativo Necessario (Android)

[Termux](https://play.google.com/store/apps/details?id=com.termux&hl=pt_BR&gl=US)

Termux (Instalador)

```bash
pkg update && pkg upgrade && pkg install python && pkg install git && pip install requests && pip install datetime && cd $home && mkdir WispProxy && git clone https://github.com/WispSSH/WispProxy-Prototipo-I.git WispProxy && cd WispProxy && rm README.md && python wispproxy.py
```

Dependencias

```bash
pip install requests
pip install datetime
```

Inicie o script com

```bash
python wispproxy.py
```

## Demonstrações

Menu Estilo

![image](https://user-images.githubusercontent.com/100727796/172061396-d688bf8f-e032-4823-84a6-d1fe844fa8ca.png)

## Funções

- Ip Range
- List Checker
- Subdomain Finder

## Como utilizar

- Ip Scanner (Necessita de dados sem internet)

Adicione um ip que na ultima casa esteja com .x e ele irá verificar todas as ocorrencias de 0 a 254.

- Lista Scanner (Necessita de dados sem internet)

Adicione uma lista de ip/hostname no arquivo lista.txt que o aplicativo irá verificar um por um.

- Subdominio (Necessita de internet)

Adicione um dominio desejado que ele retornara os valores no arquivo subdominio.txt

## Extra

- Script desenvolvido com a intenção de auxiliar na busca de proxys.
- Primeira versão feita, ignorem a lentidão e alguns erros que possam aparecer.
- Lembrando que não estou ganhando nada por ter feito e liberado o script.





