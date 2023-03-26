# air-quality-wall-panel

The first version was based upon the work of https://github.com/kylemanna/sniffer and worked for years but I wanted to use the new bme680_bsec2 library so I was up for quite a challenge.
So after basically merging https://github.com/kylemanna/sniffer and this example yaml( https://github.com/esphome/issues/issues/2692) the configuration let me crash 2 esp32 ttg displays. One without bme680 and one with bme680 sattached so something was wrong. long story short,  (I am quite sure it was a string conversion in one of the it.print commands) This works. It still needs some finetuning but can be uploaded in home assistant.  
