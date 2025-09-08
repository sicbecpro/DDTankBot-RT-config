DDTankBot RT (config importável)

1) Coloque seus recortes de templates em assets/:
   - assets/player_template.png (seu boneco)
   - assets/oponente_template.png (ícone do oponente)

2) Ajuste parâmetros em config/config.json.

3) Para compilar no Windows (WSL):
   - Instale WSL e Ubuntu
   - sudo apt update && sudo apt upgrade -y
   - sudo apt install python3-pip python3-dev build-essential git ffmpeg libsdl2-dev -y
   - pip install --upgrade buildozer
   - cd /mnt/c/SEU/CAMINHO/DDTankBot-RT-config
   - buildozer android debug deploy run

4) Abra o app junto com o jogo, clique em "Iniciar tempo real".
