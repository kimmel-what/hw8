def login(username, password):
    correct_username = "User123"
    correct_password = "qwerty12345"

    try:
        assert username == correct_username and password == correct_password, \
            "Невірне ім'я користувача або пароль"

        print("Вхід виконано успішно")

    except AssertionError as error:
        print(error)

login("", "")
