# Instalar Spotify en Cualquier linux
Aqui muestro como instalar Spotify en cual quier distribucion Linux
# Paquete Debian
Spotify para linux tambien lanza como un paquete Debian.
El objetivo de Spotify es que la comunidad se expanda.
Instrucciones de instalacion
# 1. Agregue las claves de firma del repositorio de Spotify para poder verificar los paquetes descargados
sudo apt-key adv --keyserver hkp: //keyserver.ubuntu.com: 80 --recv-keys 931FF8E79F0876134EDDBDCCA87FF9DF48BF1C90

# 2. Añadir el repositorio de Spotify
echo deb http://repository.spotify.com estable no libre | sudo tee /etc/apt/sources.list.d/spotify.list

# 3. Actualizar lista de paquetes disponibles
sudo apt-get update

# 4. Instalar Spotify
sudo apt-get install spotify-client

Es importante actualisar alfinal para que los repositorios de la distro se actualizen y encuentren la 
vercion mas reciente de la aplicacion

