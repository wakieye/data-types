# data-types
# TODO: Data types
#  TODO:types of data types
#  strings,integers,list,tuples,complex,dictionary,float,frozen set,set ,boolean binary data types and range.
# finding type of data type use the print(type(data.type))

# integers- represent numeric values
x = 10
print(type(x))
# string
x = "love"
print(type(x))
# TODO:COMPLEX
# complex
x = 1j
print(type(x))

# list
x = ["mangoes", "banana"]
print(type(x))

# tuples
x = ("mangoes", "banana")
print(type(x))

# range
x = range(100)
print(type(x))
# TODO:DICTIONARY DATA TYPES
# dictionary method 1
f = {
    'design': 'rockie',
    'torrents': 'free'
}
# dictionary method 2
d = dict([
    ('love', 'sucls'),
    ('baby', 'noisy')
])
# dictionary method 3
z = dict(
    Boston='sucks',
    Daddy='is home',
    Dean='i rule'
)
print(type(z))
z['love'] = 'death'
print(z)
print(z['Boston'])

print(z)
print(len(z))
# using inbuilt operator to determine existence of a key
# use <key> in variable or <key> not in variable but executed on python console

# dictionary practice
prey = {
    1: 'looses',
    2: 'great',
}
print(prey)
pt = dict([
    (10, 'wap'),
    (11, 'gag')
])
print(pt)
szn = dict(
    Womas='like',
    lulu='forget'
)
print(szn)
print(szn['Womas'])
# trial
person = {}
type(person)

person['fname'] = 'Joe'
person['lname'] = 'Fonebone'
person['age'] = 51
person['spouse'] = 'Edna'
person['children'] = ['Ralph', 'Betty', 'Joey']
person['pets'] = {'dog': 'Fido', 'cat': 'Sox'}
print(person)
# trial 2
slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']
print(slime)
print(slime['children'][1])
# trial 3
di = {12: 'pill', True: 'life'}
print(di)

# clearing dictionaries using var.clear() method is for removing all values and keys in a dictionary
di.clear()
print(di)

# geting key in dictionary using var.get(<key>) method is for getting values in dictionary
print(slime.get('children'))

# if key is not found you can add your return value of your choice rather that the default none value
print(person.get('love', "single"))
# var single is the return value if <single> key is not found.

# getting a list of tuples in a dictionary using the list(var.item())ie items in a dictionary are put in a tuple
# where the first value is considered the key and the second value the value.
slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']

print(list(slime.items()))
# finding a specific key or value in a tuple use list(var.items()[tuple number][key or value number in a tuple])
print(list(slime.items())[1][0])
print(list(slime.items())[1][1])

# getting a list of keys in a dictionary use the list(var.keys()) method
slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']

print(list(slime.keys()))

# getting a list of values using list(var.values())
slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']

print(list(slime.values()))

# removing a key from a dictionary using the var.pop(<key>) method or var.pop(<key>[default])

slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']
print(len(slime))
print(list(slime.values()))
print(list(slime.keys()))
print(slime.pop('level'))
print(slime)

# removing last key-value pair thus displaying them as a tuple in the console but default other key-value pairs
# displayed normaly minus the removed pair using the var.popitem() method
slime = {}
print(type(slime))

slime['young_thug'] = 'king of the world'
slime['price_tag'] = 1000000
slime['level'] = 'legend'
slime['label'] = 'wheezy records'
slime['children'] = ['Ralph', 'Betty', 'Joey', 'lil keed']

print(slime.popitem())
print(slime)
# if the variable consisting of the dictionary is empty the var.popitem() method shows a key error

# merging dictionaries using the var.update(<object>) method ie the object is another dictionary or abitrary
# key-value pairs
# a)if key in object is in the variable
d1 = {'a': 10, 'b': 29}
d2 = {'a': 220, 'c': 50}
d1.update(d2)
print(d1)
# ie if keys are in both dictionaries then the key in the first dictionary are updated by the keys on the second
# dictionary
# b)adding keys to the existing dictionary
d3 = {'f': 33, 'j': 21}
d4 = {'k': 22, 'l': 41}
d3.update(d4)
print(d3)
# c) adding key-value pairs to a dictionary using var.update([(key-value)])
y = {'money': 'power', 'wunna': 'gunna'}
y.update([('hey', 'surf'), ('surf', 'surf')])
print(y)
# d) adding key-value pairs using keyword arguments ie var.update(keywords)
y = {'money': 'power', 'wunna': 'gunna'}
y.update(king='von', june='sucks')
print(y)
# deleting an entry in a dictionary using the del var[<key>] method
y = {'money': 'power', 'wunna': 'gunna'}
del y['money']
print(y)
# extra
x=['a','b',{'foo':1,'bar':{'x':10,'y':20,'z':30},'baz':3},'c','d']
print(x)
print(x[2])

# TODO:SETS

