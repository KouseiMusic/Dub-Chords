<p align="center"><img width="300" height="69" alt="dubchordsbannersmall" src="https://github.com/user-attachments/assets/8752b522-6513-4186-9234-f01001819164" />
</p>

 **_<p align="center">Dub Techno Chords Synthesizer.</p>_**

---

![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Intel%20%7C%20Silicon%20%7C%20Universal-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone%20%7C%20AU%20%7C%20VST3-00CED1?style=flat-square&logo=steinberg&logoColor=white)
![DAW](https://img.shields.io/badge/DAW-Ableton%20Live%2012%2B-000000?style=flat-square&logo=bandlab&logoColor=white&labelColor=555555)

---

https://github.com/user-attachments/assets/1f78e813-5477-404e-b248-cf5ee1a5369b

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **Dub Engine**: Deep, resonant chords with high-feedback delay and atmospheric reverb.

- **Standalone**: Runs as a native application on macOS (Sonoma, Sequoia, Tahoe) without a browser.

- **VST Integration (AU & VST3)**: Compatible with Ableton Live 12 and other major DAWs.

- **Zero Dependencies**: Fully offline capable. No internet connection required.

- **Minimalist UI**: Dark-themed, high-contrast interface optimized for low-light studio environments.

- **Multi-Language Support**: Interface available in English, Français, Русский, 日本語, and 한국어 with the keyboards layouts and keybindings respective to each language.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: Sonoma (14.0), Sequoia (15.0) or Tahoe (16.0)
- **Architecture**: Intel (x64), Apple Silicon (Arm64) or Universal (U2B)
- **DAW (Plugin mode)**: Ableton Live 12 or 11, Logic Pro, Reason with the [BlackHole](https://github.com/ExistentialAudio/BlackHole) virtual audio driver for DAW routing in standalone mode.
> Audio Unit (AU) & VST3 plugins formats are currently under development.

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

### 𝐒𝐭𝐚𝐧𝐝𝐚𝐥𝐨𝐧𝐞
1. Download the latest [`Dub.Chords1.0.1.app.zip`](https://github.com/DeobfuscateMusic/Dub-Chords/releases/download/DubChords1.0.1/DubChords1.0.1.app.zip)
2. Extract & Drag to your `Applications` folder.
3. Open `Dub Chords` and begin playing.

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

### 𝐐𝐖𝐄𝐑𝐓𝐘 (𝐄𝐧𝐠𝐥𝐢𝐬𝐡) 𝐊𝐞𝐲𝐛𝐢𝐧𝐝𝐢𝐧𝐠𝐬 (𝐅𝐫𝐞𝐧𝐜𝐡, Русский, 日本語 & 한국어 𝐚𝐯𝐚𝐢𝐥𝐚𝐛𝐥𝐞)

|    | Key Mapping & Notes |
| :--- | :--- |
| **Top** | `Q`: D#4 \| `W`: E4 \| `E`: F4 \| `R`: F#4 \| `T`: G4 \| `Y`: G#4 \| `U`: A4 \| `I`: A#4 \| `O`: B4 \| `P`: C5 |
| **Middle** | `A`: D#3 \| `S`: E3 \| `D`: F3 \| `F`: F#3 \| `G`: G3 \| `H`: G#3 \| `J`: A3 \| `K`: A#3 \| `L`: B3 \| `;`: C4 \| `'`: C#4 \| `\`: D4 |
| **Bottom** | `Z`: F2 \| `X`: F#2 \| `C`: G2 \| `V`: G#2 \| `B`: A2 \| `N`: A#2 \| `M`: B2 \| `,`: C3 \| `.`: C#3 \| `/`: D3 |

- **Pitch**: Transpose the entire engine (-24 to +24 semitones).
- **Vel Rand**: Adds organic velocity variation to triggered chords.
- **Chance**: Probability of a chord triggering (0-100%).
- **Base Note**: Select the root of your dub chords.
- **Voices**: Control the density of the chord (3 to 5 voices).
- **Cutoff/Reso**: Sculpt the character of the resonant low-pass filter.
- **Phaser**: Add swirling movement to the sound.
- **Delay/Reverb**: Create infinite space and rhythmic feedback.

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬 & 𝐀𝐜𝐤𝐧𝐨𝐰𝐥𝐞𝐝𝐠𝐦𝐞𝐧𝐭𝐬

- **Developer**: [Kousei](https://github.com/KouseiMusic)
- **Tester**: [blockletter](https://github.com/braddownie)

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><code>𝒦𝑜𝓊𝓈𝑒𝒾</code></p>
<p align="center"><code>2026</code></p>
