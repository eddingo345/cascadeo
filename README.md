# cascadeo
wget -q -O cascadia.sh https://api.nodes.guru/cascadia.sh && chmod +x cascadia.sh && /bin/bash cascadia.sh
source $HOME/.bash_profile
cascadiad keys add wallet
cascadiad address-converter $(cascadiad keys show wallet -a)
