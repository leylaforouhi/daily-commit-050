from datetime import datetim

def milestone_message():
    today = datetime.now().strftime("%Y-%m-%d")
    message = f"🎉 Milestone reached on {today}! 50 days of consistency and coding growth."
    return message

if __name__ == "__main__":
    print(milestone_message())
