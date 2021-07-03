# Assignment3
program using if,elif and else 

altitude=1000

userAltitude=int(input("enter the altitude"))

if userAltitude<=1000:
  print("safe to land")
elif userAltitude >1000 and userAltitude <5000:
  print("bring down to 1000")
elif userAltitude >5000 and userAltitude <=8000:
  print("your are in dangerous zone")
else:
    print("try again")
    
    output:
    enter the altitude7000
your are in dangerous zone
