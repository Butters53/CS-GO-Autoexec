# CS-GO-Autoexec
CS:GO Autoexec


//Autoexec file by Butters53

//Rates
rate "1048576"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0"
cl_interp_ratio "1"
cl_lagcompensation "1"								
cl_predictweapons 		"1"
clientport 			"1337"

//Audio
volume "0.2"
voice_enable "1"
voice_scale "1"
windows_speaker_config "1"
snd_musicvolume "0"
snd_mixahead "0.05"
snd_headphone_pan_exponent "2"
snd_headphone_pan_radial_weight "2"
snd_legacy_surround "0"
snd_mute_losefocus "1"
lobby_voice_chat_enabled "0"


//Video
mat_monitorgamma "2.1"
mat_queue_mode "-1"
fps_max "121"
fps_max_menu "121"
r_dynamic "1"
r_drawtracers_firstperson "1"
r_drawparticles "1"
mat_savechanges //write settings to registry"


//Mouse
sensitivity "1.6"
zoom_sensitivity_ratio_mouse "1"
m_rawinput "1"
m_customaccel "0"
m_mouseaccel1 "0"
m_mouseaccel2 "0"


//Misc
developer "1"
con_enable "1"
con_filter_enable "1"
con_filter_text "Damage"
con_filter_text_out "Player:"
ui_steam_overlay_notification_position "bottomright"
player_nevershow_communityservermessage "1"
mm_dedicated_search_maxping "100"
mm_dedicated_force_servers ""
gameinstructor_enable "0"
option_duck_method "0"
option_speed_method "0"
cl_forcepreload "1"
cl_downloadfilter "nosounds"
cl_disablehtmlmotd "1"
cl_autohelp "0"
cl_showhelp "0"
cl_disablefreezecam "1"
cl_teammate_colors_show "1"
cl_autowepswitch "1"
cl_use_opens_buy_menu "0"
closeonbuy "0"
hud_takesshots "1"


//HUD
hud_scaling "0.7"
hud_showtargetid "1"
cl_draw_only_deathnotices "1"
cl_righthand "1"
cl_showloadout "1"
cl_showpos "0"
cl_showfps "0"
net_graph "0"
net_graphproportionalfont "1"
viewmodel_presetpos "0"
cl_bobcycle "0.98"

// repositions the gunmodel TO mimic CSS more closely.
viewmodel_fov "65"
viewmodel_offset_x "2"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"

// removes the shifting of the arm WHEN crouching down.
cl_viewmodel_shift_left_amt "0"
cl_viewmodel_shift_right_amt "0"

// removes the bobbing of the weapon back AND forth, WHEN you run.
cl_bob_lower_amt "0"
cl_bobamt_lat "0"
cl_bobamt_vert "0"




//Keybinds
bind kp_slash ""
bind kp_multiply ""
bind kp_minus ""
bind kp_home "buy bizon"
bind kp_uparrow "buy p90"
bind kp_pgup "buy deagle"
bind kp_leftarrow "buy famas;buy galilar"
bind kp_5 "buy m4a1;buy ak47"
bind kp_rightarrow "buy awp"
bind kp_end ""
bind kp_downarrow ""
bind kp_pgdn ""
bind kp_ins ""
bind kp_del ""
bind kp_plus ""
bind kp_enter ""

//Net Graph (Makes netgraph appear while pressing Tab)
alias "+ng" "+showscores; net_graph 1; net_graphpos 2"
alias "-ng" "-showscores; net_graph 0"
bind "TAB" "+ng"
net_graphheight "0"
net_graphpos "2"
net_graphproportionalfont "0"

//Radar
cl_radar_always_centered "1"
cl_radar_rotate "1"
cl_radar_scale "0.38"
cl_radar_icon_scale_min "0.4"


//Crosshair 
cl_crosshair_drawoutline "1"
cl_crosshair_dynamic_maxdist_splitratio "0.35"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.5"
cl_crosshair_dynamic_splitdist "7"
cl_crosshair_outlinethickness "1"
cl_crosshairalpha "255"
cl_crosshaircolor "4"
cl_crosshaircolor_b "50"
cl_crosshaircolor_g "250"
cl_crosshaircolor_r "50"
cl_crosshairdot "0"
cl_crosshairgap "-1"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairscale "0"
cl_crosshairsize "3"
cl_crosshairstyle "4"
cl_crosshairthickness "0.500000"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "0"


// CONSOLE
cl_showfps			"1"


//HUD
net_graphproportionalfont 	"0"
net_graphheight 		"0"
hud_scaling 			"0.6"
hud_showtargetid 		"1"
cl_autowepswitch 		"0"




host_writeconfig
echo ""
echo ""
echo "autoexec.cfg loaded"
echo ""
echo ""
