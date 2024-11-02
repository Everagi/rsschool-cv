# Oleg Ivanov

---

## Contacts

![Telegram](logo/telegram_16.png)&ensp;[Написать в Telegram @Cozar(Oleg)](https://t.me/@Cozar(Oleg))

![Telegram](logo/gmail_16.png)&ensp;[Отправить письмо на Gmail belorusskiychuvak@gmail.com](mailto:example@gmail.com)

![Telegram](logo/discord_16.png)&ensp;[Discord](https://discord.gg/invitecode)

![Telegram](logo/github_16.png)&ensp;[Профиль на GitHub](https://github.com/Everagi)

 ---
 
## About Me

I'm a communicative and determined developer with some experience in web development (freelance). My strengths include teamwork, quick learning, perseverance, and a drive for self-improvement. I have experience with programming languages such as JavaScript, C, Python.

---

## Skills

- Programming languages: 
  1. *JavaScript*
  2. *Python*
  3.  *C*
- Jinja template
- Platforms: *Node.js, Flask*
- Version control systems: *Git*
- Development tools: *Visual Studio Code, Sublime Text, GitHub, WebStorm, PyCharm*

---

## Code example *Python*

 ```python
app = Flask(__name__)
app.secret_key = 'my-super-secret-phrase-I-dont-tell-this-to-nobody'

class my_Form(FlaskForm):
    name = StringField('Username')
    phone = StringField('User phone')
    age = IntegerField('Age')
    bio = TextAreaField('About me')
    password = PasswordField('Your password')
    submit = SubmitField('GO!')

@app.route('/myform', methods=['GET', 'POST'])
def myform():
    form = my_Form()
    if request.method == 'GET':
        return render_template('myform.html', form=form)
    return form.name.data


if __name__ == '__main__':
    app.run(debug=True)

```

 ---