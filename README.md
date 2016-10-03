# Odoo 9
Instalação do Odoo 9.0 no Ubuntu 14.04


Baixar o script
> sudo git clone https://github.com/bilibidum/odoo9.git

Entrar no diretório
> cd Odoo9.0

Dar permissão para execução
> sudo chmod +x odoo_install.sh

Executar o script
> sudo sh odoo_install.sh

Redirecionar porta 8069 -> 80
> iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-port 8069


by Rafael
