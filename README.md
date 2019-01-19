# Instalar Spotify en Cualquier GNU/linux
Aqui muestro como instalar Spotify en cual quier distribucion Linux
# Paquete Debian
Spotify para linux tambien lanza como un paquete Debian.
El objetivo de Spotify es que la comunidad se expanda.
Instrucciones de instalacion
# Paquetes Externernos
  dirmngr para instalarlo 
  apt update 
  apt install dirmngr 
  
# 1. Agregue las claves de firma del repositorio de Spotify para poder verificar los paquetes descargados
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 931FF8E79F0876134EDDBDCCA87FF9DF48BF1C90

# 2. Agregue el repositorio
echo deb http://repository.spotify.com stable non-free | sudo tee /etc/apt/sources.list.d/spotify.list

# 3. Actualizar la lista de repositorios
sudo apt update

# 4. Instalar Spotify-client
sudo apt install spotify-client
