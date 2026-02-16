# Workout Planning Agent Guidelines

## Philosophy

Build workouts that demand mental fortitude. The goal is 30 minutes of high-quality, constantly varied work that pushes to a limit and scales with effort. These are written down on paper and executed — no apps, no tracking overhead. Get the work done.

## Design Principles

- **Constantly varied**: No two workouts should feel the same. Rotate interval formats, movement pairings, and energy system demands. CrossFit-style variance is the model.
- **Scalable intensity**: Every workout should have a clear "dial" — load, speed, volume, or rest — so it meets the athlete where they are on any given day.
- **Mental edge**: Include at least one element per workout that requires pushing through discomfort. Hill sprints at the end, max-effort finishers, or sustained work under fatigue.
- **Simple on paper**: A workout should fit on a quarter page. If the description is complex, the workout is wrong. Deep module, simple interface — same principle applies here.
- **Time-capped**: Target ~30 minutes of work (excluding warmup). Hard cap at 35. This constraint forces density and intention.

## Interval Formats (Rotate Freely)

- **Work:Rest ratios** — 40:20, 30:30, 45:15. Pick one per block or vary within.
- **EMOM** — Every Minute On the Minute. Complete the work, rest the remainder.
- **Tabata** — 20s max effort / 10s rest, 8 rounds. Use sparingly; it's a finisher, not a foundation.
- **Chipper** — A list of movements done sequentially for time. Good for mental grind.
- **AMRAP** — As Many Rounds As Possible in a time domain. Classic density test.
- **Ascending/Descending ladders** — Reps climb or drop each round. Creates natural pacing.

Mix formats within a single workout. A workout might open with an EMOM, shift into a work:rest block, and close with a Tabata finisher.

## Equipment Context

Location: Costa Rica. Limited equipment, lots of creativity.

**Current inventory:**
- Yoga mat
- 2x 35 lb kettlebells
- Wall/surface for handstand push-ups
- Steep hill nearby

**Equipment updates:** When new equipment is added or the athlete travels, update this section. Workouts should only reference available gear.

## Movement Library

Build from these categories. Not exhaustive — add movements as they show up in workouts.

**Kettlebell:**
- Swings (Russian, American)
- Goblet squats
- Clean & press
- Snatches
- Turkish get-ups
- Farmer carries
- Thrusters
- Sumo deadlift high pull
- Single-arm rows
- Figure 8s
- KB deadlifts (single or double)

**Bodyweight:**
- Push-ups (standard, diamond, decline, deficit)
- Pull-ups / chin-ups (if bar available)
- Air squats / jump squats
- Burpees (standard, lateral, over-KB)
- Handstand push-ups
- Lunges (walking, reverse, jumping)
- Pistol squats (scaled as needed)
- Mountain climbers
- Plank variations
- V-ups / hollow holds
- Box jumps (if surface available)

**Conditioning:**
- Hill sprints
- Shuttle runs
- Bear crawls
- Broad jumps
- High knees / butt kickers

## Workout File Format

Keep it flat in the repo root for now. One markdown file per workout, named by date.

```
YYYY-MM-DD.md
```

### Template

```markdown
# [Date] — [Workout Name]

**Time:** ~[X] min
**Equipment:** [list]
**Format:** [interval format(s) used]

## Warmup (5 min)
[movements]

## Workout
[the work]

## Notes
[scaling options, intent, anything worth remembering]
```

## Athlete Profile

- Able-bodied, can handle intense work
- Sprint capacity: 8-10 quality hill sprints before dropoff
- Prefers writing workouts on paper
- Values suffering with purpose over mindless volume
- Enjoys novelty — repeat a workout format at most once per 2-week cycle

## What This Repo Is Not

- Not a tracking app. Minimal logging, if any.
- Not a programming periodization system (yet). Just good daily workouts.
- Not prescriptive about warmup/cooldown beyond a brief structure. The athlete knows their body.

## Future Directions

- CLI tool to generate workout .md files from templates
- Equipment inventory as structured data (YAML or similar)
- Movement tagging for variance tracking (push/pull/hinge/squat/carry/condition)
- Optional workout logging format if it becomes useful
