{"_about":"Where the module touches Warband systems.",
"columns":["id","system","what","needs_check","verified"],
"rows":[
{"id":"start_in_town","system":"game start / party placement","what":"New game places player party at dust_gulch","needs_check":"module_game_menus start flow","verified":false},
{"id":"start_gear","system":"player inventory","what":"Player starts with colt_revolver and 30 revolver_rounds","needs_check":"troop item list for trp_player","verified":false},
{"id":"bounty_offer","system":"quests/dialogs","what":"Sheriff offers bounty_01 on first talk","needs_check":"module_dialogs, module_quests","verified":false},
{"id":"gunsmith_shop","system":"trade","what":"Gunsmith opens barter screen using gunsmith.json stock","needs_check":"module_dialogs trade hook","verified":false},
{"id":"launch_module","system":"Melty recipe","what":"Play starts this module directly","needs_check":"Warband launch argument for module selection, not verified","verified":false}
]}
