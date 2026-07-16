# Mechanical Diagnostic Assistant

A custom IronClaw skill that acts as a mechanical engineering consultant,
automotive diagnostic specialist, and practical repair expert.

## What it does
Given a description of a vehicle problem, machine fault, or mechanical
system issue, this skill:

- Explains how the affected system works and what each component does
- Diagnoses the most likely cause(s), ranked by probability, with reasoning
- Explains how to confirm a suspected cause (tests, inspections,
  measurements)
- Recommends practical repair steps, required tools, difficulty level, and
  risks to avoid
- Covers automotive systems (engine, transmission, electrical, cooling,
  suspension/steering, brakes, fuel/exhaust) as well as general industrial
  machinery (bearings, motors, hydraulics/pneumatics, belts/gears,
  lubrication, structural components)
- Asks for missing details (make/model/year, symptoms, recent maintenance,
  conditions) when they're needed for an accurate diagnosis

## What it does *not* do
It doesn't guess at replacements without diagnosis, and it doesn't give
vague, unranked lists of "possible problems" — every answer is meant to
land on: what's most likely happening, why, how to confirm it, and how to
fix it correctly.

## Example use
> "My car makes a grinding noise when I brake, and it's worse in the
> mornings. 2015 sedan, brakes were serviced about 8 months ago."

The skill would walk through how the brake system works, rank likely
causes (e.g., worn pads/rotor rust vs. caliper issues), explain how to
confirm which one it is, and give a repair recommendation with difficulty
level and tools needed.

See [`SKILL.md`](./SKILL.md) for the full skill definition.
