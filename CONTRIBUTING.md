# Contributing to Free Cycling Workouts

Thank you for considering contributing to this project! 🚴‍♂️

## How to Contribute

### Reporting Bugs

If you find a bug in a workout file:

1. Check if the issue already exists in [Issues](../../issues)
2. If not, create a new issue with:
   - Workout name
   - Platform you're using (TrainingPeaks, Zwift, etc.)
   - Description of the problem
   - Error message (if any)

### Suggesting New Workouts

Have an idea for a new workout? Great!

1. Open a new [Discussion](../../discussions)
2. Describe:
   - Workout goal/focus
   - Duration (must be 20-35 minutes)
   - Interval structure
   - Which collection it fits (Classic or 4DP)

### Submitting Workouts

**Requirements:**
- Duration: 20-35 minutes (including warmup/cooldown)
- Format: `.zwo` (Zwift Workout XML)
- Power-based (as % of FTP)
- Clear naming convention
- Tested on actual trainer

**Workout File Standards:**

```xml
<workout_file>
    <author>Your Name</author>
    <n>Workout Name</n>
    <description>Brief description of workout and focus</description>
    <sportType>bike</sportType>
    <tags>
        <tag name="Category"/>
    </tags>
    <workout>
        <!-- Intervals here -->
        <Warmup Duration="300" PowerLow="0.5" PowerHigh="0.7" pace="0"/>
        <SteadyState Duration="600" Power="0.9" pace="0"/>
        <Cooldown Duration="300" PowerLow="0.7" PowerHigh="0.5" pace="0"/>
    </workout>
</workout_file>
```

**Naming Convention:**
- Classic Zones: `Category_Duration.zwo` (e.g., `SweetSpot_30min.zwo`)
- 4DP Style: `4DP-Category_Focus_Duration.zwo` (e.g., `MAP_Attack_25min.zwo`)

### Pull Request Process

1. Fork the repository
2. Create a new branch: `git checkout -b feature/workout-name`
3. Add your workout file to the appropriate folder:
   - `workouts/classic-zones/` or
   - `workouts/4dp-style/`
4. Test the workout yourself
5. Update the relevant README if needed
6. Commit: `git commit -am 'Add: [workout name]'`
7. Push: `git push origin feature/workout-name`
8. Open a Pull Request with:
   - Workout name and description
   - Duration and focus
   - TSS estimate (if known)
   - Confirmation that you've tested it

### Code of Conduct

**Be Nice:**
- Respectful and constructive feedback
- Help beginners
- Share knowledge
- Give credit where due

**Don't:**
- Copy copyrighted workouts from SYSTM, TrainerRoad, etc.
- Submit untested workouts
- Spam or promote unrelated products

## Workout Quality Guidelines

**Good Workout:**
- ✅ Clear purpose (e.g., "Builds FTP", "Improves sprint power")
- ✅ Appropriate warmup (5+ minutes)
- ✅ Proper cooldown (5+ minutes)
- ✅ Recovery between hard intervals
- ✅ Realistic power targets
- ✅ Total duration 20-35 minutes

**Bad Workout:**
- ❌ No warmup/cooldown
- ❌ Unrealistic intervals (e.g., 10min @ 150% FTP)
- ❌ No recovery between hard efforts
- ❌ Too long (>35min) or too short (<20min)
- ❌ Unclear purpose

## Testing Checklist

Before submitting a workout, test it yourself:

- [ ] Warmup feels adequate
- [ ] Hard intervals are challenging but doable
- [ ] Recovery is sufficient
- [ ] Cooldown is appropriate
- [ ] File imports correctly to platform
- [ ] Power targets display correctly
- [ ] Duration matches description

## Questions?

- Open a [Discussion](../../discussions)
- Check existing [Issues](../../issues)
- Read the [FAQ](FAQ.md) (if available)

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thanks for making this project better! 🙌**
