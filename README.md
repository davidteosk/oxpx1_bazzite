# oxpx1_bazzite
Bazzite OS Fixes for Onexplayer X1
# Audio - missing speaker
create oxpx1-hda-fix.conf in /ect/modprobe.d/

options snd_intel_dspcfg dsp_driver=1
options snd_hda_intel power_save=0
options snd-hda-intel model=laptop-dmic enable=yes

