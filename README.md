# 👋 Привет, я Антон!  
### .NET / Python разработчик 

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00BFFF&center=true&vCenter=true&width=600&lines=.NET+Developer;Python+Backend+Developer;DevOps;Fullstack+Developer" alt="Typing SVG" />
</div>


<p align="center">
  <a href="mailto:anton005go.too@gmail.com">📧 anton005go.too@gmail.com</a>  
  | <a href="https://t.me/d1n0nn">Telegram</a>  
  | <a href="https://aleynichenko.ru">🌐 Мой сайт</a>  
  | <a href="https://docs.google.com/document/d/1UyzE1RjDUeMAAOiYdqbAOu4yCrP1EW2Km0I7kEhCFO4/edit?tab=t.0">Резюме</a>  
</p>  

---

## 🎯 О себе  

```csharp
using System;
using System.Collections.Generic;

public sealed class AntonAleynichenko
{
    private static readonly Lazy<AntonAleynichenko> _instance = new Lazy<AntonAleynichenko>(() => new AntonAleynichenko());

    public static AntonAleynichenko Instance => _instance.Value;

    public string Name { get; } = "Антон Алейниченко";
    public DateTime DateOfBirth { get; } = new DateTime(2006, 11, 27);
    public string City { get; } = "Москва, Россия";
    public string Gender { get; } = "Мужской";
    public int Height { get; } = 187;
    public List<string> Hobbies { get; } = new() { "Программирование", "Спорт", "Обучение", "Менеджмент проектов" };
    public List<string> CodeLanguages { get; } = new() { "C#", "Python", "C++", "SQL", "JavaScript", "HTML", "CSS", "Java", "Kotlin" };
    public List<string> Tools { get; } = new() { "Docker", "Kubernetes", "Jenkins", "PyCharm", "VS Code", "Visual Studio", "Git" };
    public string CurrentFocus { get; } = "Разработка масштабируемых приложений на C# и Python";
    public string FunFact { get; } = "Я настолько люблю кодить, что считаю кофе недостаточно асинхронным! ☕";

    private AntonAleynichenko()
    {
        Console.WriteLine("Привет! Я готов создавать инновационные и масштабируемые решения.");
    }

    public void AboutMe()
    {
        Console.WriteLine($"\nМеня зовут {Name}, я родился {DateOfBirth:dd.MM.yyyy} и живу в {City}.");
        Console.WriteLine($"Основное направление: {CurrentFocus}.");
        Console.WriteLine($"Рост: {Height} см.");
        Console.WriteLine($"Увлечения: {string.Join(", ", Hobbies)}.");
        Console.WriteLine($"Интересный факт: {FunFact}\n");

        DisplaySkills();
    }

    public void DisplaySkills()
    {
        Console.WriteLine("Мои навыки в программировании:");
        foreach (var language in CodeLanguages)
        {
            Console.WriteLine($"- {language}");
        }
        Console.WriteLine("\nИнструменты, которые я использую:");
        foreach (var tool in Tools)
        {
            Console.WriteLine($"- {tool}");
        }
    }
}
```

💻 Разработчик десктопных приложений на **C#** для Windows  
🖥️ Бэкенд разработчик на **Python**/**C#**  
🧑‍💼 Опыт проектного менеджмента и руководства командой  
⚙️ Понимание и работа с микросервисной архитектурой 

💼 Разрабатываю приложения для образования, провожу обучение Python и C#.  

---

## ✨ Мотивационная фраза  
_"Код для меня — это не просто работа, а искусство и возможность улучшать мир."_  

---

## 🧠 В чем я разбираюсь:
🐳 **Микросервисы:** Использую Docker и Kubernetes для создания надежных решений.  
🔄 **CI/CD:** Настраиваю пайплайны с помощью Jenkins.  
🌐 **API разработка:** Работаю с ASP.NET, Blazor, Django, Flask, FastAPI, Selenium  для интеграции и тестирования.  
🗃️ **Базы данных:** PostgreSQL, MySQL, SQLite, MSSQL Server, MongoDB, Redis.  
🎓 **Обучение:** Провожу лекции и воркшопы по Python и C#.

---


## 💡 Навыки и технологии  

### Языки программирования:  
<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="40" alt="C# logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="C++ logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="Java logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" height="40" alt="Kotlin logo" />
  <img width="12" />
</div>  

### Базы данных:  
<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="PostgreSQL logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="MySQL logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" height="40" alt="SQL Server logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="40" alt="SQLite logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="40" alt="redis logo"  />
  <img width="12" />
</div>

### Инструменты разработки:  
<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" height="40" alt="PyCharm logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="VS Code logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" height="40" alt="Visual Studio logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="Git logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="Kubernetes logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=jenkins" height="40" alt="Jenkins logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="40" alt="apachekafka logo"  />
</div>


---

## 📈 Статистика  
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Antongo22&hide_title=true&show_icons=true&count_private=true&theme=dark&hide_border=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Antongo22&layout=compact&theme=dark&hide_border=true" height="150" alt="Top Languages" />
  <img src="https://streak-stats.demolab.com?user=Antongo22&theme=dark&hide_border=true" height="150" alt="Streak Stats" />
</div>

---

## 🏆 Достижения  
🎯 Решено **N задач** на [LeetCode](https://leetcode.com/u/Antongo22/).  
🏅 Постоянное участие в хакатонах и образовательных проектах.  

---



## ✨ Личностные качества  
🎯 Ориентация на результат  
🧑‍🤝‍🧑 Лидерские качества  
📘 Способность к обучению  
🗣️ Коммуникабельность  

---

<div align="center">
  <img height="200" src="https://gifdb.com/images/high/homelander-gif-file-9427kb-wsek911zujaibnb0.webp" alt="Motivational GIF" />
</div>  


