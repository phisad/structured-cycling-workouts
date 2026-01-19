# Quick Setup Guide

Get started in 5 minutes! 🚀

## For TrainingPeaks Users (Recommended)

### Step 1: Download Workouts
```bash
# Option A: Clone the repo
git clone https://github.com/phisad/structured-cycling-workouts.git
cd structured-cycling-workouts

# Option B: Download ZIP
# Click "Code" → "Download ZIP" on GitHub
# Extract the ZIP file
```

### Step 2: Set Your FTP
1. Go to [trainingpeaks.com](https://www.trainingpeaks.com)
2. Login (create free account if needed)
3. Click your name → **Settings**
4. Go to **Zones** → **Bike Power**
5. Enter your FTP (e.g., 197W)
6. Click **Save**

### Step 3: Import Workouts
1. In TrainingPeaks, go to **Workout Library** (left sidebar)
2. Click **+** to create a new folder
3. Name it: "Free Cycling Workouts"
4. Click the **⋮** (three dots) next to your folder
5. Select **"Workout Import"**
6. Navigate to the `.zwo` files:
   - `workouts/classic-zones/` (16 files)
   - `workouts/4dp-style/` (14 files)
7. Select all files you want to import
8. Click **Open**
9. Wait a moment for upload to complete

### Step 4: Use with Wahoo (Optional)
1. Open **Wahoo app** on phone
2. Go to **Settings** → **Authorized Apps**
3. Select **TrainingPeaks**
4. Login with same TrainingPeaks account
5. Allow connection

Now workouts will sync automatically!

### Step 5: Schedule a Workout
1. In TrainingPeaks app or website
2. Go to **Calendar**
3. Drag a workout from Library to "Today" or "Tomorrow"
4. Wait 2-5 minutes
5. Open **Wahoo app** → **Home** → **My plan**
6. Your workout appears!
7. Start training 🚴‍♂️

---

## For Zwift Users

### Step 1: Locate Zwift Workouts Folder

**Windows:**
```
C:\Users\[YourName]\Documents\Zwift\Workouts\[UserID]\
```

**Mac:**
```
~/Documents/Zwift/Workouts/[UserID]/
```

### Step 2: Copy Workout Files
1. Download this repo
2. Copy `.zwo` files to your Zwift workouts folder
3. Restart Zwift if it's running

### Step 3: Use in Zwift
1. Open Zwift
2. Select **Workouts** tab
3. Find your imported workouts under **Custom Workouts**
4. Select one and ride!

---

## For Other Platforms

### Convert to Different Formats

Need `.fit`, `.erg`, or `.mrc` instead of `.zwo`?

1. Go to [What's on Zwift Converter](https://whatsonzwift.com/convert/workouts)
2. Upload your `.zwo` file
3. Select output format
4. Download converted file
5. Import to your platform

---

## Troubleshooting

### "TrainingPeaks won't import my file"
- Make sure file extension is `.zwo` (not `.zwo.txt`)
- Use "Workout Import" not "Upload Activity"
- Try importing files one at a time

### "Wahoo app doesn't show workout"
- Workout must be scheduled for today or tomorrow
- Wait 5-10 minutes for sync
- Check TrainingPeaks is connected in Wahoo app
- Try force-closing and reopening both apps

### "Workout is too hard/easy"
- Retest your FTP if it's been >6 weeks
- Adjust intensity in app (90-110%)
- Start with Recovery/Endurance workouts

### "I don't know my FTP"
Quick estimate:
1. Do a 5-minute all-out effort
2. Take 75% of that average power
3. That's your approximate FTP
4. (Better: do a proper 20min FTP test)

---

## Next Steps

1. **Read the FAQ:** [FAQ.md](FAQ.md)
2. **Check the comparison guide:** [COMPARISON.md](COMPARISON.md)
3. **Browse individual workouts:** [/workouts](workouts/)
4. **Plan your training week:** Use sample schedules in README

---

## Need Help?

- [FAQ](FAQ.md) - Most common questions answered
- [GitHub Discussions](../../discussions) - Ask the community
- [GitHub Issues](../../issues) - Report problems

**Happy training! 🚴‍♂️💨**
