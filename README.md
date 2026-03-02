### MPV Built-in Code Connection
Untranslated original English file address: https://github.com/mpv-player/mpv/blob/master/player/lua/stats.lua

### Display Image
<img width="3837" height="2154" alt="WeChat Image_2026-03-01_112007_816" src="https://github.com/user-attachments/assets/34541caf-e934-4ef8-84f4-75fa6c37e707" />

### Usage Instructions

Step 1: Edit the main configuration file
In your mpv.conf file, add or confirm the following line. This line disables mpv's built-in English statistics script, making way for our Chinese version script.
load-stats-overlay=no # Enables mpv's built-in statistics script [stats.lua], default is yes

Step 2: Place the Chinese version script

Place our translated stats.lua file into mpv's scripts folder.

Target location: portable_config/scripts/

Step 3: Start using it

Press the i key: Temporarily view playback statistics in fully Chinese.

Press the I (uppercase) key: Keep the statistics permanently displayed on the screen.

Press Shift + I: Keep the statistics permanently displayed on the screen.

Press the 1-5 or 0 keys: Switch between different information pages.

