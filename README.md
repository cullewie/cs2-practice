```
 ██████╗███████╗██████╗     ██████╗ ██████╗  █████╗  ██████╗
██╔════╝██╔════╝╚════██╗    ██╔══██╗██╔══██╗██╔══██╗██╔════╝
██║     ███████╗ █████╔╝    ██████╔╝██████╔╝███████║██║     
██║     ╚════██║██╔═══╝     ██╔═══╝ ██╔══██╗██╔══██║██║     
╚██████╗███████║███████╗    ██║     ██║  ██║██║  ██║╚██████╗
 ╚═════╝╚══════╝╚══════╝    ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝
```

CS2 pratik konfigi. Oyun içinde konsolu aç (`~`) ve aşağıdaki satırı yapıştır:

```
bot_kick; mp_warmup_end; sv_cheats 1; mp_limitteams 0; mp_autoteambalance 0; mp_maxmoney 60000; mp_startmoney 60000; mp_buytime 9999; mp_buy_anywhere 1; mp_freezetime 0; mp_roundtime 60; mp_roundtime_defuse 60; mp_respawn_on_death_ct 1; mp_respawn_on_death_t 1; sv_infinite_ammo 1; sv_showimpacts 1; sv_showimpacts_time 10; sv_grenade_trajectory 1; sv_grenade_trajectory_time 10; ammo_grenade_limit_total 4; sv_grenade_trajectory_prac_pipreview 1; bind ALT noclip; bind rctrl sv_rethrow_last_grenade; bind F1 "give weapon_hegrenade; give weapon_flashbang; give weapon_smokegrenade; give weapon_molotov"; mp_restartgame 1
```

## Tuşlar

| Tuş | İşlev |
| --- | --- |
| `ALT` | noclip (uçma) |
| `Sağ CTRL` | son atılan grenade'i tekrar at |
| `F1` | tüm grenade'leri ver (HE, flash, smoke, molotov) |

## Ne yapıyor

- Botları atar, warmup'ı bitirir, `sv_cheats 1` açar
- Para 60000, buytime sınırsız, her yerden satın alma açık
- Freezetime yok, round süresi 60 dk, ölünce anında respawn
- Sonsuz mermi, mermi izleri (`sv_showimpacts`) ve grenade yörüngesi açık
- Her grenade türünden 4 adet taşınabilir
