print("AYURVEDIC FAMILY DOCTOR\n \n \n \n")
name=str(input("Please enter your name:"))
print("HELLO WELCOME TO AYURVEDIC DOCTOR",name)
     
print("\n \n \n \n")


question1 = "Do you have any of these complaints?"
options1 = "a.Headache\nb.Fever\nc.Abdominal pain\nd.injury\ne.Burn"
print(question1)
print(options1)

while True:
    response = input("Hit 'a', 'b', 'c'  'd'  or 'e' for your answer\n")

    if response == "a":
        print("1.If you have acidity, avoid eating spicy food,staying awake at night\n2.Add ghee in your diet,drink milk daily and eat your meals at time\n3.Get Adequate Sleep\n4.Soothe Pain with a Cold Compress\n5.Drink Water. Inadequate hydration may lead you to develop a headache")
        break

    elif response == "b":
        print("1.Avoid eating cold things\n2.Take a light diet,avoid getting out in cold weather\n3.Be hydrated\n4.Take your temperature and assess your symptoms\n5.Take medications to reduce fever\n6.But no matter what the number on the thermometer reads, if you have any concerns consult your doctor.")
        break

    elif response == "c":
        print("1.Take a stroll around slowly to boost your digestion\n2.Drink warm water and eat chewping of ojawan\n3.Be hydrated.\n4.Add ghee in your diet\n4.Avoid eating chana and spices.\n5.Drink warm water before sleeping")
        break
        
    elif response == "d":
        print("1.Apply some turmeric powder after washing the wound\n2.Wrap it with cotton and bandage when bleeding stops\n3. If its superficial, apply pain killer oil and massage it lightly\n4.Rest. Resting is one of the most effective ways to start your healing process\n5.Ice. The benefits of applying ice are greatest within the first day or two after sustaining an injury")
        break  
        
    elif response == "e":
        print("1.Apply ice or pour cold water as early as possible\n2.Apply ghee with aloevera on the burn\n3.If blisters are formed afterwards, keep it dry,avoid contact with water\n4.Cool the burn. Hold the burned area under cool (not cold) running water or apply a cool, wet compress until the pain eases\n5.Remove rings or other tight items\n6.Don't break blisters,Consider a tetanus shot")
        break       


while True:
    response = input("\nI HOPE THAT THESE SUGGESTIONS HAVE COMFORTED YOU AND BEEN HELPFUL FOR YOU PLEASE CONSULT YOUR DOCTOR\n")

