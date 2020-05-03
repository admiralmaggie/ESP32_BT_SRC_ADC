ESP32 Bluetooth A2DP-SOURCE using Highspeed ADC
========================
This demo is based on ESP-IDF A2DP-SOURCE code. The demo is modified so bluetooth sink (speaker) is sourced with audio input via I2S internal ADC at 44100 sample rate. The stadnard demo's connect/disconnect looping mode is disabled. You can specify a BT MAC to skip pairing/discovery mode. 

### Hardware Required

This example is able to run on any commonly available ESP32 development board. The ADC input should be connected ADC1 Channel 0 pin. Any decent microphone with an amplifier like MAX9814 should work.  

### BT Security Database
To delete ALL existing BT paired devices, push RESET button and then immediate hold down BOOT button (do not hold down BOOT while pressing RESET! that would place the device in download mode.)

