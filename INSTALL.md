
- Install docker & docker-compose

 2010  git clone https://gitlab.com/alabarga/vector-search-engine-workshop.git
 2011  udo apt-get remove docker docker-engine docker.io containerd runc
 2012  sudo apt-get remove docker docker-engine docker.io containerd runc
 2013  sudo apt-get install docker-ce docker-ce-cli containerd.io
 2014  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
 2015  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
 2016  sudo apt-get update
 2017  sudo apt-get install docker-ce docker-ce-cli containerd.io
 2018  sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

- make build
- make run
- http://localhost:5000/docs#

- Update nodejs: https://heynode.com/tutorial/install-nodejs-locally-nvm/
