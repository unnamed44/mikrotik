# mikrotik





scp -P 4422 id_rsa.pub admin@10.0.43.254:box-id_rsa.pub
ssh -p 4422 admin@10.0.43.254 'user ssh-keys import user=admin public-key-file=box-id_rsa.pub'


