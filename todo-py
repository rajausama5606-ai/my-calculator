task = []
print("===raja ki to-do list===")
while True:
    print("\n1. kam add kro")
    print("2. kam dekho")
    print("3. kam dleat kero")
    print("4.exit kro")
    ch = input("apna choice btaw 1 sa 4 tk:")
    if ch ==  "1":
        kam = input("naya kam kya hai:")
        task.append(kam)
        print(f"t'{kam}'add ho gya hai")
    elif ch ==  "2":
        print("\n---tumara kam ---")
        if len(task) == 0:
            print("koi kam nai , moj krlo")
        else:
            for i,task in enumerate(task, 1):
                print(f"{i}. {task}")
    elif ch == "3":
        num = input("kon sa number dleat krna hai:")
        num = int(num)

        if 1 <= num <= len(task):
            dleat =task.pop(num - 1)
            print(f"'{dleat}'dleat ho gya hai!")
        else:
            print("glat number hai , dobara try kro")
    elif ch == "4":
        print("ALLAH hafiz  raja ! kal milty han !")
        break
    else:
        print("1, 2, 3 ya 4 ma sa koi number btaw , dobara try kro")
