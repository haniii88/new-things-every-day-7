from datetime import datetim

def daily_message():
    now = datetime.now()
    print(f"Hello GitHub! Today is {now.strftime('%Y-%m-%d %H:%M:%S')}")

if __name__ == "__main__":
    daily_message()
