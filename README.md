# motivation_generator.py
import random

quotes = [
    "🚀 هر روز یک فرصت جدید است!",
    "💪 تو قوی‌تر از چیزی هستی که فکر می‌کنی.",
    "🌱 شروع کن، حتی اگر کوچک باشد.",
    "🔥 شکست فقط یک درس است، نه پایان راه.",
    "🎯 تمرکز کن روی پیشرفت، نه کمال.",
    "🌞 امروز بهترین زمان برای شروع است."
]

def main():
    print("✨ ژنراتور جملات انگیزشی ✨\n")
    while True:
        print(random.choice(quotes))
        again = input("\nمی‌خوای جمله بعدی رو ببینی؟ (y/n): ")
        if again.lower() != "y":
            print("👋 موفق باشی!")
            break

if __name__ == "__main__":
    main()
