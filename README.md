# otv-magnetic-encoder-ring-sdk
Precision-magnetized encoder rings for humanoid robots, servo motors, and industrial automation. Compatible with iC-Haus iC-MU series (absolute/incremental). Full custom diameters (down to 1.0 mm thin), pole pairs (16–128), and ferrite/NdFeB/SmCo materials. Engineering samples in 4 weeks.
# OTV Magnetic Encoder Ring

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()
[![Product](https://img.shields.io/badge/Product-Magnetic%20Encoder%20Ring-blue)]()

Precision-magnetized encoder rings for humanoid robots, servo motors, and industrial automation. Compatible with **iC‑Haus iC‑MU series** (absolute/incremental) and other leading magnetic encoder ICs.

---

## 🎯 Overview

A typical humanoid robot integrates 30–40 joint modules, and each joint requires a high-performance encoder ring that is compact, accurate, and rugged. The OTV magnetic encoder ring delivers:

- **Hollow‑shaft architecture** – leaves the center unobstructed for cables
- **Ultra‑thin profile** – can be as thin as 1.0 mm to fit tight axial spaces
- **Absolute positioning** – position available instantly after power‑up, no homing sequence required
- **Rugged reliability** – dust, oil, moisture, shock, and vibration tolerant

## 📋 Technical Specifications

| Parameter | Value / Range |
|:---|:---|
| **Pole pairs** | 16 to 128 (or custom numbers for specific Nonius ratios) |
| **Outer diameter (OD)** | Custom, from small diameters upward |
| **Inner diameter (ID)** | Custom |
| **Minimum thickness** | 1.0 mm for ultra‑tight joints |
| **Magnetic pattern** | Dual‑track (absolute + incremental), single‑track, or single‑track with reference mark (missing pole) |
| **IC compatibility** | iC‑Haus iC‑MU series (pole pitch 1.28 mm, 1.5 mm, 2.0 mm) |
| **Resolution (with iC‑MU200)** | 18, 19, or 20 bits, depending on master pole pairs |
| **Mounting integration** | Bond directly to a metal hub, or supplied with a metal carrier |
| **Materials** | Ferrite rubber (bonded), neodymium‑based rubber compounds, SmCo for high temperature stability |

## 📦 Standard Product Portfolio

We supply rings fully optimized for the most widely used absolute encoder chips, including the **iC‑Haus iC‑MU series** [5†L76-L79]:

| Chip Series | Pole Pitch |
|:---|:---|
| iC‑MU / iC‑MU (standard) | 1.28 mm |
| iC‑MU150 | 1.5 mm |
| iC‑MU200 | 2.0 mm |

### Axial Nonius Encoder Disc – iC‑MU200 Reference

| Model | Master PP | Nonius PP | ID (mm) | OD (mm) | Master Track Dia (mm) | Nonius Track Dia (mm) | Master PW (mm) | Nonius PW (mm) |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| A2003200 | 32 | 31 | 25 | 44.5 | 40.8 | 32.8 | 2.0 | 1.66 |
| A2006400 | 64 | 63 | 62 | 85 | 81.5 | 73.5 | 2.0 | 1.83 |

### Axial Nonius Encoder Disc – iC‑MU150 Reference

| Model | Master PP | Nonius PP | ID (mm) | OD (mm) | Master Track Dia (mm) | Nonius Track Dia (mm) | Master PW (mm) | Nonius PW (mm) |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| A1503200 | 32 | 31 | 18 | 34.5 | 30.6 | 23.4 | 1.5 | 1.34 |
| A1506400 | 64 | 63 | 47.40 | 65.10 | 61.1 | 53.9 | 1.5 | 1.34 |

### Axial Nonius Encoder Disc – iC‑MU Reference (1.28 mm Pitch)

| Model | Master PP | Nonius PP | ID (mm) | OD (mm) | Master Track Dia (mm) | Nonius Track Dia (mm) | Master PW (mm) | Nonius PW (mm) |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| A1286400 | 64 | 63 | 38 | 56 | 52.2 | 45 | 1.28 | 1.12 |
| A1283200 | 32 | 31 | 15 | 29 | 26 | 18.88 | 1.28 | 1.12 |

### Radial Nonius Encoder Disc Reference

| Model | Master PP | Nonius PP | ID (mm) | OD (mm) | Master Track Dia (mm) | Nonius Track Dia (mm) | Master PW (°) | Nonius PW (°) |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| R1286000 | 32 | 31 | 20 | 24.5 | 4.8 | 1.2 | 5.63 | 5.81 |
| R1503000 | 64 | 63 | 53.1 | 59.6 | 5.8 | 2.2 | 2.81 | 2.86 |

> *PP = Pole Pairs | PW = Pole Width* 

## 🧪 How It Works

The encoder system comprises three main parts:

1. **Encoder ring** – A precision‑formed ring with alternating north and south poles arranged circumferentially
2. **Sensor chip** – A Hall, AMR or TMR sensor IC (such as the iC‑MU series from iC‑Haus) positioned off‑axis, reading the magnetic field emitted by the poles
3. **Processing electronics** – The ASIC converts magnetic flux variation into a digital position

For absolute position measurement, the ring provides two tracks: an **incremental track** with high‑frequency pole pairs for fine interpolation, and an **absolute/Nonius track** with a slightly different pole count. The chip reads both tracks, calculates their phase difference, and instantly determines the absolute angular position [8†L7-L16].

## 🎛️ Full Customization Services

OTV Sensing provides full customization for:

- **Dimensions** – OD, ID, thickness to match your mechanical environment; can be as thin as **1.0 mm**
- **Pole count** – From **16 to 128 pole pairs**, or custom numbers for specific Nonius ratios
- **Magnetic pattern** – Dual‑track (absolute + incremental), single‑track, or single‑track with reference mark (missing pole)
- **Mounting integration** – Bond directly to metal hub, or supplied with precision‑machined stainless steel carrier with mounting holes or clamping hub
- **Materials** – Ferrite rubber (bonded), neodymium‑based rubber compounds with enhanced thermal stability, SmCo for high temperature environments [9†L101-L110]

## 📦 Quality Assurance

Our quality control process includes:

- ✅ Dimensional sampling inspection
- ✅ 100% magnetic parameter test [9†L111-L117]

## 🕒 Lead Times & MOQ

| Product Type | Lead Time |
|:---|:---|
| **Standard products (no stock)** | 2 weeks after order confirmation |
| **Custom design samples** | ~4 weeks after design confirmation [11†L137-L144] |

- **Standard MOQ** – Flexible, negotiable for prototype or trial orders [11†L137-L138]
- **Sample building** – Generally charged a nominal fee to cover material and setup costs [11†L139-L141]

## 🔧 Compatibility

Fully optimized for the most widely used absolute encoder chips, including:

- iC‑Haus iC‑MU series (pole pitch: 1.28 mm)
- iC‑Haus iC‑MU150 (pole pitch: 1.5 mm)
- iC‑Haus iC‑MU200 (pole pitch: 2.0 mm) [5†L76-L79]

### Resolution with iC‑MU200

| Master Pole Pairs | Output Resolution |
|:---|:---|
| 16 | 18 bits |
| 32 | 19 bits |
| 64 | 20 bits [11†L130-L133] |

## 🚀 Getting Started

1. **Identify your requirements** – encoder IC model, desired resolution, mechanical envelope, environmental conditions
2. **Contact OTV Sensing** – provide mechanical drawing, target dimensions, pole pair count, operating temperature, and encoder IC model
3. **Receive engineering samples** – 4 weeks after design confirmation
4. **Validate** – test and approve
5. **Scale to production** – supported from small batches to volume production

## 📄 License

Proprietary – contact OTV Sensing for licensing and commercial use.

## 📞 Contact

**OTV Precision Sensing**

Website: [www.otvsensing.com](https://otvsensing.com)

Custom encoder ring inquiry: [www.otvsensing.com/custom-magnetic-encoder-rings/](https://otvsensing.com/custom-magnetic-encoder-rings/)

*We are ready to support you from concept through production.*
