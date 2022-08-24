# Anastasiia Mezentseva

### Junior Frontend Developer

---

##### __Contact information:__

__Phone:__ +90 531 3121728
__E-mail:__ a.mezentseva@hotmail.com
[Telegram](https://t.me/Nastasien)
[Behance](https://www.behance.net/nst_mznts)
[Linkedin](linkedin.com/in/anastasiia-mezentseva-5b23b4234)

---

##### __Briefly About Myself:__

My name is Anastasiia. I have extensive experience in banking. Working in a bank, I gained experience in interacting with various companies and their representatives. I faced with different work situations, I improved my skills in working with large amounts of data, learned how to structure and format them correctly. Also, I have stress resistance and experience in a multitasking environment.

I am studying UI\UX design. I learn how to design mobile and web applications, adapt it to different types of devices, and study the user experience of using applications. I have been studying English with a tutor for several years. I need this knowledge to publish my design work on an international platform (Behance), to travel and just to communicate with people from other countries. I am also learning Python and C programming languages.

---

##### __Skills and Proficiency:__

- HTML5, CSS3
- Git, GitHub
- VS Code
- Python, C
- Adobe Photoshop, Illustrator, InDesign
- Figma

---

##### __Code example:__

```python
def get_weather(city, weatherbot):
    emoji = {
        'Clear': 'Clear \u2600\ufe0f',
        'Clouds':'Clouds \u2601\ufe0f',
        'Rain':'Rain \U0001f327\ufe0f',
        'Drizzle':'Drizzle \U0001f327\ufe0f',
        'Thunderstorm':'Thunderstorm \u26c8\ufe0f',
        'Snow':'Snow \U0001f328\ufe0f',
        'Mist':'Mist \U0001f32b',
        'Fog':'Fog \U0001f32b'}
    try:
        r=requests.get(f"https://api.openweathermap.org/data/2.5/weather?q={city}&appid={weatherbot}&units=metric")
        data=r.json()
        #pprint(data)
        city=data['name']
        cur_weather=int(data['main']['temp'])
        weather_emoji=data['weather'][0]['main']
        if weather_emoji in emoji:
            we=emoji[weather_emoji]
        feels_like=int(data['main']['feels_like'])
        humidity=data['main']['humidity']
        pressure=int(data['main']['pressure']/ 1.333)
        wind=data['wind']['speed']
        sunrise=datetime.datetime.fromtimestamp(data['sys']['sunrise'])
        sunset=datetime.datetime.fromtimestamp(data['sys']['sunset'])
        print(f'The weather in {city}\nCurrent temperature: {cur_weather}C° {we}\nFeels like: {feels_like}C°\n'
            f'Humidity: {humidity}%\nPressure: {pressure}mmHg\nWind: {wind}m/s\nSunrise: {sunrise}\nSunset: {sunset}'
        )
    except Exception as ex:
        print(ex)
        print("I can't find this city. Try again.")

def main():
    city=input("Enter a city name:")
    get_weather(city, weatherbot)
```

---

##### __Courses:__

- Programming in Python on [Stepik](https://stepik.org) (completed)
- HTML and CSS Tutorials on the [w3schools](https://www.w3schools.com/) (completed)
- Fundamentals of C Programming on [Stepik](https://stepik.org) (in progress)
- RS Schools Course «UpSkill Me» (in progress)

---

##### __Languages:__

- English - Intermediate/Upper-intermediate
![English level](https://media-exp1.licdn.com/dms/image/C561FAQGlBgv6TjunJQ/feedshare-document-cover-images_1280/0/1660074500869?e=1661778000&v=beta&t=XFCE5vDLGHns7C0ueCXhJjzzzbh6ce7ZM6wA5YrBZjA 'Grammar Foundations')
- Russian - Native