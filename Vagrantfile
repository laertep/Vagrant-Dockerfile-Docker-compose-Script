Vagrant.configure("2") do |config|
  config.vm.provider = "virtualbox" do |v|
    v.name = "desafio05"
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "public_network"
  config.vm.synced_folder "./nginx-desafio05", "/home/vagrant"
  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get update
    sudo apt-get install -y docker.io
    sudo docker build -t nginx-desafio05
    sudo docker run --name nginx -p 80:80 nginx-desafio05
  SHELL
  config.vm.provision "shell", path: "docker-compose.sh"
end
