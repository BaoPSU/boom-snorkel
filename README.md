# Boom Snorkel

Open source 3D printed articulating fume extraction arm. Mounts to a bench T-slot rail and positions the intake snout over your work area. Fully repositionable -- loosen the M8 knob, move it, retighten.

![Boom Snorkel installed on bench](images/full_assembly.jpeg)

## How it works

An M8 threaded rod runs through the entire arm. The 3D printed joints have wave-face (serrated) mating surfaces. When the knob is loose, joints rotate freely. Tighten the knob and the wave faces mesh together, locking every joint in position simultaneously.

The black flexible snake tube from the original fume extractor attaches via a tapered press-fit adapter, so you keep the original intake nozzle.

## Bill of materials

| Part | Spec | Notes |
|---|---|---|
| PVC pipe | 2" Schedule 40 (e.g. 7200-0600) | Cut to desired segment lengths |
| M8 threaded rod | Length = total arm span | Runs full length of arm |
| M8 knob nuts | x2 | Red knob style for hand tightening |
| 3D printed joints | See prints below | PLA or PETG, lime green in reference build |
| 3D printed snake adapter | See prints below | Press-fit to existing snake tube |
| 3D printed mounting bracket | See prints below | Clips to bench T-slot rail |

## Prints

| File | Description |
|---|---|
| `joint.stl` | Articulating joint with wave-face locking surfaces |
| `snake_adapter.stl` | Tapered adapter for standard flexible fume extractor snake tube |
| `mounting_bracket.stl` | Clips to bench T-slot / pegboard rail |

Variants in the Fusion 360 project:
- **Original** -- baseline joint design
- **Extended** -- longer arm reach
- **Stubby** -- shorter segment for tight spaces
- **Template** -- bare template for new variants

## Assembly

1. Cut 2" Schedule 40 PVC to desired segment lengths
2. Thread M8 rod through all joints and PVC segments
3. Clip mounting bracket onto bench T-slot rail
4. Press snake adapter onto end of arm, attach snake tube
5. Hand-tighten M8 knob to desired stiffness
6. Loosen to reposition, retighten to lock

## License

CERN Open Hardware Licence v2 - Strongly Reciprocal (CERN-OHL-S-2.0)