## Required Vars
- `name`
- `friendly_name`
- ### diagnostics.yaml
- ### esphome.yaml
  - `api_key`
  - `ota_password`
  - #### optional:
    - `min_version`: 2024.12.0
- ### wifi.yaml
  - `wifi_ssid`
  - `wifi_password`
  - `wifi_ssid_2`
  - `wifi_password_2`
  - `wifi_ssid_3`
  - `wifi_password_3`
- ### components/bluetooth-proxy.yaml
  - #### optional:
    - `ble_proxy_active_scan`: false
- ### components/media-adf.yaml
  - `mic_lr_pin`
  - `mic_blk_pin`
  - `mic_dat_pin`
  - `amp_lr_pin`
  - `amp_blk_pin`
  - `amp_dat_pin`
  - #### optional:
    - `mic_sample_rate`: 44100
    - `amp_sample_rate`: 44100
    - `mic_bits_per_sample`: 16bit
    - `amp_bits_per_sample`: 16bit
    - `mic_channel`: left
    - `amp_channel`: left
    - `media_player_id`: adf_media_player
    - `media_player_on_announcement`: noop
- ### components/ultrasonic.yaml
  - `sonar_trigger_pin`
  - `sonar_echo_pin`
  - #### optional:
    - `sonor_update_interval`: 500ms
    - `sonar_timeout`: 4m
    - `sonar_ceiling_detection_threshold`: 10
- ### esp32/esp32-cam.yaml
  - #### optional:
    - `led_builtin_use_psram`: true
    - `led_builtin_name`: "Flash"
    - `led_builtin_internal`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/esp32-devkit.yaml
  - #### optional:
    - `led_builtin_name`: "Status LED"
    - `led_builtin_internal`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/metro-s3.yaml
  - #### optional:
    - `led_builtin_name`: "Status LED"
    - `led_builtin_internal`: true
    - `neopixel_builtin_name`: "Built-in Neopixel"
    - `neopixel_builtin_internal`: true
    - `neopixel_builtin_use_psram`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/qtpy-c3.yaml
  - #### optional:
    - `neopixel_builtin_name`: "Built-in Neopixel"
    - `neopixel_builtin_internal`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/qtpy-s2.yaml
  - #### optional:
    - `neopixel_builtin_name`: "Built-in Neopixel"
    - `neopixel_builtin_internal`: true
    - `neopixel_builtin_use_psram`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/qtpy-s3-nopsram.yaml
  - #### optional:
    - `neopixel_builtin_name`: "Built-in Neopixel"
    - `neopixel_builtin_internal`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true
- ### esp32/qtpy-s3.yaml
  - #### optional:
    - `neopixel_builtin_name`: "Built-in Neopixel"
    - `neopixel_builtin_internal`: true
    - `neopixel_builtin_use_psram`: true
    - `button_builtin_name`: "Built-in Button"
    - `button_builtin_internal`: true