# VTOL Quadplane Build Log

**Firmware:** iNav  
**GitHub:** [kbrennan1961-png/inav](https://github.com/kbrennan1961-png/inav) (fork)

## Projects

### 1. Mini Sparrow VTOL
**Platform:** DIY VTOL quadplane based on Flite Test Mini Sparrow  
**Flight Controller:** TBD  
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
| Flight Controller | TBD | F4 target likely |
| Motors / ESCs | TBD | |
| Propellers | TBD | |
| Battery | TBD | |
| ELRS module | TBD | |
| VTX / Camera | TBD | Analog |
| GPS / Compass | TBD | For navigation |
| Tail sitter / tilt mechanism | TBD | |

---

### 2. XK450 VTOL Upgrade
**Platform:** XK450 VTOL plane → F4 flight controller + GPS + iNav  
**Flight Controller:** F4 board (target TBD)  
**GPS:** Yes  
**Compass:** Yes  
**Notes:** Replacing original proprietary FC with standard iNav-compatible F4 board

#### Status
- [ ] Identify current FC and wiring
- [ ] Select F4 target board
- [ ] Wire new FC + GPS + compass
- [ ] iNav CLI diff dump
- [ ] Tuning (fixed-wing)
- [ ] Tuning (multirotor / transition)
- [ ] Maiden flight

#### Parts List
| Part | Source | Notes |
|------|--------|-------|
| XK450 airframe | Existing | Keep original frame |
| F4 Flight Controller | TBD | See target list below |
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
- Target: TBD
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
- [Flite Test Mini Sparrow](https://www.flitetest.com/products/mini-sparrow-kit)
- [iNav F4 Targets](https://github.com/iNavFlight/inav/tree/master/src/main/target) — 80+ boards
