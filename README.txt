5parks VST3 - LEVEL 9000 BEEFCAKE CORE

Base:
- built forward from 5parks_VST3_night_prism_refinement.zip

Main upgrades in this pass:
- rebuilt the UI into a darker premium synth layout with a much larger hero wavetable display
- replaced the blanket rainbow styling with selective neon accents and module-specific colour identity
- added a custom rotary/combo/toggle look for a more polished flagship feel
- shrank the routing/mod panel to free space for the big visual display
- made the sound engine friendlier by softening defaults and reducing harsh factory gain staging
- changed OSC B default pitch to unison instead of a fixed fifth for more natural starting tones
- added a hard source-mute path so all oscillator/sub/noise levels at zero produce silence
- removed extra oscillator phase-advancing calls inside the distortion/character stages to reduce shrillness
- added extra final warmth smoothing so low-tone settings can produce gentler bass tones

Files updated:
- source/PluginEditor.h
- source/PluginEditor.cpp
- source/PluginProcessor.cpp
- source/SynthEngine.h
