fps_max 321


mat_postprocess_enable 0


r_shadows 0


fog_enable 0


mat_motion_blur_enabled 0


mat_queue_mode 2


r_dynamic 0


cl_forcepreload 1


mat_vsync 0


m_rawinput 1


m_customaccel 0









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









bind "F4" "cl_viewmodelfovsurvivor 180"
bind "F3" "cl_viewmodelfovsurvivor 85"











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














// default crosshair

cl_crosshair_alpha 255
cl_crosshair_blue 220
cl_crosshair_dynamic 1
cl_crosshair_green 182
cl_crosshair_red 138 
cl_crosshair_thickness 2












------------------YisusCL Glows---------------
cl_glow_item_r 1; cl_glow_item_g 1; cl_glow_item_b 0.2"

cl_glow_item_far_r 1; cl_glow_item_far_g 1; cl_glow_item_far_b 1"

cl_glow_thirdstrike_item_r 1; cl_glow_thirdstrike_item_g 1; cl_glow_thirdstrike_item_b 1"

cl_glow_ghost_infected_r 1; cl_glow_ghost_infected_g 1; cl_glow_ghost_infected_b 1"

cl_glow_infected_r 0; cl_glow_infected_g 0; cl_glow_infected_b 1"

cl_witch_glow_idle_r 1; cl_witch_glow_idle_g 0.2; cl_witch_glow_idle_b 1"

cl_witch_glow_angry_r 0; cl_witch_glow_angry_g 1; cl_witch_glow_angry_b 0"

cl_glow_ability_r 1; cl_glow_ability_g 1; cl_glow_ability_b 0.2"

cl_glow_survivor_hurt_r 1; cl_glow_survivor_hurt_g 0; cl_glow_survivor_hurt_b 0"

cl_glow_survivor_health_high_r 0; cl_glow_survivor_health_high_g 1; cl_glow_survivor_health_high_b 0"

cl_glow_survivor_health_med_r 0.80; cl_glow_survivor_health_med_g 1; cl_glow_survivor_health_med_b 0.015"
 
cl_glow_survivor_health_low_r 0.807; cl_glow_survivor_health_low_g 0.419; cl_glow_survivor_health_low_b 0.027"

cl_glow_survivor_health_crit_r 1; cl_glow_survivor_health_crit_g 0.015; cl_glow_survivor_health_crit_b 0.015"

cl_glow_survivor_r 0; cl_glow_survivor_g 1; cl_glow_survivor_b 0"

cl_glow_infected_vomit_r 0.6; cl_glow_infected_vomit_g 0.2; cl_glow_infected_vomit_b 1"

cl_glow_survivor_vomit_r 0.592; cl_glow_survivor_vomit_g 0.2; cl_glow_survivor_vomit_b 1"

cl_glow_survivor_health_bleed_pulse 1
 
cl_glow_survivor_health_bleed_pulse_amount 1
 
cl_glow_survivor_health_bleed_pulse_speed 30
 
cl_glow_survivor_health_include_buffer 1













	











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










