# **Pure Data DJ System with OSC Control**

Interactive DJ system built with Pure Data and OSC Controller, featuring real-time audio manipulation through mobile interface controls.

---

## **Project Overview**

This project implements a complete DJ workstation in Pure Data, controlled remotely via OSC (Open Sound Control) protocol. The system integrates multiple audio sources including sample pads, synthesizers, and MIDI instruments, all manipulable through sliders and buttons from a mobile device.

### **Key Features:**
- **24-pad Sample Grid**: Trigger audio files (WAV) from mobile toggles.
- **Synthesizer Modules**: Three generative percussion synthesizers (kick, snare, hi-hat).
- **MIDI Piano**: 24-note keyboard with instrument selection.
- **Recording System**: Capture and playback mixed audio sessions.
- **Real-time Mixing**: Centralized audio bus with volume controls.
- **OSC Integration**: Network control via port 8100.

---

## **Technologies Used**

- **Pure Data (Pd)**: Main audio processing environment
- **OSC Protocol**: Wireless control from mobile app (OSC Controller)
- **MIDI**: External synthesizer integration (Microsoft GS Wavetable)
- **Audio Objects**: `readsf~`, `osc~`, `noise~`, `phasor~`, `tabwrite~`, `throw~/catch~`


---

## **Controls**

### **OSC Widgets:**
- **Toggles (gtoggle 1-24)**: Sample pad triggers.
- **Buttons (gbutton 1-24)**: MIDI piano notes.
- **Button 1-3**: Drum synthesizers.
- **Slider 1**: Master volume.
- **Slider 2**: Effect modulation (module-specific).
- **Slider 3**: MIDI instrument selector (0-127).

### **Additional Toggles:**
- **Toggle 1-3**: Auxiliary audio modules.
- **Record Toggle**: Start/stop session recording.
- **Playback Toggle**: Play recorded session.

---

## **Installation & Setup**

### **Requirements:**
1. Pure Data 0.52+
2. OSC Controller app (Android)
3. `Sounds/` folder with WAV files (Sound1.wav - Sound24.wav)

---

## **Demo Video**

[Watch Demo on Cloud](https://javerianacaliedu-my.sharepoint.com/:f:/g/personal/misancio_javerianacali_edu_co/Ersg3Re-fCpLiCFPyjYnzycBeuqCCcipkvOZURYRcVuIsw?e=aCSKec) 

---

## **Team Members**

- **Julio Mazo.** 
- **Miguel Angel Sanchez.** 

- **Course**: SInteraction Systems.
- **Institution**: Pontificia Universidad Javeriana Cali.



