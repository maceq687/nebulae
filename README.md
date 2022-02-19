# nebulae
My custom QU-Bit Electronix Nebulae v1 Pd instruments <br>
discussion: https://modwiggler.com/forum/viewtopic.php?p=2278911#2278911 <br>
Nebulae: https://www.qubitelectronix.com/legacy <br>
Alternate instruments: https://www.qubitelectronix.com/nebul-alt-instruments/ <br>

## Description of the instruments:

### 3OP FM
Oscillator build of three stacked FM operators, 3rd modulating 2nd, 2nd modulating 1st (basically a half of the 3rd DX7 algorithm)

* speed knob: global octave switch (+0...4 octaves)
* glide knob: glide for 2nd and 3rd operator
* pitch: pitch for all operators (1V/oct)
* grain size knob: 2nd operator tune (+0...4 octaves)
* grain rate knob: 3rd operator tune (+0...3 octaves)
* loop start knob: 2nd operator index
* loop size knob: 3rd operator index 

<img src="Nebulae_3OP_FM\Nebulae_3OP_FM_manual.jpg" width="587" height="384">

3OP FM Video demo:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=KAsKHrH6iwU
" target="_blank"><img src="http://img.youtube.com/vi/KAsKHrH6iwU/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

### 4SimpleDrums
Simple four-part drum generator
* speed knob: drum1 level
* pitch knob: drum2 level
* grain size knob: drum3 level
* grain rate: drum3 (open hi-hat) trigger (hi-hat sounds are not linked)
* loop start knob: drum4 level
* loop size: drum4 (closed hi-hat) trigger (hi-hat sounds are not linked)
* next button: drum2 (snare drum) trigger
* recall button: drum1 (bass drum) trigger

<img src="Nebulae_4SimpleDrums\Nebulae_4SimpleDrums_manual.jpg" width="587" height="384">

### Chord
Stack of four oscillators with continuously variable waveshapes and with selectable harmonic relations
* pitch: global pitch (1V/oct)
* mix: global fine tune (-/+ 1 semitone)
* grain size: all oscillators waveshape (ramp-triangle-saw-square-narrow pulse)
* grain rate: chord quality (maj7-min7-dom7-half_dim)
* loop start: chord inversion (root-1st-2nd-3rd)
* freeze toggle: triad toggle (7th chord tone toggle)
* next button: global octave switch (-/+ 2 octaves)

<img src="Nebulae_Chord\Nebulae_Chord_manual.jpg" width="587" height="384">

### DrDrum
One-part drum generator capable of storing and editing 4 presets (resets after power off)
* speed knob: noise/oscillator mix
* glide knob: low pass filter cutoff frequency
* pitch knob: drum presets 1-4 select (does not responds well to fast changing CV voltage)
* mix knob: level
* grain size: trigger on oscillator pitch
* grain rate: target oscillator pitch
* loop start: envelope attack time
* loop size: envelope decay time
* next button: randomize all parameters
* recall button: trigger input

<img src="Nebulae_DrDrum\Nebulae_DrDrum_manual.jpg" width="587" height="384">

### Dual Osc
Dual oscillator with continuously variable waveshape + low pass filter
* speed knob: 2nd oscillator tune (-/+ 7 semitones)
* glide knob: fm modulation amount (2nd oscillator modulates 1st oscillator frequency)
* pitch: pitch for both oscillators (1V/oct)
* mix knob: global fine tune (-/+ 2 semitones)
* grain size knob: oscillator 1 waveshape (ramp-triangle-saw-square-narrow pulse)
* grain rate knob: oscillator 2 waveshape (ramp-triangle-saw-square-narrow pulse)
* loop start knob: oscillators 1 and 2 mix
* loop size knob: low pass filter cutoff frequency
* next button knob: oscillator 1 octave switch (-/+ 2 octaves)
* recall button knob: oscillator 2 octave switch (-/+ 2 octaves)

<img src="Nebulae_Dual_Osc\Nebulae_Dual_Osc_manual.jpg" width="587" height="384">
