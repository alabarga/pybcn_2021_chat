
- Install docker & docker-compose

- git clone https://gitlab.com/alabarga/vector-search-engine-workshop.git

- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
- echo   "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
 -  sudo apt-get update
 -  sudo apt-get install docker-ce docker-ce-cli containerd.io
-  sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

- make build
- make run
- http://localhost:5000/docs#

- Update nodejs: https://heynode.com/tutorial/install-nodejs-locally-nvm/


https://github.com/opennmt/
https://github.com/LibreTranslate/LibreTranslate
