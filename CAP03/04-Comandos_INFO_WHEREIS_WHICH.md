# CAP 03.04 Comandos `infos` | `whereis` | `which`

* **INFO** - São as paginas dos manuais nativos do Linux
```bash
info <comando>
# OU
info
```
`OBS:` o COMANDO yelp, é uma alternativa para ver o menual do Linux na interface grafica

* **WHEREIS** - Mostra a localização dos Binarios, os arquivos de configuração e o diretorio em que está.

```bash
whereis <Comando que deseja procurar>

# PARAMETROS

#localizar bionarios (-b)
whereis -b gunzip

#localizar os arquivos de configuração
whereis -m false
```
* **WHICH** -  Ele só mostra os binarios, mesma sintae  