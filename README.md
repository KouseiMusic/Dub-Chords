<p align="center"><img width="300" height="69" alt="dubchordsbannersmall" src="https://github.com/user-attachments/assets/8752b522-6513-4186-9234-f01001819164" />
</p>

 **_<p align="center">Dub Techno Chords Synthesizer.</p>_**

---

![Version](https://img.shields.io/badge/Version-1.1.0-brightgreen?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Intel%20%7C%20Silicon%20%7C%20Universal-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone%20%7C%20AU%20%7C%20VST3-00CED1?style=flat-square&logo=steinberg&logoColor=white)
![DAW](https://img.shields.io/badge/DAW-Ableton%20Live%2012%2B-000000?style=flat-square&logo=bandlab&logoColor=white&labelColor=555555)

---

<img width="1288" height="856" alt="dubchordspreview" src="https://github.com/user-attachments/assets/148ace22-6c75-422d-b4e8-f982e0d96b99" />

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **Dub Engine**: Deep, resonant chords with up to 5 voices per trigger, amplitude envelopes and organic velocity variation for analogue warmth.

- **Global Delay**: Feedback delay with high-feedback capabilities to darken repeats. Feedback depth and wet level are both adjustable.

- **Global Reverb**: Atmospheric reverb network for spatial depth.

- **Phaser Modulation**: Add swirling movement to the sound with the built-in phaser effect.

- **WAV Recording**: One-click recording to a WAV file named with a date-time stamp. Captured post-master volume for a clean, ready-to-use bounce.

- **Multi-Language Keyboard Support**: Interface and keyboard bindings adapt to English (QWERTY), French (AZERTY), Russian (ЙЦУКЕН), Japanese (JIS) and Korean (두벌식) layouts. On-screen key labels update to match the selected locale.

- **Standalone**: Runs as a native application on macOS (Sonoma, Sequoia, Tahoe) without a browser.

- **Zero Dependencies at Runtime**: No internet connection required. Fully self-contained once installed.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: Sonoma (14.0), Sequoia (15.0) or Tahoe (16.0)
- **Architecture**: Intel (x64), Apple Silicon (Arm64) or Universal (U2B)
- **DAW (Plugin mode)**: Ableton Live 12 or 11, Logic Pro, Reason with the [BlackHole](https://github.com/ExistentialAudio/BlackHole) virtual audio driver for DAW routing in standalone mode.
> Audio Unit (AU) & VST3 plugins formats are currently under development.

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

### 𝐒𝐭𝐚𝐧𝐝𝐚𝐥𝐨𝐧𝐞
1. Download the latest [`Dub Chords`](https://github.com/KouseiMusic/Dub-Chords/releases/download/Dub_Chords_1.1.0/Dub_Chords_1.1.0_app_macOS_Universal.zip).
2. Extract & Drag `Dub Chords` to your `Applications` folder.
3. If macOS shows a Gatekeeper warning on first launch, right-click the application and choose `Open`, then confirm.

### 𝐀𝐮𝐝𝐢𝐨 𝐔𝐧𝐢𝐭 (𝐀𝐔)

> 𝐔𝐧𝐝𝐞𝐫 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭

### 𝐕𝐒𝐓𝟑 

> 𝐔𝐧𝐝𝐞𝐫 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭

## 𝐃𝐀𝐖 𝐔𝐬𝐚𝐠𝐞

1. Install [`BlackHole`](https://github.com/ExistentialAudio/BlackHole), a free virtual audio driver for macOS.
2. Open `Audio MIDI Setup` (found in `/Applications/Utilities/`).
3. Create a `Multi-Output Device` that includes both your `Audio Interface` and `BlackHole`.
4. Set the `Multi-Output Device` as the system output in `System Settings` > `Sound`.
5. In your `DAW`, create an `Audio Input Track` and set its input source to `BlackHole`.
6. You can now record or monitor `Dub Chords`'s output in real time.

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬

### 𝐒𝐲𝐧𝐭𝐡 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬

| Parameter | Range | Description |
| :--- | :--- | :--- |
| **Pitch** | -24 to +24 st | Master semitone transpose applied to the entire engine. |
| **Vel Rand** | 0 - 100% | Adds organic velocity variation to triggered chords for a more human feel. |
| **Chance** | 0 - 100% | Probability of a chord triggering. Lower values create sparse, generative rhythms. |
| **Cutoff** | 20 Hz - 20 kHz | Low-pass filter cutoff frequency. Sculpt the character of the dub chord. |
| **Reso** | 0 - 100% | Filter resonance (Q). Higher values accentuate the cutoff frequency. |
| **Phaser** | 0 - 100% | Phaser depth. Adds a swirling, sweeping movement to the sound. |
| **Delay** | 0 - 100% | Delay wet level and feedback depth. Creates infinite space and rhythmic echoes. |
| **Reverb** | 0 - 100% | Reverb wet level. Adds atmospheric depth and wash to the chords. |

### 𝐁𝐚𝐬𝐞 𝐍𝐨𝐭𝐞 & 𝐕𝐨𝐢𝐜𝐢𝐧𝐠

The **Base Note** sets the root of the chord relative to each key pressed. The chord shape is always built upward from the played note. Combining Base Note with the Pitch transpose lets you voice chords in any key without remapping the keyboard.

The **Voices** control adjusts the density of the chord, allowing you to select between 3, 4, or 5 simultaneous notes per trigger.

---

## 𝐐𝐖𝐄𝐑𝐓𝐘 (𝐄𝐧𝐠𝐥𝐢𝐬𝐡) 𝐊𝐞𝐲𝐛𝐢𝐧𝐝𝐢𝐧𝐠𝐬

Keyboard bindings adapt automatically when a language is selected from the Options menu. The tables below show the default English (QWERTY) layout.

**Top Row**

| Key | Note | Key | Note | Key | Note | Key | Note | Key | Note |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Q** | D#4 | **W** | E4 | **E** | F4 | **R** | F#4 | **T** | G4 |
| **Y** | G#4 | **U** | A4 | **I** | A#4 | **O** | B4 | **P** | C5 |

**Middle Row**

| Key | Note | Key | Note | Key | Note | Key | Note | Key | Note | Key | Note |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **A** | D#3 | **S** | E3 | **D** | F3 | **F** | F#3 | **G** | G3 | **H** | G#3 |
| **J** | A3 | **K** | A#3 | **L** | B3 | **;** | C4 | **'** | C#4 | **\\** | D4 |

**Bottom Row**

| Key | Note | Key | Note | Key | Note | Key | Note | Key | Note |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Z** | F2 | **X** | F#2 | **C** | G2 | **V** | G#2 | **B** | A2 |
| **N** | A#2 | **M** | B2 | **,** | C3 | **.** | C#3 | **/** | D3 |

French (AZERTY), Russian (ЙЦУКЕН), Japanese (JIS) and Korean (두벌식) layouts are available from **Options > Language**. Selecting a language remaps both the on-screen key labels and the computer keyboard bindings to match the physical layout of that locale.

---

## 𝐑𝐞𝐜𝐨𝐫𝐝𝐢𝐧𝐠

Press the `Rec` button in the header to begin capturing audio. Press it again to stop. A `.wav` file is exported automatically and named using the application name and the current date and time (e.g. `dubchords_2026-06-26_14-30.wav`). Recording captures the full processed signal including delay and reverb.

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬 & 𝐀𝐜𝐤𝐧𝐨𝐰𝐥𝐞𝐝𝐠𝐦𝐞𝐧𝐭𝐬

- **Developer**: [Kousei](https://github.com/KouseiMusic)
- **Tester**: [blockletter](https://github.com/braddownie)

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><code>𝒦𝑜𝓊𝓈𝑒𝒾</code></p>
<p align="center"><code>2026</code></p>
