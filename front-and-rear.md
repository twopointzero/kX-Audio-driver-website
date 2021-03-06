## Front and Rear issues

These issues pertain to all Creative cards, but not to the E-mu APS and some Audigy2 Platinum Ex cards. Creative audio cards based on the EMU10kX audio DSP require a DAC (Digital to Analog Converter) in order to produce analog output. In general, this task is typically performed by either AC97 Codecs or I2S Codecs.

As a rule, Creative audio cards use the AC97 Codec for Front and Center/Subwoofer outputs, and I2S Codec for Rear output. The AC97 Codec is also used as an ADC (Analog to Digital Converter) and, thus, is responsible for all on-board analog inputs. (Note that LiveDrives and other DaughterBoard cards use different schemes).

The AC97 Codecs used in SBLive! cards are rather noisy devices (when compared to I2S Codecs), and this leads to some quality problems. As a rule, SBLive Rear outputs have much better Signal To Noise Ratio (SNR), Total Harmonic Distortion (THD) and Channel Separation (acs) since they use the I2S Codec. So, if you want to get better sound quality for music playback it is recommended that you plug your speakers into the 'Rear Out' and enable the 'Swap Front and Rear' kX Mixer option (the swap is enabled by default).

The Audigy and Audigy2 cards use both AC97 and I2S Codecs for Front output and this theoretically gives you rather good Front quality. But nevertheless, the AC97 Codec causes some distortion and thus the same procedure is recommended for use with Audigy / Audigy2 cards as well.

Certain Audigy2 Platinum Ex cards lack AC97 codec and thus don't require Front and Rear outputs to be swapped.

Of course, the above should be considered as a recommendation only.
