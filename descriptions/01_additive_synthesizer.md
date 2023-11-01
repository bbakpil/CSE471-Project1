## Additive Synthesizer

An additive synthesizer generates sound by adding together multiple sinusoidal waveforms, each at a different frequency, amplitude, and phase.

### Supported Components
	<instrument instrument="AdditiveInstrument">
		<!-- Intro -->
		<note measure="1" beat="1" duration="1" note="C3" h1=".5" adsr="0 0 0 3"/>
		<note measure="1" beat="1.5" duration="1" note="E3" h1=".5" adsr="0 0 0 3"/>

(1) Polyphony: Ability of an instrument or device to produce multiple sounds or notes simultaneously.

- The score file is set up to produce sound simultaneously.

(2) Envelope generation: A process by which a synthesizer or audio processor shapes the amplitude evolution of a sound over time, typically defined by stages such as attack, decay, sustain, and release.

- The adsr is indicated and set in the score file, each alphabet representing attack, decay, sustain, and release.

### Grading Criteria
10 - Sinusoid playback on demand from the sequencer



20 - Definition of all harmonics

: 2 harmonics are included. When 3 harmonic sound is generated, the sound breaks up

30 - Envelope generation

: works fine

35 - Polyphony

: works fine
