# generate-wireguard-keys bash script

Simple bash script I made to generate Wireguard client keys and configs for use with the wg-quick Linux utility

The script specifically made for use with wg-quick, however the keys themselves should be able to be used with any Wireguard client/server

Parameters for the wireguard server are defined in the wg_generator_server_settings, used for generating configs

Keys and configs are stored in the current working directory.

**Syntax**: generate-wireguard-keys [CLIENT_VPN_IP] [CLIENT_NAME] 

**[CLIENT_VPN_IP]** - The ip the client will have when connected to the Wireguard vpn

**[CLIENT_NAME]** - Human friendly name for the client for use in identifying it in the configs
