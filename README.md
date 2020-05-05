# fusionpbx-convert-recordings
This script will convert all call recordings from "yesterday" from the default WAV format to OPUS encoded .ogg files.

Script requires "ffmpeg" to handle the actual file conversion.  

Quick install as root:

apt-get -y install ffmpeg

cd /etc/cron.daily

wget https://raw.githubusercontent.com/StratoSwitch/fusionpbx-convert-recordings/master/fusionpbx-convert-recordings

chmod +x fusionpbx-convert-recordings


