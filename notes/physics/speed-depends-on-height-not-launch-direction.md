---
title: Speed at a given height depends on launch speed and height, not launch direction
area: physics
tags: [energy, kinematics, projectile]
added: 2026-09-19
---

## Idea

Without air resistance, a projectile's speed when it passes a given height is
fixed by its launch speed and the height dropped — not by which way it was
thrown. Straight down, straight up, or sideways all give the same speed at the
same height.

## Key facts

$$E_k = \tfrac12 m v_0^2 + mgh$$

Only the magnitude $v_0$ enters, because kinetic energy is $\tfrac12 m v^2$ with
$v^2 = v_x^2 + v_y^2$ — a scalar with no direction in it. Gravity contributes
$mgh$ regardless of path, since gravity is a conservative force.

The *velocity* still differs between the cases; only the speed matches.

## Example

1 kg thrown vertically downward at 20 m/s, measured 100 m lower:

$$\tfrac12(1)(20)^2 + (1)(9.8)(100) = 200 + 980 = 1180\ \text{J}$$

so $v = \sqrt{2 \cdot 1180 / 1} \approx 49\ \text{m/s}$. Thrown *upward* at
20 m/s instead, it arrives at that same height with the same 1180 J — it just
takes about 4 s longer, climbing 20 m and coming back down.

## Pitfalls

**Air resistance breaks it, and it breaks it asymmetrically.** The upward throw
covers 40 m more path, so it loses more to drag. For a dense metal sphere over
100 m the error is a few percent; for a ping-pong ball it is the whole answer.

**$g = 9.8$ vs $g = 10$ is not rounding in a multiple-choice problem.** The
example gives 1180 J at $g = 9.8$ and 1200 J at $g = 10$. When the computed
value is missing from the options, check which $g$ the problem intends before
suspecting the physics.

**Time, range and maximum height *do* depend on launch direction.** Only the
speed-at-a-height relation is direction-blind.
