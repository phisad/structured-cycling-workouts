# Structured Cycling Workouts

A collection of structured indoor cycling workouts in `.zwo` format, designed for time-crunched cyclists who want effective training sessions.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Workouts](https://img.shields.io/badge/workouts-30-blue.svg)]()
[![Duration](https://img.shields.io/badge/duration-20--35min-green.svg)]()

## 🎯 What is this?

This repository contains **30 structured cycling workouts** (20-35 minutes each) that you can use with:
- TrainingPeaks
- Wahoo ELEMNT
- Zwift
- Any platform that accepts `.zwo` files

Perfect for cyclists who:
- ✅ Have limited training time
- ✅ Want a basic collection of structured workouts
- ✅ Need variety in their training
- ✅ Train on smart trainers or with power meters

## 📦 Two Collections

### Collection 1: Classic Training Zones (16 workouts)
Traditional zone-based training for general fitness and endurance.

**Categories:**
- Recovery (2 workouts) - 55% FTP
- Endurance (2 workouts) - 65% FTP  
- Tempo (2 workouts) - 75% FTP
- Sweet Spot (4 workouts) - 88-90% FTP
- Threshold (2 workouts) - 95% FTP
- VO2max (4 workouts) - 115-120% FTP

[📖 Full documentation](workouts/classic-zones/README.md)

### Collection 2: 4DP-Style Workouts (14 workouts)
Performance-focused workouts inspired by Wahoo's Four-Dimensional Power methodology.

**Categories:**
- **FTP/Endurance** (4 workouts) - Sustained power, 75-100% FTP
- **MAP/Attack** (4 workouts) - VO2max intervals, 110-120% FTP
- **AC/Breakaway** (3 workouts) - Anaerobic capacity, 135-150% FTP
- **NM/Sprint** (3 workouts) - Neuromuscular power, max efforts

[📖 Full documentation](workouts/4dp-style/README.md)

## 🚀 Quick Start

### Option 1: TrainingPeaks (Recommended for Wahoo users)

1. **Set your FTP** in TrainingPeaks:
   - Login to [trainingpeaks.com](https://www.trainingpeaks.com)
   - Settings → Zones → Bike Power → Enter your FTP

2. **Import workouts**:
   - Go to Workout Library
   - Create a new folder
   - Click ⋮ (three dots) → "Workout Import"
   - Select the `.zwo` files you want

3. **Use with Wahoo**:
   - Connect TrainingPeaks in Wahoo app (Settings → Authorized Apps)
   - Workouts sync automatically
   - Drag workout to calendar → appears in Wahoo app

### Option 2: Direct Download

Download individual workouts or entire collections:
- [Download All Workouts (ZIP)](../../releases/latest)
- Individual files in [`/workouts`](workouts/) folder

## 📊 Which Collection Should I Use?

| Your Goal | Recommended Collection |
|-----------|----------------------|
| General fitness | Classic Zones |
| New to structured training | Classic Zones |
| Coming back from a break | Classic Zones |
| Performance/racing | 4DP-Style |
| Specific weakness training | 4DP-Style |
| Sprint improvement | 4DP-Style (NM workouts) |
| Mix of both | Use both! |

[📖 Detailed comparison guide](COMPARISON.md)

## 💡 Sample Training Week

**Beginner (Classic Zones):**
```
Mon: Recovery 30min
Wed: Sweet Spot 30min
Fri: VO2max 25min
Weekend: Endurance or off
```

**Intermediate (Mixed):**
```
Mon: Off or Recovery
Tue: FTP Sustained 25min (Classic)
Thu: MAP Attack 20min (4DP)
Sat: Sweet Spot 35min (Classic)
Sun: Endurance or off
```

**Advanced (4DP Focus):**
```
Mon: Off
Tue: FTP Over-Under 35min
Thu: AC Breakaway 20min
Sat: MAP Pyramid 30min
Sun: FTP Endurance 20min (recovery)
```

## 🔧 Technical Details

**File Format:** `.zwo` (Zwift Workout)
- Open XML format
- Power targets as % of FTP
- Compatible with most training platforms

**FTP-Based:** All workouts scale to your FTP
- Update FTP once → all workouts adjust automatically
- No need to modify individual files

**Tested With:**
- ✅ TrainingPeaks (import via Workout Library)
- ✅ Wahoo ELEMNT (via TrainingPeaks sync)
- ✅ Zwift (native .zwo support)
- ✅ Most smart trainers in ERG mode

## 🤝 Contributing

Found a bug? Have a workout idea? Contributions welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-workout`)
3. Commit your changes (`git commit -am 'Add new workout'`)
4. Push to the branch (`git push origin feature/new-workout`)
5. Open a Pull Request

**Workout Submission Guidelines:**
- 20-35 minutes duration
- Clear focus/goal
- Tested on actual trainer
- Follows `.zwo` format standards

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Summary:** Free to use, modify, and distribute. No warranty provided.

## ⚠️ Disclaimer

- These workouts are **not affiliated with** Wahoo, TrainingPeaks, or Zwift
- Created by the community, for the community
- Always consult a physician before starting a new training program
- Listen to your body - adjust intensity as needed
- FTP values are estimates - get tested for accuracy

## 🙏 Acknowledgments

- Inspired by Wahoo's 4DP methodology
- Training zone concepts from traditional periodization
- Community feedback and testing

## 📮 Support

- **Issues:** [GitHub Issues](../../issues)
- **Discussions:** [GitHub Discussions](../../discussions)
- **Email:** [your-email] (optional)

## 🔗 Related Projects

- [Power Formula (web-app)](http://powerformula.cc/)

---

**⭐ If these workouts help you, consider giving the repo a star!**

Made with ❤️ for the cycling community
