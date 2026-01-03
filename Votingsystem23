votes = {"Candidate A": 0, "Candidate B": 0}

def vote():
    print("1. Candidate A")
    print("2. Candidate B")
    choice = input("Vote for candidate: ")

    if choice == "1":
        votes["Candidate A"] += 1
    elif choice == "2":
        votes["Candidate B"] += 1
    else:
        print("Invalid vote")

def view_results():
    for candidate, count in votes.items():
        print(candidate, ":", count)

def main():
    while True:
        print("1. Vote")
        print("2. View Results")
        print("3. Exit")
        choice = input("Choose option: ")

        if choice == "1":
            vote()
        elif choice == "2":
            view_results()
        elif choice == "3":
            break
        else:
            print("Invalid option")

main()