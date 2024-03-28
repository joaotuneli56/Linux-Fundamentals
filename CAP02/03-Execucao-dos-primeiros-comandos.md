# CAP 2.3 Execução dos primeiros comandos

 * **Tipos de Usuario**
    * `$` Usuario corrente/padrão , sem super permissões.
    Identificação é sempre 1000.

    * `#` Super Admin. Identificação é sempre 0

* Comandos para desligar a maquina:

```bash
shutdown -h now
# OU
halt -p 
# OU
poweroff
# OU
init 0
# Desliga a maquina daqui 10 minutos
shutdown -h 10
# Desliga a maquina 17:00
shutdown -h 17:00


```

* **Outros comandos uteis:**

    * Comando para alterar o nivel de usuario comum para super ususario

    ```bash
    sudo -i
    ```

    * Comando para saber qual usuario está utilizando
    ```bash
    whoami
    ``` 

    * 




