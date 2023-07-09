<p align="center">
  <img src="https://media1.giphy.com/media/QNFhOolVeCzPQ2Mx85/giphy.gif" width="20%">
  <br><br>
  <samp>
    I'm Emran Imam :wave:
    <br><br>
    I work as a Mobile 📱 and Web 🌐 developer!
    <br><br>
    <a href="https://www.facebook.com/emran.imam" target="_blank"><img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" width="30px" alt="Facebook"></a>&nbsp; &nbsp;<a href="mailto:emran.imam@gmail.com" target="_blank"><img src="https://img.icons8.com/fluent/48/000000/gmail.png" width="30px" alt="Facebook"></a> &nbsp; &nbsp;<a href="https://www.linkedin.com/in/emran-imam/" target="_blank"><img src="https://img.icons8.com/color/48/000000/linkedin.png" width="30px" alt="Facebook"></a> &nbsp; &nbsp;<a href="https://twitter.com/emranimam" target="_blank"><img src="https://img.icons8.com/color/48/000000/twitter.png" width="30px" alt="Facebook"></a> &nbsp; &nbsp;
  </samp>
</p>

#### A Computer Science Graduate and Freelance Programmer

```
{
   "🧑‍💻working_on":[
      "JobsNavi"
   ],
   "📚learning":[
      "Dart",
      "Flutter",
      "NodeJS",
      "VueJS"
   ],
   "💬ask_me":[
      "Flutter",
      "Dart"
   ],
   "🎯fun_fact":[
      "🎮",
      "☕"
   ],
   "💻technologies":{
      "frontEnd":[
         "HTML5",
         "CSS",
         "JS",
         "Flutter"
      ],
      "backEnd":[
         "PHP",
         "Laravel",
         "Dart"
      ],
      "databases":[
         "SQL",
         "Firebase",
         "SQLite"
      ]
   }
}
```

#### profile.dart
<details>
  <summary>Click to expand!</summary>
  
  ```
class Profile {
  List<String> workingOn;
  List<String> learning;
  List<String> askMe;
  List<String> funFact;
  Technologies technologies;

  Profile(
      {this.workingOn,
      this.learning,
      this.askMe,
      this.funFact,
      this.technologies});

  Profile.fromJson(Map<String, dynamic> json) {
    workingOn = json['🧑‍💻working_on'].cast<String>();
    learning = json['📚learning'].cast<String>();
    askMe = json['💬ask_me'].cast<String>();
    funFact = json['🎯fun_fact'].cast<String>();
    technologies = json['💻technologies'] != null
        ? new Technologies.fromJson(json['💻technologies'])
        : null;
  }

  Map<String, dynamic> toJson() {
    final Map<String, dynamic> data = new Map<String, dynamic>();
    data['🧑‍💻working_on'] = this.workingOn;
    data['📚learning'] = this.learning;
    data['💬ask_me'] = this.askMe;
    data['🎯fun_fact'] = this.funFact;
    if (this.technologies != null) {
      data['💻technologies'] = this.technologies.toJson();
    }
    return data;
  }
}

class Technologies {
  List<String> frontEnd;
  List<String> backEnd;
  List<String> databases;

  Technologies({this.frontEnd, this.backEnd, this.databases});

  Technologies.fromJson(Map<String, dynamic> json) {
    frontEnd = json['frontEnd'].cast<String>();
    backEnd = json['backEnd'].cast<String>();
    databases = json['databases'].cast<String>();
  }

  Map<String, dynamic> toJson() {
    final Map<String, dynamic> data = new Map<String, dynamic>();
    data['frontEnd'] = this.frontEnd;
    data['backEnd'] = this.backEnd;
    data['databases'] = this.databases;
    return data;
  }
}
```
</details>



[![Github Stats By Anurag](https://github-readme-stats.vercel.app/api?username=emran92&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/anuraghazra/github-readme-stats)

<p align="center">
  Made with :blue_heart: &nbsp;using GitHub Markdown &nbsp;:arrow_down:
</p>
