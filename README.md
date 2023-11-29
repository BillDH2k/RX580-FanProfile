# RX580-FanProfile
Custom Fan Profile for RX580. Tested on Sapphrine Nitro+, Pulse models. May work on other RX580 models too.

This custom fan profile is injected, via OpenCore loading, to the Graphics card Device Properties, to achieve a faster fan speed. The default fan profile (stored in video card BIOS) does not start fan spinning until 60C and ram up too slow, so the card would be running a bit too hot under macOS. 

This profile has the following parameters:
- Default fan speed = 20% 
- Med Temp = 60C  (40%)
- High Temp = 70C (60%)
- Max Temp = 80C
- Target Temp = 70C

The additonal instruction to create your own fan profile can be found in this ([link here](https://old.reddit.com/r/hackintosh/comments/hg56pv/guide_polaris_rx_560_580_etc_custom_powerplay/)).
