# Parrotics

> **Robots that learn by watching.** Show it once. It parrots it.

Parrotics is a concept for a small consumer and research robotics company making expressive, bird-inspired desktop robots, in the same space as Pollen Robotics' Microduck and Reachy Mini, but with its own identity.

- **Domain:** parrotics.com (registered 2026-10-24, Hostinger, expires 2027-10-24)
- **Status:** concept / early exploration

## Files in this folder

| File | What's in it |
|---|---|
| `README.md` | Vision, positioning, differentiators, roadmap, open questions |
| `products.md` | The product line: Budgie, Macaw, Cockatoo (and a future flying R&D track) |
| `naming-and-domains.md` | Why "Parrotics", naming alternatives, product domain status |

## The idea

A parrot's defining skill is **imitation**. Imitation learning, teaching a robot by demonstration, is one of the most active areas in robotics. So the name, the animal and the technology all tell the same story.

Parrots also cover both halves of what makes small robots fun:

- **Action:** a beak and feet that work like hands, climbing, balancing, dancing.
- **Interaction:** talking, mimicking sounds, expressive head and wing movement.

For comparison, Pollen splits these into two products. Microduck is about action (walking, kicking, grabbing), and Reachy Mini is about interaction. A parrot robot does both naturally.

## Key decisions

### Talking: yes, a core feature

1. **Mimicry:** it repeats sounds, words and melodies you teach it. Instantly fun and very on-brand.
2. **Conversation (optional):** a voice assistant on open-source models, running on-device or on the user's own phone or computer. Privacy first.

### Flying: not in the first products

- Battery life for small flying robots is typically only minutes.
- Propellers near faces and pets are a safety risk, and they're noisy.
- Crash damage, returns and flight control add a lot of cost and complexity.

**Instead:** expressive, moving wings (flap when excited, fold when "sleeping"), and keep flight as a later research track (see `products.md`).

### Perches, not floors

A parrot lives on a perch, so the robot never has to balance on a desk edge or walk across a table. That's simpler than a walking biped, and it gets to market faster.

## What makes Parrotics different

1. **Teach by showing.** Move the robot's head or wings by hand, or record a demonstration in the app, and it repeats the movement. Imitation learning as a toy.
2. **Open hardware.** Microduck's software is open source but its hardware isn't. Publishing the shells and part files would win over the maker community.
3. **Swappable feathers.** 3D-printable coloured shells (red macaw, blue budgie, white cockatoo) for personality, plus community designs.
4. **Flock mode.** Several Parrotics robots chirping, dancing and "talking" to each other, for classrooms, events and social media.
5. **Simulation-first skills.** Climbing, balance and dances trained in simulation (reinforcement learning), then deployed to the robot, as Pollen does with Microduck.

## Taglines

- *Robots that learn by watching.*
- *Show it once.*
- *Your desk's new bird.*

## Rough roadmap

1. **Prototype Budgie:** perch stand, moving head and neck, beak, wings, camera, mic and speaker, sound mimicry.
2. **Teach-by-showing app:** record and replay motions, share them with others.
3. **Macaw:** grasping feet, climbing, stronger beak gripper, simulation-trained skills.
4. **Cockatoo:** a research platform for universities and labs.
5. **Flight R&D:** tethered or flapping-wing experiments, only once the core business works.

## Open questions

- Consumer first (Budgie), or research and education first (Cockatoo)?
- How much runs on the robot, and how much on the user's phone or computer?
- Open hardware from day one, or after launch?
- Target price for Budgie: closer to $199 or $299?
- Manufacturing: in-house small batches, or a contract manufacturer?
