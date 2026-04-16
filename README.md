fps_max 321


mat_postprocess_enable 0


r_shadows 0


fog_enable 0


mat_motion_blur_enabled 0


mat_queue_mode 2


r_dynamic 0


cl_forcepreload 1


mat_vsync 0









mat_setvideomode 2560 1440 1
mat_setvideomode 2560 1440 0










// Font

reloadfont "mat_setvideomode 2560 1440 1; mat_setvideomode 2560 1440 0"

reloadfont








net_graphheight 60 - change height
net_graphproportionalfont 1 - change size
net_graphpos 330 - change position








sensitivity 1.8







mat_monitorgamma 1.6

mat_monitorgamma_tv_enabled 1








fov_desired 105.239998






alias views_24 "echo " 24 viewmodelfovsurvivor ";cl_viewmodelfovsurvivor 24 ;alias changeview views_75"
alias views_75 "echo " 75 viewmodelfovsurvivor ";cl_viewmodelfovsurvivor 75 ;alias changeview views_24"
alias changeview "views_75"
bind "F3" "changeview"





bind "F4" "cl_viewmodelfovsurvivor 180"








bind "l" "record fix; stop"

bind "DOWNARROW" "cl_crosshair_dynamic 0"

bind "LEFTARROW" "cl_crosshair_dynamic 1"

bind "F8" "toggleconsole"

bind "F9" "openserverbrowser"    // F9 Buscador de servidores.

bind f10 disconnect

bind "Mouse5" "say_team !tank"

bind "Mouse4" "say_team !mvp"

bind "o" "say_team !bonus"

bind "u" "say_team Go Go Go!"

bind "i" "say_team >HELP<"







bind tab "+showscores_custom"
alias "+showscores_custom" "+showscores;net_graph 3";
alias "-showscores_custom" "-showscores;net_graph 1";










//NETWORKING

rate                                            "127000"
cl_cmdrate                                      "127"
cl_updaterate                                   "127"
cl_interp                                       "0.0167"  
cl_interp_ratio                                 "0"
sv_minrate                                      "25000"             
sv_mincmdrate                                   "93"             
sv_maxcmdrate                                   "127"             
sv_maxrate                                      "127000"














// pink crosshair

cl_crosshair_red 238 ;
cl_crosshair_green 138;
cl_crosshair_blue 238
cl_crosshair_thickness "4"























	











//BunnyHop Scroll

bind "MWHEELUP" "+jump"
bind "MWHEELDOWN" "+jump"
bind "SPACE" "+jump"









//IMPUT LAG KEYS//

bind w +mfwd
bind s +mback
bind a +mleft
bind d +mright
bind "e" "+use"
bind "MOUSE1" "+attack"
bind "MOUSE2" "+attack2"


alias +mfwd "-back;+forward;alias checkfwd +forward"
alias +mback "-forward;+back;alias checkback +back"
alias +mleft "-moveright;+moveleft;alias checkleft +moveleft"
alias +mright "-moveleft;+moveright;alias checkright +moveright"
alias -mfwd "-forward;checkback;alias checkfwd;"
alias -mback "-back;checkfwd;alias checkback;"
alias -mleft "-moveleft;checkright;alias checkleft;"
alias -mright "-moveright;checkleft;alias checkright;"
alias checkfwd; 
alias checkback; 
alias checkleft; 
alias checkright;










