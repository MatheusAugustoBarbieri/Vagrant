COMANDS VAGRANT:

vagrant version

vagrant init hashicorp/bionic64

vagrant up

vagrant up "maquina que quer subir"

vagrant status

vagrant status "maquina que quer ver"

vagrant halt

vagrant suspend

vagrant ssh

vagrant reload

vagrant destroy

vagrant destroy -f "maquina que quer destruir"

vagrant ssh-config

vagrant provision

"é gerada uma pasta ssh assim que a VM é criada"

vagrant destroy -f && vagrant up

multimachine{
tem que apontar a maquina q quer acessar "vagrant ssh mysql"
}

COMANDS LINUX:

ls

ls -a

cd

mkdir

pwd

cat

ssh -p 'porta' 'ip'

clear

netstat -lntp

curl http://localhost:80

ifconfig

ping 'ip'

exit

ssh

ssh-keygen -t rsa

cp

cp 'arquivo' 'caminho onde quer colar'

cat 'chavePublica' >> authorized_keys

ssh -i 'chavePrivada' vagrant@ip

<!-- joga o arquivo do mysql pro nosso SO -->

cat /etc/mysql/mysql.conf.d/mysqld.cnf >> /configs/mysqld.cnf
e altera bind-address para = 0.0.0.0

INSTALADOS:
nginx: sudo apt-get install -y nginx
