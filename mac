#codigo para obtener la Mac-del-esp32

Import network 
sta_if = network    .WLAN(network.STA_IF)
sta_if.active(True)
sta_mac = sta_if.config('mac')
mac_adrees = ':' . join('%02x' % b for b in sta_mac)
print('Direccion MAC:' ,mac_adrees)
