class Car:
    def init(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    def get_info(self):
        return f"{self.year} {self.make} {self.model}"

my_car = Car("Toyota", "Camry", 2020)
print(my_car.get_info())  # Виведе: 2020 Toyota Camry
