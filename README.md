Arithmetic Operators


if name == 'main':
    a = int(input())
    b = int(input())
    
    sum = a + b
    dif = a - b
    product = a*b
    
    print(sum)
    print(dif)
    print(product)

==========================================================

Mutations

def mutate_string(string, position, character):
    string = list(string)
    position = int(position)
    string[position] = character
    text = ""
    for  x in string:
        text += x
    return text
if name__ == 'main__':
    s = input()
    i, c = input().split()
    s_new = mutate_string(s, int(i), c)
    print(s_new)
