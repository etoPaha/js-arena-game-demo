# Mesh2Motion — референс-анимации

Источник: https://github.com/Mesh2Motion/mesh2motion-app (`static/animations/`), скачано 2026-09-29.
Лицензия ассетов — **CC0** (README проекта: «The art assets (3d models, rigs, animations) are all licensed under CC0»).

- `human-base-animations.glb` — модель + 83 клипа (`Sword_Regular_A/B/C` с `_Rec`, `Sword_Attack`, `Sword_Block`, `Idle_Sword`, `Hit_*`, `Roll`, …)
- `human-addon-animations.glb` — ещё ~70 клипов (`Dodge_*`, `Strafe_*`, `Defend`, `Fighting Idle`, `Sword_Attack_Air_Vertical`, …)

Используются только в просмотрщике `?animview` как референс; перенос на наш скелет — `src/anim/retarget.ts`.
