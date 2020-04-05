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
  
  for animal in animals:
      print(animal)

  for index in range(3):
      print(animals[index])

  current_index = 0
  while current_index < len(animals):
      print(animals[current_index])
      current_index += 1

  ````

- Dictionaries
  - These are like a map (key, value)
 ````
    contacts_dictionary = {'milo': '123456', 'lina': '45677', 'mommy': '345665'}
    print(contacts_dictionary)
    contacts_dictionary['gordo'] = '321245'
    print(contacts_dictionary)
    print(len(contacts_dictionary))

 ````
 
 ## Exercises
 
  ````
  to_do_list = []
  finished = False
  while not finished:
      task = input('Enter a task for your to-do list. Press <enter> when done: ')
      if len(task) == 0:
          finished = True
      else:
          to_do_list.append(task)
          print('Task added.')
  # Display the to-do list.
  print()
  print('Your To-Do List:')
  print('-' * 16)

  for task in to_do_list:
      print(task)
  ````
  
  
