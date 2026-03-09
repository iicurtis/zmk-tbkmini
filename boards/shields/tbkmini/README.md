uv run west build -b nice_nano -S zmk-usb-logging -- -DZMK_CONFIG=/home/icurtis/Documents/keyboard/miryoku_zmk/config/ -DZMK_EXTRA_MODULES=/home/icurtis/Documents/keyboard/zmk-tbkmini -DSHIELD=tbkmini_left

uv run west build -b xiao_ble -S zmk-usb-logging -- -DZMK_EXTRA_MODULES=/home/icurtis/Documents/keyboard/zmk-tbkmini -DSHIELD=tbkmini_dongle

uv run west build -b nice_nano -- -DZMK_EXTRA_MODULES=/home/icurtis/Documents/keyboard/zmk-tbkmini -DSHIELD=tbkmini_left
