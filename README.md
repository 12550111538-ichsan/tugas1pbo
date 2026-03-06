class Cafe:
    def __init__(self, cafe_name, coffee_type):
        self.cafe_name = cafe_name
        self.coffee_type = coffee_type
    def describe_cafe(self):
        print("Nama Cafe:", self.cafe_name)
        print("Jenis Kopi:", self.coffee_type)
        print()
    def open_cafe(self):
        print(self.cafe_name, "sekarang buka!")


# Membuat 3 instance
cafe1 = Cafe("icsan cafe", "Latte")
cafe2 = Cafe("amir cafe", "Americano")
cafe3 = Cafe("pekanbaru cafe", "Cappuccino")

# Memanggil metode
cafe1.describe_cafe()
cafe2.describe_cafe()
cafe3.describe_cafe()

class User:
    def __init__(self, first_name, last_name, age, email, city):
        self.first_name = first_name
        self.last_name = last_name
        self.age = age
        self.email = email
        self.city = city
    def describe_user(self):
        print("Nama:", self.first_name, self.last_name)
        print("Umur:", self.age)
        print("Email:", self.email)
        print("Kota:", self.city)
        print()
    def greet_user(self):
        print("Halo", self.first_name, "! Selamat datang.\n")


# Membuat beberapa instance user
user1 = User("Ahmad", "Fauzi", 20, "ahmad@email.com", "Pekanbaru")
user2 = User("Siti", "Aisyah", 21, "siti@email.com", "Bangkinang")
user3 = User("Budi", "Santoso", 22, "budi@email.com", "Dumai")

# Memanggil metode
user1.describe_user()
user1.greet_user()

user2.describe_user()
user2.greet_user()

user3.describe_user()
user3.greet_user()
