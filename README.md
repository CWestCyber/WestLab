# WestLab
class Budget:
    def __init__(self, deposit, withdraw, name):
        self.deposit = deposit
        self.withdraw = withdraw
        self.name = name

food = Budget(1000, 800, 'food')
clothing = Budget(800, 500,'clothing')
entertainment = Budget(300,200, 'entertainment')

print(food.deposit)
print(food.withdraw)
print(clothing.deposit)
print(clothing.withdraw)
print(entertainment.deposit)
print(entertainment.deposit)
