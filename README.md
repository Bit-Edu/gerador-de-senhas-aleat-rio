# gerador-de-senhas-aleatrio
import secrets
import string
bancodata_senha = string.ascii_letters + string.digits + string.punctuation
sizer = int(input("How much caractes the password will have: "))
password = ''.join(secrets.choice(bancodata_senha) for i in range(sizer))
print("Your password is: ")
print(password)
