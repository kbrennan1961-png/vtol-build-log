# VTOL Quadplane Build Log

**Firmware:** iNav  
**GitHub:** [kbrennan1961-png/inav](https://github.com/kbrennan1961-png/inav) (fork)

## Flight Controller

**Selected:** MATEKF405SE  
**Why:** Designed for fixed-wing iNav, 2 motors + 7 servos, 4x BEC for servo rail power, STM32F405, MPU6000, OSD, baro, 6x UART + softserial

---

## Projects

### 1. Mini Sparrow VTOL
**Platform:** DIY VTOL quadplane based on Flite Test Mini Sparrow  
**Flight Controller:** MATEKF405SE  
**Radio:** ELRS  
**Video:** Analog FPV  
**Airframe:** 28" Mini Sparrow wing + profile foam fuselage

#### Status
- [ ] Airframe build
- [ ] Wiring / power distribution
- [ ] FC configuration
- [ ] iNav CLI diff dump
- [ ] Tuning (fixed-wing)
- [ ] Tuning (multirotor / transition)
- [ ] Maiden flight

#### Parts List
| Part | Source | Notes |
|------|--------|-------|
| Mini Sparrow 28" wing kit | Flite Test | |
| Fuselage | Profile foam | |
| Flight Controller | MATEKF405SE | 2 motors, 7 servos, 4x BEC |
| Motors / ESCs | TBD | |
| Propellers | TBD | |
| Battery | TBD | |
| ELRS module | TBD | |
| VTX / Camera | TBD | Analog |
| GPS / Compass | TBD | For navigation |
| Tilt mechanism | TBD | |

---

### 2. XK450 VTOL Upgrade
**Platform:** XK450 VTOL plane → MATEKF405SE + GPS + iNav  
**Flight Controller:** MATEKF405SE  
**GPS:** Yes  
**Compass:** Yes  
**Notes:** Replacing original proprietary FC with standard iNav-compatible F4 board

#### Status
- [ ] Identify current FC and wiring
- [ ] Acquire MATEKF405SE
- [ ] Wire new FC + GPS + compass
- [ ] iNav CLI diff dump
- [ ] Tuning (fixed-wing)
- [ ] Tuning (multirotor / transition)
- [ ] Maiden flight

#### Parts List
| Part | Source | Notes |
|------|--------|-------|
| XK450 airframe | Existing | Keep original frame |
| MATEKF405SE | TBD | Same FC for both builds |
| GPS module | TBD | |
| Compass | TBD | |
| Motors / ESCs | TBD | Reuse or replace |
| Radio system | TBD | |

## Build Notes

### Airframe
- 

### Wiring
- 

### iNav Configuration
- CLI diff: [mini-sparrow-diff.txt](mini-sparrow-diff.txt)
- CLI diff: [xk450-diff.txt](xk450-diff.txt)
- Target: MATEKF405SE
- iNav version: TBD

### Tuning
- 

## Flight Log
| Date | Aircraft | Location | Notes |
|------|----------|----------|-------|
| | | | |

## Resources
- [iNav Documentation](https://github.com/iNavFlight/inav)
- [iNav VTOL Guide](https://github.com/iNavFlight/inav/blob/master/docs/VTOL.md)
- [MATEKF405SE Target](https://github.com/iNavFlight/inav/tree/master/src/main/target/MATEKF405SE)
- [Flite Test Mini Sparrow](https://www.flitetest.com/products/mini-sparrow-kit)
