print("💖 Welcome to Pavithra's Mood Journal 💖")
print("Enter your mood for each day this week 🌈 (happy, sad, tired, angry, etc.)")

moods = []
days = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"]

for day in days:
    mood = input(f"How did you feel on {day}? ").lower()
    moods.append(mood)

print("\n📊 Here's your mood summary for the week:\n")

mood_count = {}
for mood in moods:
    if mood in mood_count:
        mood_count[mood] += 1
    else:
        mood_count[mood] = 1

for mood, count in mood_count.items():
    print(f"• {mood.capitalize()}: {count} time(s)")

most_common = max(mood_count, key=mood_count.get)
print(f"\n💡 Most common mood: {most_common.upper()}")

# cute suggestion
if most_common == "happy":
    print("You're vibing this week! Keep shining ✨")
elif most_common == "tired":
    print("Get some good sleep and treat yourself to something nice 💤")
elif most_common == "sad":
    print("Sending you hugs 🫂 Talk to someone and be kind to yourself.")
else:
    print("You're on a journey! Stay mindful 🌻")

print("\nThanks for journaling with me 💌")
