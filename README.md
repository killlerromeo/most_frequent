# most_frequent
created by killerromeo using python
a= input('Please enter a string:-')
def mostfrequent(string):
    d = dict()
    for key in string:
        if key not in d:
            d[key] = 1
        else:
            d[key] += 1
    return d
print(mostfrequent(a))
