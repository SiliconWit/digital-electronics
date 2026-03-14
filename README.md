---
title: "Digital Electronics and Logic - Collaboration Guide"
description: "Contributing guide for Digital Electronics and Logic course content"
tableOfContents: true
sidebar:
  order: 999
---

# Digital Electronics and Logic

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/digital-electronics/](https://siliconwit.com/education/digital-electronics/)

A practical course covering the digital building blocks inside every microcontroller. Nine lessons go from binary arithmetic and logic gates to memory, buses, ADC/DAC, and MCU architecture. Each lesson connects directly to embedded programming concepts.

## Lessons

| # | Title |
|---|-------|
| 1 | Binary, Hex, and Number Systems |
| 2 | Logic Gates and Boolean Algebra |
| 3 | Combinational Logic Circuits |
| 4 | Flip-Flops, Latches, and Registers |
| 5 | Counters, Timers, and Frequency Dividers |
| 6 | Memory: SRAM, Flash, and EEPROM |
| 7 | Bus Architecture and Communication Interfaces |
| 8 | ADC and DAC Fundamentals |
| 9 | Microcontroller Architecture Overview |

## File Structure

```
digital-electronics/
├── index.mdx
├── binary-hex-number-systems.mdx
├── logic-gates-boolean-algebra.mdx
├── combinational-logic-circuits.mdx
├── flip-flops-latches-registers.mdx
├── counters-timers-dividers.mdx
├── memory-types-organization.mdx
├── bus-architecture-interfaces.mdx
├── adc-dac-fundamentals.mdx
├── microcontroller-architecture-overview.mdx
└── README.md
```

## How to Contribute

1. Fork the repository: [SiliconWit/digital-electronics](https://github.com/SiliconWit/digital-electronics)
2. Create a feature branch: `git checkout -b feature/your-topic`
3. Make your changes and commit with a clear message
4. Push to your fork and open a Pull Request against `main`
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Use ASCII block diagrams in `text` code blocks where they aid understanding
- Use truth tables for logic operations
- Use Starlight components (`<Tabs>`, `<TabItem>`, `<Steps>`, `<Card>`) where appropriate
- Every lesson should include a "How This Connects to Embedded Programming" section
- LaTeX math is fine for formulas (e.g., `$2^{8} = 256$`)

## Local Development

Clone the main site repository and initialize submodules:

```bash
git clone --recurse-submodules <main-repo-url>
cd siliconwit-com
npm install
npm run dev
```

To test a production build:

```bash
npm run build
```

## License

This course content is released under the [MIT License](LICENSE).
