# ConkyTiles
Rectangular Conky widgets for weather, news, financial and basic system info.

Instructions:

1) Make sure conky, whois, curl, jq and awk are installed in your system.

2) Copy the conky files from this repository into ~/.conky/tiles folder.

3) Insert the following lines into ~/.conky/conky-startup.sh:

   conky -c ~/.conky/tiles/time &\
   conky -c ~/.conky/tiles/weather &\
   conky -c ~/.conky/tiles/cpu &\
   conky -c ~/.conky/tiles/network &\
   conky -c ~/.conky/tiles/stocks &\
   conky -c ~/.conky/tiles/news &

4) Run ~/.conky/conky-startup.sh
