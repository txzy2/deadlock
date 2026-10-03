Конфиги Deadlock (копия от 04.10.2026)
======================================

Куда что класть (папка игры Deadlock):

  gameinfo.gi                ->  Deadlock/game/citadel/gameinfo.gi
  video.txt                  ->  Deadlock/game/citadel/cfg/video.txt
  machine_convars.vcfg       ->  Deadlock/game/citadel/cfg/machine_convars.vcfg
  user_convars_0_slot0.vcfg  ->  Deadlock/game/citadel/cfg/user_convars_0_slot0.vcfg

Где лежит игра (Steam Library):
  .../SteamLibrary/steamapps/common/Deadlock

Важные заметки:
  1. Копировать файлы нужно при ПОЛНОСТЬЮ закрытой игре (Steam -> Stop).
  2. gameinfo.gi может перезаписываться обновлениями Deadlock или после
     "Проверить целостность файлов" в Steam. После патча проверяй.
  3. Оригинальные (до правок) версии лежат рядом с исходными файлами
     с суффиксом .opencode-backup.
  4. video.txt привязан к конкретному ПК/видеокарте (внутри DeviceID),
     при переносе на другое железо игра может пересоздать его сама.
  5. machine_convars.vcfg - машинные настройки (там fps_max и т.п.),
     user_convars_0_slot0.vcfg - пользовательские (сенса, прицел, HUD).

Что настроено (кратко):
  - Deadlock запускается через gamescope: 1440x1080 -> 1920x1080, FSR, stretch,
    180 Гц, -vulkan;
  - fps_max = 180;
  - отключены motion blur и depth of field, включено сглаживание CMAA;
  - gameinfo.gi: возвращены анимации/частицы/тени/трава/ткань, но тяжёлые
    эффекты (динамический свет, объёмный туман, SSAO) оставлены выключенными.

Файл deadlock-config-*.tar.gz - те же файлы одним архивом (удобно отправить).
