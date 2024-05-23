# use this for mqtt client 
nix-shell -p mqttx --command mqttx

# generate ./config/password by running `mosquitto_passwd -c /mosquitto/config/password user` from within the container
