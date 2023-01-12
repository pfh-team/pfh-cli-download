# PFH Command Line Interface
Interface de linha de comandos do Prezão Free Hack

## Sistemas Operacionais
<p>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Unofficial_Windows_logo_variant_-_2002%E2%80%932012_%28Multicolored%29.svg/170px-Unofficial_Windows_logo_variant_-_2002%E2%80%932012_%28Multicolored%29.svg.png" width="80" height="80" />
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" width="80" height="80" />
<img src="https://logos-download.com/wp-content/uploads/2020/06/Apple_Mac_OS_Logo.png" width="80" height="80" />
</p>

## Informações
Baixe https://prezaofreehack-api.herokuapp.com/v2/assets/pfh-cli.zip
<br>
Criado por ```PFH Team```
<br>
Versão ```1.0.5```

## Requerimentos
Java Virtual Machine (JVM)

## Configure
Adicione o caminho da pasta ```pfh``` na variável de ambiente ```PATH``` e no Unix-like dê a permissão de executar arquivos binários para a pasta ```pfh``` executando o comando ```chmod +x {PFH_DIR}```

## Execute
Use o comando ```pfh``` para mostrar as opções disponíveis

## Uso
### Opções Principais
Entrar na conta ```pfh login {NUMERO_DE_TELEFONE}```
<br>
Sair na conta ```pfh logout```
<br>
Gerar moedas ```pfh generate```
<br>
### Opções de UIDs Permitidos
Mostrar UIDs da lista de permitidos ```pfh alloweduids```
<br>
Adicionar UID na lista de permitidos ```pfh alloweduids:add {ID_DE_USUARIO}```
<br>
Remover UID da lista de permitidos ```pfh alloweduids:remove {ID_DE_USUARIO}```
<br>
Limpar UIDs da lista de permitidos ```pfh alloweduids:clear```
