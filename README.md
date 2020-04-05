# python

- Format String example
  ````
  text = input('What would you like the cat to say? ')
  text_length = len(text)
  print(' {}'.format('_' * text_length))
  print(' < {} >'.format(text))
  print(' {}'.format('-' * text_length))
  print(' /')
  print(' /\_/\ /')
  print('( o.o )')
  print(' > ^ <')

  ````

- Basic Math operations
  ````
  sum = 1 + 2
  difference = 100 - 1
  product = 3 * 4
  quotient = 8 / 2
  power = 2 ** 4
  remainder = 3 % 2

  print("Sum {}".format(sum))
  print("Difference {}".format(difference))
  print("Product {}".format(product))
  print("Power {}".format(power))
  print("Remainder {}".format(remainder))

  ````

- Exceptions
  ````
  animals = ['rabbit', 'dog', 'cat']
  try:
    cat_index = animals.index('bear')
  except:
    cat_index = 'Animal not found'
  print(cat_index)

  ````

- Loops
  
  ````
  animals = ['rabbit', 'dog', 'cat']
  print('-' * 20 + ' For loop' + '-' * 20)
  for animal in animals:
      print(animal)

  print('-' * 20 + ' For loop with index' + '-' * 20)
  for index in range(3):
      print(animals[index])

  print('-' * 20 + ' while loop' + '-' * 20)
  current_index = 0
  while current_index < len(animals):
      print(animals[current_index])
      current_index += 1

  ````
  
  
