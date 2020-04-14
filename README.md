# bitbucket_config
step by step automatic configuration for bitbucket ssh keys generation 

a) via git bash, executar comandos:
git clone https://gist.github.com/3442828a038fbbf5c4b7.git ~/gitdotfiles
cd ~/gitdotfiles
sh install.sh -f

b) durante a execução acima será necessário informar seu nome email, logo após a conclusão execute mais estes comandos:
ssh-keygen #pressionar enter em todos os pontos de parada até o comando ser concluído
cat ~/.ssh/id_rsa.pub | clip

c) o último comando irá copiar a chave ssh para a área de transferência do windows, agora basta colar esta chave na conta do bitbucket, seguindo os passos abaixo:
i: acesse o link: https://bitbucket.org/account/user/[seu_usuário_cit]/ssh-keys/
ii: acionar comando Add Key
iii: colar o texto do clipboard no campo key
iv: confirmar adição.
