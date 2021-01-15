09:17:02 Steam Console Client (c) Valve Corporation
09:17:02 -- type 'quit' to exit --
09:17:02 Loading Steam API...OK.
09:17:02 
09:17:03 Connecting anonymously to Steam Public...Logged in OK
09:17:03 Waiting for user info...OK
09:17:04 Success! App '740' already up to date.

09:17:05 @sSteamCmdForcePlatformType windows
09:17:05 "@sSteamCmdForcePlatformType" = "windows"
09:17:05 force_install_dir ../
09:17:05 app_update 740
09:17:05 quit
09:17:05 Redirecting stderr to 'D:\servers\csgo_297437\steamcmd\logs\stderr.txt'

09:17:05 Params: -game csgo -console -tickrate 128.00 -port 49525 +tv_port 49526 -maxplayers_override 16 -usercon -nowatchdog +sv_pure 0 +sv_lan 0 +ip 89.203.193.220 +game_type 0 +exec server.cfg +game_mode 1 +map de_dust2 +sv_setsteamaccount B74A031F37B9312A5EC65A15FC43AA0C -gamemodes_serverfile gamemodes_server.txt +mapgroup h_custom -condebug -norestart -allowdebug
09:17:06 #
09:17:06 #Console initialized.
09:17:06 #Using breakpad minidump system 740/13776.1219.DC
09:17:06 #Filesystem successfully switched to safe whitelist mode
09:17:06 #Game.dll loaded for "Counter-Strike: Global Offensive"
09:17:06 #CGameEventManager::AddListener: event 'server_pre_shutdown' unknown.
09:17:06 #CGameEventManager::AddListener: event 'game_newmap' unknown.
09:17:06 #CGameEventManager::AddListener: event 'finale_start' unknown.
09:17:06 #CGameEventManager::AddListener: event 'round_start' unknown.
09:17:06 #CGameEventManager::AddListener: event 'round_end' unknown.
09:17:06 #CGameEventManager::AddListener: event 'difficulty_changed' unknown.
09:17:06 #CGameEventManager::AddListener: event 'player_death' unknown.
09:17:06 #CGameEventManager::AddListener: event 'hltv_replay' unknown.
09:17:06 #CGameEventManager::AddListener: event 'player_connect' unknown.
09:17:06 #CGameEventManager::AddListener: event 'player_disconnect' unknown.
09:17:06 #GameTypes: missing mapgroupsSP entry for game type/mode (custom/custom).
09:17:06 #GameTypes: missing mapgroupsSP entry for game type/mode (cooperative/cooperative).
09:17:06 #GameTypes: missing mapgroupsSP entry for game type/mode (cooperative/coopmission).
09:17:06 Seeded random number generator @ 1064343566 ( 0.940 )
09:17:06 Failed to load gamerulescvars.txt, game rules cvars might not be reported to management tools.
09:17:06 Server is hibernating
09:17:06 No web api auth key specified - workshop downloads will be disabled.
09:17:06 scripts\talker\response_rules.txt(token 3685) : Multiple definitions for criteria 'tlk_cw.regroup' [-1793082848]
09:17:06 scripts\talker\swat.txt(token 1688) : response entry 'radio.sticktogetherswat' with unknown command 'scenes/swat/radiobotregroup02.vcd'
09:17:06 scripts\talker\coopvoice.txt(token 657) : No such response 'guardianroundstartintro' for rule 'guardianroundintro'
09:17:06 Discarded rule guardianroundintro
09:17:06 CResponseSystem:  scripts\talker\response_rules.txt (4154 rules, 763 criteria, and 3878 responses)
09:17:06 Plugins: found file "CSay.vdf"
09:17:06 eBot LOADED
09:17:06 Plugins: found file "metamod.vdf"
09:17:06 maxplayers set to 64
09:17:06 Fast Build Temp Cache:  'maps/soundcache/_master.cache'

09:17:07 Elapsed time:  0.00 seconds
09:17:07 ConVarRef cl_embedded_stream_video_playing doesn't point to an existing ConVar
09:17:07 Execing config: valve.rc
09:17:07 Execing config: default.cfg
09:17:07 Unknown command "cl_bobamt_vert"
09:17:07 Unknown command "cl_bobamt_lat"
09:17:07 Unknown command "cl_bob_lower_amt"
09:17:07 Unknown command "cl_viewmodel_shift_left_amt"
09:17:07 Unknown command "cl_viewmodel_shift_right_amt"
09:17:07 Unknown command "cl_teamid_min"
09:17:07 Unknown command "cl_teamid_max"
09:17:07 Unknown command "cl_teamid_overhead"
09:17:07 Unknown command "cl_teamid_overhead_maxdist"
09:17:07 Execing config: joystick.cfg
09:17:07 Execing config: autoexec.cfg
09:17:07 --------------------------------------------------------
09:17:07 sv_pure set to 0.
09:17:07 --------------------------------------------------------
09:17:07 Execing config: server.cfg
09:17:07 Unknown command "sv_maxcmdrate"
09:17:07 Unknown command "sv_vote_creation_time"
09:17:07 Writing cfg/banned_user.cfg.
09:17:07 Writing cfg/banned_ip.cfg.
09:17:07 Execing config: banned_user.cfg
09:17:07 Execing config: banned_ip.cfg
09:17:07 Unknown command "allow_spectators"
09:17:07 Setting mapgroup to 'h_custom'
09:17:07 Execing config: modsettings.cfg
09:17:07 NET_CloseAllSockets
09:17:07 NET_GetBindAddresses found 89.203.193.220: 'HP FlexFabric 10Gb 2-port 554FLB Adapter #2'
09:17:07 WARNING: UDP_OpenSocket: unable to bind socket
09:17:07 Network: IP 89.203.193.220 mode MP, dedicated No, ports 49525 SV / -1 CL
09:17:07 L 01/15/2021 - 09:17:07: [SM] Error encountered parsing core config file: Line contained too many invalid tokens
09:17:07 CServerGameDLL::ApplyGameSettings game settings payload received:
09:17:07   ::ExecGameTypeCfg {
09:17:07     map {
09:17:07       mapname de_dust2
09:17:07     }
09:17:07   }
09:17:07 ApplyGameSettings: Invalid mapgroup name h_custom
09:17:07 ---- Host_NewGame ----
09:17:07 Execing config: game.cfg
09:17:07 Switching filesystem to allow files loaded from disk (sv_pure_allow_loose_file_loads = 1)
09:17:08 DISP_VPHYSICS found bad displacement collision face (252.50 1542.13 147.50) (250.00 1543.00 155.00) (250.00 1543.50 155.00) at tri 25
09:17:08 DISP_VPHYSICS entire displacement vdisp_0290 will have no collision, dimensions (6.00 14.00 32.00) from (249.00 1537.00 124.00) to (255.00 1551.00 156.00)
09:17:08 DISP_VPHYSICS found bad displacement collision face (250.13 1539.50 147.50) (249.75 1543.00 155.00) (250.00 1543.00 155.00) at tri 30
09:17:08 DISP_VPHYSICS entire displacement vdisp_0291 will have no collision, dimensions (12.50 7.00 32.00) from (242.00 1537.00 124.00) to (254.50 1544.00 156.00)
09:17:08 DISP_VPHYSICS found bad displacement collision face (-1884.00 704.30 159.97) (-1884.00 703.00 180.00) (-1884.54 704.60 160.25) at tri 6
09:17:08 DISP_VPHYSICS entire displacement vdisp_1842 will have no collision, dimensions (2.54 6.60 82.03) from (-1885.54 699.00 158.97) to (-1883.00 705.60 241.00)
09:17:08 DISP_VPHYSICS found bad displacement collision face (-1884.00 705.40 127.95) (-1884.00 704.30 159.97) (-1884.54 704.60 160.25) at tri 30
09:17:08 DISP_VPHYSICS entire displacement vdisp_1876 will have no collision, dimensions (2.54 8.30 130.25) from (-1885.54 699.00 31.00) to (-1883.00 707.30 161.25)

09:17:11 Host_NewGame on map de_dust2
09:17:11 L 01/15/2021 - 09:17:11: -------- Mapchange to de_dust2 --------
09:17:11 L 01/15/2021 - 09:17:11: [SM] Failed to load plugin "gloves.smx": Unable to load plugin (no debug string table).
09:17:11 L 01/15/2021 - 09:17:11: [SM] Failed to load plugin "weapons.smx": Unable to load plugin (no debug string table).
09:17:11 CGameEventManager::AddListener: event 'teamplay_win_panel' unknown.
09:17:11 CGameEventManager::AddListener: event 'teamplay_restart_round' unknown.
09:17:11 CGameEventManager::AddListener: event 'arena_win_panel' unknown.

09:17:11 GameTypes: initializing game types interface from GameModes.txt.
09:17:11 GameTypes: merging game types interface from gamemodes_server.txt.
09:17:11 Failed to load gamemodes_server.txt
09:17:11 GameTypes: missing mapgroupsSP entry for game type/mode (custom/custom).
09:17:11 GameTypes: missing mapgroupsSP entry for game type/mode (cooperative/cooperative).
09:17:11 GameTypes: missing mapgroupsSP entry for game type/mode (cooperative/coopmission).
09:17:11 ammo_grenade_limit_default - 1
09:17:11 ammo_grenade_limit_flashbang - 1
09:17:11 ammo_grenade_limit_total - 3
09:17:11 ammo_item_limit_healthshot - 4
09:17:11 bot_allow_grenades - 1
09:17:11 bot_allow_machine_guns - 1
09:17:11 bot_allow_pistols - 1
09:17:11 bot_allow_rifles - 1
09:17:11 bot_allow_rogues - 1
09:17:11 bot_allow_shotguns - 1
09:17:11 bot_allow_snipers - 1
09:17:11 bot_allow_sub_machine_guns - 1
09:17:11 bot_autodifficulty_threshold_high - 5.0
09:17:11 bot_autodifficulty_threshold_low - -2.0
09:17:11 bot_chatter - normal
09:17:11 bot_coop_idle_max_vision_distance - 1400
09:17:11 bot_defer_to_human_goals - 0
09:17:11 bot_defer_to_human_items - 1
09:17:11 bot_difficulty - 1
09:17:11 bot_max_hearing_distance_override - -1
09:17:11 bot_max_visible_smoke_length - 200
09:17:11 bot_max_vision_distance_override - -1
09:17:11 bot_quota - 10
09:17:11 bot_quota_mode - normal
09:17:11 bot_coop_idle_max_vision_distance - 1400
09:17:11 bot_max_vision_distance_override - -1
09:17:11 bot_max_hearing_distance_override - -1
09:17:11 bot_coopmission_dz_engagement_limit - missing cvar specified in bspconvar_whitelist.txt
09:17:11 cash_player_bomb_defused - 300
09:17:11 cash_player_bomb_planted - 300
09:17:11 cash_player_damage_hostage - -30
09:17:11 cash_player_get_killed - 0
09:17:11 cash_player_interact_with_hostage - 150
09:17:11 cash_player_killed_enemy_default - 300
09:17:11 cash_player_killed_enemy_factor - 1
09:17:11 cash_player_killed_hostage - -1000
09:17:11 cash_player_killed_teammate - -300
09:17:11 cash_player_rescued_hostage - 1000
09:17:11 cash_player_respawn_amount - 0
09:17:11 cash_team_elimination_bomb_map - 3250
09:17:11 cash_team_elimination_hostage_map_ct - 2000
09:17:11 cash_team_elimination_hostage_map_t - 1000
09:17:11 cash_team_hostage_alive - 0
09:17:11 cash_team_hostage_interaction - 500
09:17:11 cash_team_loser_bonus - 1400
09:17:11 cash_team_loser_bonus_consecutive_rounds - 500
09:17:11 cash_team_planted_bomb_but_defused - 800
09:17:11 cash_team_rescued_hostage - 0
09:17:11 cash_team_survive_guardian_wave - 1000
09:17:11 cash_team_terrorist_win_bomb - 3500
09:17:11 cash_team_win_by_defusing_bomb - 3250
09:17:11 cash_team_win_by_hostage_rescue - 3500
09:17:11 cash_team_win_by_time_running_out_bomb - 3250
09:17:11 cash_team_win_by_time_running_out_hostage - 3250
09:17:11 contributionscore_assist - 1
09:17:11 contributionscore_bomb_defuse_major - 3
09:17:11 contributionscore_bomb_defuse_minor - 1
09:17:11 contributionscore_bomb_exploded - 1
09:17:11 contributionscore_bomb_planted - 2
09:17:11 contributionscore_cash_bundle - 0
09:17:11 contributionscore_crate_break - 0
09:17:11 contributionscore_hostage_kill - -2
09:17:11 contributionscore_hostage_rescue_major - 3
09:17:11 contributionscore_hostage_rescue_minor - 1
09:17:11 contributionscore_kill - 2
09:17:11 contributionscore_kill_factor - 0
09:17:11 contributionscore_objective_kill - 3
09:17:11 contributionscore_suicide - -2
09:17:11 contributionscore_team_kill - -2
09:17:11 ff_damage_reduction_bullets - 0.1
09:17:11 ff_damage_reduction_grenade - 0.25
09:17:11 ff_damage_reduction_grenade_self - 1
09:17:11 ff_damage_reduction_other - 0.25
09:17:11 global_chatter_info - 
09:17:11 healthshot_healthboost_damage_multiplier - 1
09:17:11 healthshot_healthboost_speed_multiplier - 1
09:17:11 healthshot_healthboost_time - 0
09:17:11 inferno_child_spawn_max_depth - 4
09:17:11 inferno_max_flames - 16
09:17:11 inferno_max_range - 150
09:17:11 molotov_throw_detonate_time - 2.0
09:17:11 mp_afterroundmoney - 0
09:17:11 mp_anyone_can_pickup_c4 - 0
09:17:11 mp_autokick - 1
09:17:11 mp_autoteambalance - 1
09:17:11 mp_bot_ai_bt - 
09:17:11 mp_buy_allow_grenades - 1
09:17:11 mp_buy_allow_guns - 255
09:17:11 mp_buy_anywhere - 0
09:17:11 mp_buy_during_immunity - 0
09:17:11 mp_buytime - 90
09:17:11 mp_c4_cannot_be_defused - 0
09:17:11 mp_c4timer - 40
09:17:11 mp_consecutive_loss_max - 4
09:17:11 mp_coop_force_join_ct - 0
09:17:11 mp_coopmission_bot_difficulty_offset - 0
09:17:11 mp_coopmission_mission_number - 0
09:17:11 mp_coopmission_dz - missing cvar specified in bspconvar_whitelist.txt
09:17:11 mp_ct_default_grenades - 
09:17:11 mp_ct_default_melee - weapon_knife
09:17:11 mp_ct_default_primary - 
09:17:11 mp_ct_default_secondary - weapon_hkp2000
09:17:11 mp_retake_ct_loadout_default_pistol_round - 1|3;#GameUI_Retake_Card_4v3,0,0,secondary0|1;#GameUI_Retake_Card_FlashOut,0,0,secondary0,grenade2;#GameUI_Retake_Card_HideAndPeek,0,0,secondary0,grenade4
09:17:11 mp_retake_ct_loadout_upgraded_pistol_round - 2|2;#GameUI_Retake_Card_TakeFive,0,0,secondary3|2;#GameUI_Retake_Card_BlindFire,0,0,secondary2,grenade2|2;#GameUI_Retake_Card_OnlyTakesOne,0,0,secondary4|2;#GameUI_Retake_Card_SneakyBeakyLike,0,0,secondary2,grenade4
09:17:11 mp_retake_ct_loadout_light_buy_round - 3|2;#GameUI_Retake_Card_UmpInSmoke,1,1,smg2,grenade4|2;#GameUI_Retake_Card_FunNGun,1,1,smg0,grenade3|2;#GameUI_Retake_Card_Sharpshooter,1,1,rifle2,grenade2|2;#GameUI_Retake_Card_BurstBullpup,1,1,rifle0
09:17:11 mp_retake_ct_loadout_full_buy_round - 4|2;#GameUI_Retake_Card_LightEmUp,1,1,rifle1,grenade2|2;#GameUI_Retake_Card_Kobe,1,1,rifle1,grenade3|1;#GameUI_Retake_Card_1g,1,1,rifle1,grenade0|1;#GameUI_Retake_Card_DisappearingAct,1,1,rifle1,grenade4|1;#GameUI_Retake_Card_EyesOnTarget,1,1,rifle3
09:17:11 mp_retake_ct_loadout_bonus_card_availability - 1,2
09:17:11 mp_retake_ct_loadout_bonus_card - #GameUI_Retake_Card_TheAWPortunity,1,1,rifle4
09:17:11 mp_retake_ct_loadout_enemy_card - #GameUI_Retake_Card_BehindEnemyLines,1,1,rifle1,grenade2
09:17:11 mp_retake_t_loadout_default_pistol_round - 0|3;#GameUI_Retake_Card_4BadGuysLeft,0,0,secondary0|1;#GameUI_Retake_Card_LookAway,0,0,secondary0,grenade2;#GameUI_Retake_Card_WhenThereIsSmoke,0,0,secondary0,grenade4
09:17:11 mp_retake_t_loadout_upgraded_pistol_round - 0|2;#GameUI_Retake_Card_BlindFire,0,0,secondary2,grenade2|2;#GameUI_Retake_Card_QueOta,0,0,secondary4|1;#GameUI_Retake_Card_SmokeScreen,0,0,secondary2,grenade4|1;#GameUI_Retake_Card_TecTecBoom,0,0,secondary3,grenade3
09:17:11 mp_retake_t_loadout_light_buy_round - 0|2;#GameUI_Retake_Card_BackInAFlash,1,1,smg2,grenade2|2;#GameUI_Retake_Card_AllIn,1,1,rifle0|1;#GameUI_Retake_Card_BoomBox,1,1,smg0,grenade3,grenade4|1;#GameUI_Retake_Card_SetThemFree,1,1,rifle2,grenade2
09:17:11 mp_retake_t_loadout_full_buy_round - 0|2;#GameUI_Retake_Card_OlReliable,1,1,rifle1,grenade2|1;#GameUI_Retake_Card_SmokeShow,1,1,rifle1,grenade4|1;#GameUI_Retake_Card_HotShot,1,1,rifle1,grenade0|1;#GameUI_Retake_Card_EyeSpy,1,1,rifle3,grenade3
09:17:11 mp_retake_t_loadout_bonus_card_availability - 1,1,2
09:17:11 mp_retake_t_loadout_bonus_card - #GameUI_Retake_Card_TheAWPortunity,1,1,rifle4
09:17:11 mp_retake_t_loadout_enemy_card - #GameUI_Retake_Card_FindersKeepers,1,1,rifle1,grenade2
09:17:11 mp_retake_max_consecutive_rounds_same_target_site - 2
09:17:11 mp_damage_headshot_only - 0
09:17:11 mp_damage_scale_ct_body - 1.0
09:17:11 mp_damage_scale_ct_head - 1.0
09:17:11 mp_damage_scale_t_body - 1.0
09:17:11 mp_damage_scale_t_head - 1.0
09:17:11 mp_damage_vampiric_amount - 0
09:17:11 mp_death_drop_c4 - 1
09:17:11 mp_death_drop_defuser - 1
09:17:11 mp_death_drop_grenade - 2
09:17:11 mp_death_drop_gun - 1
09:17:11 mp_deathcam_skippable - 1
09:17:11 mp_default_team_winner_no_objective - -1
09:17:11 mp_defuser_allocation - 0
09:17:11 mp_display_kill_assists - 1
09:17:11 mp_dm_bonus_percent - 50
09:17:11 mp_dm_bonus_respawn - 0
09:17:11 mp_dm_bonusweapon_dogtags - 0
09:17:11 mp_dm_dogtag_score - 0
09:17:11 mp_dm_kill_base_score - 10
09:17:11 mp_dm_teammode - 0
09:17:11 mp_dm_teammode_bonus_score - 1
09:17:11 mp_dm_teammode_dogtag_score - 0
09:17:11 mp_dm_teammode_kill_score - 1
09:17:11 mp_dogtag_despawn_on_killer_death - 1
09:17:11 mp_dogtag_despawn_time - 120
09:17:11 mp_dogtag_pickup_rule - 0
09:17:11 mp_drop_grenade_enable - 0
09:17:11 mp_drop_knife_enable - 0
09:17:11 mp_economy_reset_rounds - 0
09:17:11 mp_equipment_reset_rounds - 0
09:17:11 mp_force_assign_teams - 0
09:17:11 mp_force_pick_time - 15
09:17:11 mp_forcecamera - 1
09:17:11 mp_free_armor - 0
09:17:11 mp_freezetime - 6
09:17:11 mp_friendlyfire - 0
09:17:11 mp_ggprogressive_round_restart_delay - 15.0
09:17:11 mp_ggtr_always_upgrade - 0
09:17:11 mp_ggtr_bomb_defuse_bonus - 1
09:17:11 mp_ggtr_bomb_detonation_bonus - 1
09:17:11 mp_ggtr_bomb_pts_for_flash - 4
09:17:11 mp_ggtr_bomb_pts_for_he - 3
09:17:11 mp_ggtr_bomb_pts_for_molotov - 5
09:17:11 mp_ggtr_bomb_pts_for_upgrade - 2.0
09:17:11 mp_ggtr_bomb_respawn_delay - 0.0
09:17:11 mp_ggtr_end_round_kill_bonus - 1
09:17:11 mp_ggtr_halftime_delay - 0.0
09:17:11 mp_ggtr_last_weapon_kill_ends_half - 0
09:17:11 mp_give_player_c4 - 1
09:17:11 mp_global_damage_per_second - 0.0
09:17:11 mp_guardian_bot_money_per_wave - 800
09:17:11 mp_guardian_force_collect_hostages_timeout - 50
09:17:11 mp_guardian_loc_icon - missing cvar specified in bspconvar_whitelist.txt
09:17:11 mp_guardian_loc_string_desc - 
09:17:11 mp_guardian_loc_string_hud - #guardian_mission_type_kills
09:17:11 mp_guardian_loc_weapon - 
09:17:11 mp_guardian_player_dist_max - 2000
09:17:11 mp_guardian_player_dist_min - 1300
09:17:11 mp_guardian_special_kills_needed - 10
09:17:11 mp_guardian_special_weapon_needed - awp
09:17:11 mp_guardian_target_site - -1
09:17:11 mp_guardian_force_collect_hostages_timeout - 50
09:17:11 mp_guardian_give_random_grenades_to_bots - 1
09:17:11 mp_guardian_ai_bt_difficulty_adjust_wave_interval - 1
09:17:11 mp_guardian_ai_bt_difficulty_max_next_level_bots - 3
09:17:11 mp_guardian_ai_bt_difficulty_cap_beginning_round - 2
09:17:11 mp_guardian_ai_bt_difficulty_initial_value - 2
09:17:11 mp_halftime - 0
09:17:11 mp_halftime_pausetimer - 0
09:17:11 mp_heavyassaultsuit_aimpunch - 1.0
09:17:11 mp_heavyassaultsuit_cooldown - 5
09:17:11 mp_heavyassaultsuit_deploy_timescale - 0.8
09:17:11 mp_heavyassaultsuit_speed - 130
09:17:11 mp_heavybot_damage_reduction_scale - 1.0
09:17:11 mp_hostagepenalty - 10
09:17:11 mp_hostages_max - 2
09:17:11 mp_hostages_spawn_force_positions - 
09:17:11 mp_hostages_spawn_same_every_round - 1
09:17:11 mp_items_prohibited - 
09:17:11 mp_limitteams - 2
09:17:11 mp_match_can_clinch - 1
09:17:11 mp_match_end_changelevel - 0
09:17:11 mp_max_armor - 2
09:17:11 mp_maxmoney - 16000
09:17:11 mp_maxrounds - 0
09:17:11 mp_molotovusedelay - 15.0
09:17:11 mp_only_cts_rescue_hostages - 1
09:17:11 mp_plant_c4_anywhere - 0
09:17:11 mp_playercashawards - 1
09:17:11 mp_radar_showall - 0
09:17:11 mp_randomspawn - 0
09:17:11 mp_randomspawn_dist - 0
09:17:11 mp_randomspawn_los - 1
09:17:11 mp_respawn_immunitytime - 4.0
09:17:11 mp_respawn_on_death_ct - 0
09:17:11 mp_respawn_on_death_t - 0
09:17:11 mp_respawnwavetime_ct - 10.0
09:17:11 mp_respawnwavetime_t - 10.0
09:17:11 mp_round_restart_delay - 7.0
09:17:11 mp_roundtime - 5
09:17:11 mp_roundtime_defuse - 0
09:17:11 mp_roundtime_hostage - 0
09:17:11 mp_solid_teammates - 1
09:17:11 mp_starting_losses - 0
09:17:11 mp_startmoney - 800
09:17:11 mp_suicide_penalty - 1
09:17:11 mp_t_default_grenades - 
09:17:11 mp_t_default_melee - weapon_knife
09:17:11 mp_t_default_primary - 
09:17:11 mp_t_default_secondary - weapon_glock
09:17:11 mp_tagging_scale - 1.0
09:17:11 mp_taser_recharge_time - -1
09:17:11 mp_teamcashawards - 1
09:17:11 mp_teammates_are_enemies - 0
09:17:11 mp_timelimit - 5
09:17:11 mp_use_respawn_waves - 0
09:17:11 mp_warmup_pausetimer - 0
09:17:11 mp_warmuptime - 30
09:17:11 mp_warmuptime_all_players_connected - 0
09:17:11 mp_weapon_self_inflict_amount - 0
09:17:11 mp_weapons_allow_heavy - -1
09:17:11 mp_weapons_allow_heavyassaultsuit - 0
09:17:11 mp_weapons_allow_map_placed - 0
09:17:11 mp_weapons_allow_pistols - -1
09:17:11 mp_weapons_allow_rifles - -1
09:17:11 mp_weapons_allow_smgs - -1
09:17:11 mp_weapons_allow_typecount - 5
09:17:11 mp_weapons_allow_zeus - 1
09:17:11 mp_weapons_glow_on_ground - 0
09:17:11 mp_weapons_max_gun_purchases_per_weapon_per_match - -1
09:17:11 mp_win_panel_display_time - 3
09:17:11 occlusion_test_async - 0
09:17:11 spec_freeze_panel_extended_time - 0.0
09:17:11 spec_freeze_time - 3.0
09:17:11 spec_replay_bot - 0
09:17:11 spec_replay_enable - 0
09:17:11 spec_replay_leadup_time - 5.3438
09:17:11 sv_accelerate - 5.5
09:17:11 sv_air_pushaway_dist - 0
09:17:11 sv_airaccelerate - 12
09:17:11 sv_allow_votes - 1
09:17:11 sv_alltalk - 0
09:17:11 sv_arms_race_vote_to_restart_disallowed_after - 0
09:17:11 sv_auto_adjust_bot_difficulty - 1
09:17:11 sv_auto_full_alltalk_during_warmup_half_end - 1
09:17:11 sv_autobunnyhopping - 0
09:17:11 sv_autobuyammo - 0
09:17:11 sv_bot_buy_decoy_weight - 1
09:17:11 sv_bot_buy_flash_weight - 1
09:17:11 sv_bot_buy_grenade_chance - 33
09:17:11 sv_bot_buy_hegrenade_weight - 6
09:17:11 sv_bot_buy_molotov_weight - 1
09:17:11 sv_bot_buy_smoke_weight - 1
09:17:11 sv_bots_force_rebuy_every_round - 0
09:17:11 sv_bots_get_easier_each_win - 0
09:17:11 sv_bots_get_harder_after_each_wave - 0
09:17:11 sv_bounce - 0
09:17:11 sv_buy_status_override - -1
09:17:11 sv_deadtalk - 0
09:17:11 sv_disable_immunity_alpha - 0
09:17:11 sv_disable_radar - 0
09:17:11 sv_disable_show_team_select_menu - missing cvar specified in bspconvar_whitelist.txt
09:17:11 sv_duplicate_playernames_ok - 0
09:17:11 sv_enablebunnyhopping - 0
09:17:11 sv_env_entity_makers_enabled - 1
09:17:11 sv_extract_ammo_from_dropped_weapons - 0
09:17:11 sv_falldamage_scale - 1
09:17:11 sv_falldamage_to_below_player_multiplier - 1
09:17:11 sv_falldamage_to_below_player_ratio - 0
09:17:11 sv_force_reflections - 0
09:17:11 sv_friction - 5.2
09:17:11 sv_grassburn - 0
09:17:11 sv_gravity - 800
09:17:11 sv_guardian_extra_equipment_ct - 
09:17:11 sv_guardian_extra_equipment_t - 
09:17:11 sv_guardian_health_refresh_per_wave - 50
09:17:11 sv_guardian_heavy_all - 0
09:17:11 sv_guardian_heavy_count - 0
09:17:11 sv_guardian_max_wave_for_heavy - 0
09:17:11 sv_guardian_min_wave_for_heavy - 0
09:17:11 sv_guardian_refresh_ammo_for_items_on_waves - 
09:17:11 sv_guardian_reset_c4_every_wave - 0
09:17:11 sv_guardian_respawn_health - 50
09:17:11 sv_guardian_spawn_health_ct - 100
09:17:11 sv_guardian_spawn_health_t - 100
09:17:11 sv_health_approach_enabled - 0
09:17:11 sv_health_approach_speed - 10
09:17:11 sv_hegrenade_damage_multiplier - 1
09:17:11 sv_hegrenade_radius_multiplier - 1
09:17:11 sv_hide_roundtime_until_seconds - missing cvar specified in bspconvar_whitelist.txt
09:17:11 sv_highlight_distance - 500
09:17:11 sv_highlight_duration - 3.5
09:17:11 sv_ignoregrenaderadio - 0
09:17:11 sv_infinite_ammo - 0
09:17:11 sv_knife_attack_extend_from_player_aabb - 0
09:17:11 sv_maxspeed - 320
09:17:11 sv_maxvelocity - 3500
09:17:11 sv_occlude_players - 1
09:17:11 sv_outofammo_indicator - 0
09:17:11 sv_show_ragdoll_playernames - missing cvar specified in bspconvar_whitelist.txt
09:17:11 sv_show_team_equipment_force_on - 0
09:17:11 sv_staminajumpcost - .080
09:17:11 sv_staminalandcost - .050
09:17:11 sv_stopspeed - 80
09:17:11 sv_talk_enemy_dead - 0
09:17:11 sv_talk_enemy_living - 0
09:17:11 sv_teamid_overhead_maxdist - 0
09:17:11 sv_teamid_overhead_maxdist_spec - 0
09:17:11 sv_versus_screen_scene_id - 0
09:17:11 sv_vote_to_changelevel_before_match_point - 0
09:17:11 sv_warmup_to_freezetime_delay - 4
09:17:11 sv_water_movespeed_multiplier - 0.8
09:17:11 sv_water_swim_mode - 0
09:17:11 sv_wateraccelerate - 10
09:17:11 sv_waterfriction - 1
09:17:11 sv_weapon_encumbrance_per_item - 0.85
09:17:11 sv_weapon_encumbrance_scale - 0
09:17:11 tv_delay - 10
09:17:11 tv_delay1 - 15
09:17:11 weapon_accuracy_nospread - 0
09:17:11 weapon_air_spread_scale - 1.0
09:17:11 weapon_max_before_cleanup - 0
09:17:11 weapon_recoil_scale - 2.0
09:17:11 weapon_reticle_knife_show - 1
09:17:11 weapon_sound_falloff_multiplier - 1.0
09:17:11 sv_camera_fly_enabled - missing cvar specified in bspconvar_whitelist.txt
09:17:11 Executing dedicated server config file
09:17:11 Execing config: server.cfg
09:17:11 Unknown command "sv_maxcmdrate"
09:17:11 Unknown command "sv_vote_creation_time"
09:17:11 Writing cfg/banned_user.cfg.
09:17:11 Writing cfg/banned_ip.cfg.
09:17:11 Execing config: banned_user.cfg
09:17:11 Execing config: banned_ip.cfg
09:17:11 Unknown command "allow_spectators"
09:17:11 Execing config: gamemode_competitive.cfg
09:17:11 Execing config: gamemode_competitive_server.cfg
09:17:11 exec: couldn't exec gamemode_competitive_server.cfg
09:17:11 GameTypes: set convars for game type/mode (classic:0/competitive:1):
09:17:11   exec {
09:17:11     exec gamemode_competitive.cfg
09:17:11     exec_offline gamemode_competitive_offline.cfg
09:17:11     exec gamemode_competitive_server.cfg
09:17:11   }
09:17:11 Set Gravity 800.0 (0.250 tolerance)
09:17:11 CHostage::Precache: missing hostage models for map de_dust2. Adding the default models.
09:17:11 PrecacheScriptSound 'Snowball.Bounce' failed, no such sound script entry
09:17:12 PrecacheScriptSound 'Survival.VO.Taunt4a' failed, no such sound script entry

09:17:13 Failed to load models/weapons/w_knife_ghost_dropped.mdl!

09:17:13 Failed to load models/props/crates/patch_envelope02.mdl!
09:17:13 PrecacheScriptSound 'balkan_epic_blank' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.omw_to_plant_a_04' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_ramp_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_back_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_platform_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_catwalk_03' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_enemy_spawn_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_doubledoors_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_front_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_overpass_03' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_palace_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_stairs_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_snipers_nest_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_connector_01' failed, no such sound script entry
09:17:13 PrecacheScriptSound 'professional_epic.loc_door_01' failed, no such sound script entry
09:17:14 Invalid file size for host.txt
09:17:14 Commentary: Could not find commentary data file 'maps/de_dust2_commentary.txt'. 
09:17:14 The Navigation Mesh was built using a different version of this map.
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Error parsing BotProfile.db - unknown attribute 'Rank'
09:17:14 Created class baseline: 20 classes, 13792 bytes.
09:17:14 Initializing Steam libraries for secure Internet server
09:17:14 Logging into Steam gameserver account with logon token 'B74A031Fxxxxxxxxxxxxxxxxxxxxxxxx'
09:17:14 Initialized low level socket/threading support.
09:17:14 \src\steamnetworkingsockets\clientlib\csteamnetworkingsockets_steam.cpp(138): Assertion Failed: Initted interface twice?
09:17:14 Set SteamNetworkingSockets P2P_STUN_ServerList to '' as per SteamNetworkingSocketsSerialized
09:17:14 SteamDatagramServer_Init succeeded
09:17:14 Execing config: sourcemod/sourcemod.cfg
09:17:14 Execing config: sourcemod\basevotes.cfg
09:17:14 Execing config: sourcemod\funcommands.cfg
09:17:14 Execing config: sourcemod\funvotes.cfg

09:17:14 Connection to Steam servers successful.
09:17:14    Public IP is 89.203.193.220.
09:17:14 Assigned persistent gameserver Steam ID [G:1:3976299].
09:17:14 Gameserver logged on to Steam, assigned identity steamid:85568392924015723
09:17:14 Set SteamNetworkingSockets P2P_STUN_ServerList to '146.66.155.54:3478' as per SteamNetworkingSocketsSerialized
09:17:15 VAC secure mode is activated.
09:17:15 Received server welcome from GC.
09:17:15 GC Connection established for server version 1219, instance idx 1
