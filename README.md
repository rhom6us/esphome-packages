## Required Vars
- name
- friendly_name
- ### esphome.yaml
  - api_key
  - ota_password
- ### wifi.yaml
  - wifi_ssid
  - wifi_password
  - wifi_ssid_2
  - wifi_password_2
  - wifi_ssid_3
  - wifi_password_3
- ### components/media-adf.yaml
  - mic_lr_pin
  - mic_blk_pin
  - mic_dat_pin
  - amp_lr_pin
  - amp_blk_pin
  - amp_dat_pin
  - #### optional
    - mic_sample_rate: 44100
    - amp_sample_rate: 44100
    - mic_bits_per_sample: 16bit
    - amp_bits_per_sample: 16bit
    - mic_channel: left
    - amp_channel: left
    - media_player_id: adf_media_player
    - media_player_on_announcement: noop