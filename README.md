# Nebulator
Granular Synthesizer - Max Patch

The main aim was to create a granular synthesizer that uses samples from another patch instantly. An additive based (Hybrid) and a granular (Nebula) synthesizers are implemented in this patch.  

Hybrid has some modulation (fm/am) and filter features. Also it contains a drunk arranger, a randomized trigger. Also, it is possible to play it by yourself by QWERTY keys.  To change octave of the keypad use the Z and X keys.

-Spacebar opens ezdac~ 

-Numkey 3 starts and stops recording for 4 seconds long waveform~. It renews the sample always while rec is open.

In addition, it is possible to change Hybrid's sound character by adjusting poly~ patcher's values from inside.

You can record a sample without starting Nebula. 

I put a preset object for quick start. If you click 1st preset, you will be hearing granular synthesis while recording sample (Do not forget to press Spacebar). Although you will not hear Hybrid because its gain is zero for this preset but you can mix them by adjusting Hybrid's Gain.
