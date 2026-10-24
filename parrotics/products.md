# Parrotics product line

Each product is named after a parrot species, ordered from small and simple to large and capable.

Prices and parts are early ballpark estimates for planning only; validate them with a hardware engineer.

---

## Budgie (entry)

*The friendly desk companion.*

- **Form:** a small parrot sitting on its own perch stand.
- **Movement:** head and neck (look, tilt, bob), a beak that opens and closes, expressive wings (flap, fold).
- **Senses:** camera, microphone array, speaker.
- **Does:**
  - repeats sounds, words and melodies you teach it
  - reacts to faces, voices and music
  - dances, head-bobbing to the beat
  - optional conversation through an open-source voice assistant
- **Teach by showing:** move its head or wings by hand and it replays the motion.
- **Rough price:** ~$199–299
- **Domain idea:** microbudgie.com (free when checked on 2026-10-24)

## Macaw (flagship)

*The one with hands, well, feet and a beak.*

Everything in Budgie, plus:

- **Feet that grip:** climbs a perch or rope, shifts along a branch, hangs upside down.
- **Beak gripper:** picks up and carries light objects.
- **Skills learned in simulation:** climbing, balancing and tricks trained with reinforcement learning, then deployed to the robot.
- **Swappable feather shells:** red, blue and green macaw colourways, plus 3D-printable community designs.
- **Rough price:** ~$399–599
- **Domain ideas:** micromacaw.com, minimacaw.com (free when checked on 2026-10-24)

## Cockatoo (research)

*A platform for labs and universities.*

- Larger, with more joints and better sensors.
- Built for imitation-learning research, manipulation, and multi-robot "flock" experiments.
- Full SDK, simulation models and open documentation.
- **Rough price:** ~$999+
- **Domain idea:** microcockatoo.com (free when checked on 2026-10-24)

## Later: flight (R&D track)

Not a launch product. Explore only once the core business is working.

- Tethered or flapping-wing prototypes for research.
- Main challenges: battery life (minutes), safety around people and pets, noise, crash durability.

## Other species to keep in mind

Possible future products or special editions:

- **Cockatiel:** microcockatiel.com and minicockatiel.com were free on 2026-10-24
- **Lovebird:** a pair of robots that interact with each other
- **Kea:** a "curious and mischievous" edition, since kea parrots are famous problem-solvers
- **African Grey:** a "talker" edition focused on speech and language
- **Polly:** a possible nickname or app name

## Rough hardware sketch (entry model)

| Part | Notes |
|---|---|
| 6–10 hobby servo motors | Head, neck, beak, wings (plus feet on Macaw) |
| Small Linux computer | e.g. a Raspberry Pi or Rockchip-based board, as Microduck uses |
| Camera | Face and object detection |
| Microphone array + speaker | Talking, mimicry, music |
| Battery | Or powered through the perch base |
| 3D-printed shell | Swappable "feathers" |

Parts cost is roughly in the low hundreds of dollars, which supports a retail price of about $299–499. This is an estimate, not a quote.
