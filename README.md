# Instalar VPSMANAGER e atualizar os pacotes do sistema:

apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/nexyssh/VPSMANAGER-FULL/master/Plus && chmod 777 Plus && ./Plus


# Acessar root do seu sistema:

wget https://raw.githubusercontent.com/nexyssh/VPSMANAGER-FULL/master/senharoot.sh && chmod 777 senharoot.sh && ./senharoot.sh
