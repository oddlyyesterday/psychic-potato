print('1)Dawn')
print('2)Dusk')
Q1=int(input('Do you like dawn or dusk?'))
print(Q1)
if Q1==1:
  print('Gryffindor and Ravenclaw both get a +1.')
elif Q1==2:
  print('Hufflepuff and Slytherin both get a +1')  
else:
  print('Wrong input')  
print('1) The Good')
print('2) The Great')
print('3) The Wise')
print('4) The Bold')
Q2=int(input('When I’m dead, I want people to remember me as:'))
if Q2==1:
  print(' Hufflepuff +2.')  
elif Q2==2:
  print('Slytherin +2.')  
elif Q2==3:
  print('Ravenclaw +2.') 
elif Q2==4:
  print('Gryffindor +2.')
else:
  print('Wrong input.')     
print('1) The violen')
print('2) The trumpet')
print('3) The piano')
print('4) The drum')
Q3=int(input('Which kind of instrument most pleases your ear?'))
if Q3==1:
  print('Slytherin +4.')
elif Q3==2:
  print('Hufflepuff +4.')
elif Q3==3:
  print('Ravenclaw +4.')
elif Q3==4:
  print('Gryffindor +4.')  
else:
  print('Wrong input')  
Q4=int(input('Slytherin points:'))  
if Q4>0:
      print('sssssnake!')
Q5=int(input('Hufflepuff points:')) 
if Q5>0:
     print('You might belong in Hufflepuff,Where they are just and loyal,Those patient Hufflepuffs are trueAnd unafraid of toil.') 
Q6=int(input('Ravenclaw points:'))
if Q6>0:
      print('Or yet in wise old Ravenclaw,If you have a ready mind,Where those of wit and learning,Will always find their kind.')
Q7=int(input('Gryffindor points:'))
if Q7>0:
      print('Act first, think later — it’s the Gryffindor way!') 
elif Q7==0:
   print('That’s cute. You must be from one of the... other houses.')            
