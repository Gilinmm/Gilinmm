impot.randomn

simvl = "+-_=qwertyuioplkjhgfdsazxcvbnm,.QWERTYUIOPLMKNBJVHCGXFZDAS1234567890!@#$%^&*|\/?;:"

password_length = int(input("Какой длины будет пароль"))
password = ""
for i in range(password_lenght):
  password += random.choice(simvl)
print(password)
