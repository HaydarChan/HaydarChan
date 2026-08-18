# Hi, there! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px" alt="Waving hand">

> I'm an Informatics Engineering graduate from Bandung Institute of Technology 🇮🇩

### 🐍 Profile
```python
from dataclasses import dataclass
from typing import List

@dataclass
class Developer:
    name: str        # 👤
    role: List[str]  # 💼
    location: str    # 📍
    education: str   # 🎓
    interests: List[str]  # 🎯
    languages: List[str]  # ⚡

    def greeting(self) -> str:
        return "👋 Hi, I'm Atqiya! Focused on building resilient backend services and high-performance systems."

atqiya = Developer(
    name="Atqiya",
    role=["Software Engineer", "Design Engineer"],
    location="Indonesia",
    education="Informatics Engineering graduate from Bandung Institute of Technology",
    interests=["Software Engineering", "AI", "UX Design", "Stock Market"],
    languages=["Go", "Java", "Python", "TypeScript", "JavaScript", "Dart"],
)

print(atqiya.greeting())
```

---

### Connect with Me

* **LinkedIn:** [linkedin.com/in/atqiyahaydar](https://linkedin.com/in/atqiyahaydar)
* **LeetCode:** [leetcode.com/u/ashhforrd](https://leetcode.com/u/ashhforrd/)
* **Email:** [atqiyahaydar15@gmail.com](mailto:atqiyahaydar15@gmail.com)
