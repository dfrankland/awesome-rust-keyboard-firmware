# awesome-rust-keyboard-firmware

A list of keyboard firmwares written in Rust and related resources.

## Active Projects

### [anne-key][]

[anne-key]: https://github.com/ah-/anne-key

*   Status: stable
*   MCU: [stm32l151][]
*   System: [Real Time For the Masses][]

An alternative firmware for the first Anne Pro Keyboard, with the goal of being
more stable than the original firmware and adding extra features.

### [keyberon][] / [keyberon-f4][]

[keyberon]: https://github.com/TeXitoi/keyberon
[keyberon-f4]: https://github.com/TeXitoi/keyberon-f4

*   Status: beta
*   MCU: [stm32f103][] / [stm32f401][]
*   System: [Real Time For the Masses][]

A hand wired preonic mechanical keyboard with a firmware in rust.

### [polymer-kb][]

[polymer-kb]: https://gitlab.com/polymer-kb/polymer

*   Status: alpha
*   MCU: [stm32f103][]
*   System: [Embedded Executor][]

Work-in-progress modular mechanical keyboard. First iteration of the keyboard
implementing a split ortholinear layout.

Notes on and instructions for getting started with Rust embedded development:

*   <https://josh.robsonchase.com/embedded-bootstrapping/>
*   <https://josh.robsonchase.com/embedded-frustrations/>

More info on the Embedded Executor system, its inception, and progress:

*   <https://josh.robsonchase.com/embedded-executor/>
*   <https://josh.robsonchase.com/embedded-executor-2/>

### [proton-c][]

[proton-c]: https://github.com/dfrankland/proton-c

*   Status: alpha
*   MCU: [stm32f303][]
*   System: [Real Time For the Masses][]

A proof-of-concept blinking the LED of the Proton C, an ARM STM32F303xC based
drop-in replacement for the Pro Micro. It uses the same chip as the Planck rev6
boards, and Skully's new ARM Clueboards.

### [KeyToKey][] / [stm32f103_k2k][]

[KeyToKey]: https://github.com/TyberiusPrime/KeyToKey
[stm32f103_k2k]: https://github.com/TyberiusPrime/stm32f103_k2k

*   Status: alpha
*   MCU: [stm32f103][]
*   System: [Real Time For the Masses][]

## Inactive Projects

### [flutterby-rs][]

[flutterby-rs]: https://github.com/wez/flutterby-rs

*   Status: alpha
*   MCU: [atmega32u4][]
*   System: none

Keyboard firmware implemented in Rust primarily for the ErgoDox EZ.

There's also another reference implementation in C++:

*   <https://github.com/wez/flutterby-cpp>

### [dactyl-build][]

[dactyl-build]: https://github.com/techhazard/dactyl-build

*   Status: alpha
*   MCU: [mk20dx256][]
*   System: none

An attempt to build a custom dactyl keyboard using Rust.

Lots of notes on decisions made and the struggles had developing the project on
the repo's wiki pages:

*   <https://github.com/techhazard/dactyl-build/wiki>

### [teensy_kbd][]

[teensy_kbd]: https://github.com/IsaacWoods/teensy_kbd

*   Status: alpha
*   MCU: [mk20dx256][]
*   System: none

Rust firmware for mechanical keyboards using the Teensy 3.2.

Mostly follows the guides made by Branan Riley on running Rust on Teensy 3.2:

*   <https://www.pjrc.com/using-rust-language-on-teensy-3-2/>
*   <https://branan.github.io/teensy/>

[Real Time For the Masses]: https://github.com/japaric/cortex-m-rtfm
[Embedded Executor]: https://gitlab.com/polymer-kb/firmware/embedded-executor

[stm32l151]: https://www.st.com/content/ccc/resource/technical/document/reference_manual/cc/f9/93/b2/f0/82/42/57/CD00240193.pdf/files/CD00240193.pdf/jcr:content/translations/en.CD00240193.pdf
[stm32f103]: https://www.st.com/resource/en/reference_manual/cd00171190.pdf
[stm32f303]: https://www.st.com/resource/en/reference_manual/dm00043574.pdf
[stm32f401]: https://www.st.com/resource/en/reference_manual/dm00096844.pdf
[atmega32u4]: http://ww1.microchip.com/downloads/en/devicedoc/atmel-7766-8-bit-avr-atmega16u4-32u4_datasheet.pdf
[mk20dx256]: https://www.nxp.com/docs/en/reference-manual/K20P64M72SF1RM.pdf
