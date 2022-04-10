# ConkyTiles
Rectangular Conky widgets for weather, news, financial and basic system info.

Instructions:

1) Make sure conky, curl, jq and awk are installed in your system.

2) Copy the conky files from this repository into ~/.conky/tiles folder.

3) Insert the following lines into ~/.conky/conky-startup.sh:

   cd "/home/nacho/.conky/tiles"\
   conky -c "/home/nacho/.conky/tiles/time" &\
   conky -c "/home/nacho/.conky/tiles/weather" &\
   conky -c "/home/nacho/.conky/tiles/cpu" &\
   conky -c "/home/nacho/.conky/tiles/network" &\
   conky -c "/home/nacho/.conky/tiles/stocks" &\
   conky -c "/home/nacho/.conky/tiles/news" &

4) Run ~/.conky/conky-startup.sh
