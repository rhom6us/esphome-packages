## Required Vars
- `name`
- `friendly_name`
- ### diagnostics.yaml
  - `node_status_disabled`: false
  - `uptime_seconds_disabled`: false
  - `wifi_signal_disabled`: false
  - `esphome_version_disabled`: false
  - `uptime_text_disabled`: false
  <!-- - `esphome_project_version_disabled`: false
  - `esphome_project_version_detailed_disabled`: false
  - `esphome_project_name_disabled`: false -->
- ### esphome.yaml
  - `api_key`
  - `ota_password`
  - `project_author`: rhombus
  - `project_version`
  ### config/wifi.yaml
  - `wifi_ssid`
  - `wifi_password`
  - `wifi_ssid_2`
  - `wifi_password_2`
  - `wifi_ssid_3`
  - `wifi_password_3`
## Boards:
  ### config/boards/esp32/esp32-cam.yaml
  - `led_builtin_name`: "Flash"
  - `led_builtin_internal`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/esp32-devkit.yaml
  - `led_builtin_name`: "Status LED"
  - `led_builtin_internal`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/metro-s3.yaml
  - `led_builtin_name`: "Status LED"
  - `led_builtin_internal`: true
  - `neopixel_builtin_name`: "Built-in Neopixel"
  - `neopixel_builtin_internal`: true
  - `neopixel_builtin_use_psram`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/qtpy-c3.yaml
  - `neopixel_builtin_name`: "Built-in Neopixel"
  - `neopixel_builtin_internal`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/qtpy-s2.yaml
  - `neopixel_builtin_name`: "Built-in Neopixel"
  - `neopixel_builtin_internal`: true
  - `neopixel_builtin_use_psram`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/qtpy-s3-nopsram.yaml
  - `neopixel_builtin_name`: "Built-in Neopixel"
  - `neopixel_builtin_internal`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/esp32/qtpy-s3.yaml
  - `neopixel_builtin_name`: "Built-in Neopixel"
  - `neopixel_builtin_internal`: true
  - `neopixel_builtin_use_psram`: true
  - `button_builtin_name`: "Built-in Button"
  - `button_builtin_internal`: true
  ### config/boards/rp2040/pico-w.yanl
  - `led_builtin_name`: "Built-in LED"
  - `led_builtin_internal`: true
## Components:
### config/components/bluetooth-proxy.yaml
- `ble_proxy_active_scan`: false
### config/components/media-adf.yaml
- `mic_lr_pin`
- `mic_blk_pin`
- `mic_dat_pin`
- `amp_lr_pin`
- `amp_blk_pin`
- `amp_dat_pin`
- `mic_sample_rate`: 44100
- `amp_sample_rate`: 44100
- `mic_bits_per_sample`: 16bit
- `amp_bits_per_sample`: 16bit
- `mic_channel`: left
- `amp_channel`: left
- `media_player_id`: adf_media_player
- `media_player_on_announcement`: noop
### config/components/ultrasonic.yaml
- `sonar_trigger_pin`
- `sonar_echo_pin`
- `sonor_update_interval`: 500ms
- `sonar_timeout`: 4m
- `sonar_ceiling_detection_threshold`: 10
### config/components/ultrasonic_direction.yaml
- `sonar_trigger_pin`
- `sonar_echo_pin`
- `sonar_update_interval`: 500ms
- `sonar_timeout`: 4m
- `sonar_id`: subject_distance
- `sonar_name`: "Distance"
- `sonar_internal`: true
- `sonar_direction_idle_time`: 1s
