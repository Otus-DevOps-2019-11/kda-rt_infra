# kda-rt_infra
kda-rt Infra repository

#cloud-bastion
подключение в одну команду :
ssh -i ~/.ssh/appuser appuser@35.208.144.51 -A "ssh 10.128.0.3" -T

Можно создать альяс:
alias connect_internal='ssh -i ~/.ssh/appuser appuser@35.208.144.51 -A "ssh 10.128.0.3" -T'

bastion_IP = 35.208.144.51
someinternalhost_IP = 10.128.0.3