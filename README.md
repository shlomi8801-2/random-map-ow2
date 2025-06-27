# random-map-ow2
add it in launch arguments of overwatch 2 in steam or anything that can run it as bash and it will give you random background each time you launch the game
### to install(currently only for linux):
```
#download the file randmapow2
chmod +x ./randmapow2
sudo cp /randmapow2 /usr/bin/randmapow2
```
### in steam:
goto ``overwatch 2`` right click on it then ``Properties... -> General -> LAUNCH OPTIONS`` and paste this inside
```
%command% $(randmapow2)
```
for example i use this as the launche options
```
PULSE_LATENCY_MSEC=60 mangohud %command% $(randmapow2)
```
#### Enjoy!
## Example:
![alt text](https://github.com/shlomi8801-2/random-map-ow2/blob/main/github%20random%20ow2%20backgroud.GIF)


[mangohud](https://github.com/flightlessmango/MangoHud)
