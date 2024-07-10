

class Osoba:
    def __init__(self, ime, godine):
        self.ime = ime
        self.godine = godine

    def predstavi_se(self):
        return f'Ja sam {self.ime} i imam {self.godine} godina.'


class Student(Osoba):
    def __init__(self, ime, godine, fakultet):
        super().__init__(ime, godine)
        self.fakultet = fakultet

    def predstavi_se(self):
        return f'Ja sam student {self.ime}, imam {self.godine} godina i studiram na fakultetu {self.fakultet}.'


class Zaposlenik(Osoba):
    def __init__(self, ime, godine, pozicija):
        super().__init__(ime, godine)
        self.pozicija = pozicija

    def predstavi_se(self):
        return f'Ja sam zaposlenik {self.ime}, imam {self.godine} godina i radim kao {self.pozicija}.'


osoba1 = Osoba('Ana', 30)
student1 = Student('Marko', 25, 'Fakultet informatike')
zaposlenik1 = Zaposlenik('Ivan', 35, 'Programer')


print(osoba1.predstavi_se())
print(student1.predstavi_se())
print(zaposlenik1.predstavi_se())
