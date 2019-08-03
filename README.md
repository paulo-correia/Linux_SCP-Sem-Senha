# SCP Sem Senha

Requisitos básicos:

Criação de chaves do SSH sem senha [aqui](https://github.com/paulo-correia/Linux_SSH-Sem-Senha)

Tendo criado as chaves, na máquina cliente digite como **root** ou usuário:

 `scp -i /root/id_rsa.pub arquivo1 arquivo2 ... root@servidor:/caminho/arquivo renomeado1 ou troque o root pelo usuário/.ssh`

**Obs:** Pode se transferir um único ou vários aquivos.

 </div></div>
