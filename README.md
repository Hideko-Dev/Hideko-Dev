<p align="left">
 <img src="https://media.discordapp.net/attachments/1103327372025012255/1122804703709900921/1687767138502.png?width=1349&height=449" width="400">
 <img src="https://media.discordapp.net/attachments/1103327372025012255/1122804703483416647/1687767471706.png?width=1349&height=449" width="400">
 <img src="https://media.discordapp.net/attachments/1103327372025012255/1122804702879428699/1687767767532.png?width=1349&height=449" width="410">
 <img src="https://media.discordapp.net/attachments/1103327372025012255/1122804703214964776/1687767606341.png?width=1349&height=449" width="410">
 

` C:\Profile.kt `
```kotlin
package dev.hideko.profile

import dev.hideko.messages
import dev.hideko.skills
import com.github.profile

class Hideko : Profile() {
    override fun myProfile() {
        var message = {
        " Hello! I'm Hideko, Student. ",
        " I am always playing with my friends and doing many other things. ",
        " My hobby is playing. I often work on development. "
        }
    }

    override fun mySkill() {
        var html = "perfect"
        var css = "little"
        var python = "little"
        var ruby = "little"
        var csharp = "middle"
        var skript = "perfect"
        var kotlin = "perfect"
        var java = "perfect"
        var perfect = {
        "HTML", "Skript", "Kotlin", "Java" 
        }
        var middle {
        "python", "csharp"
        }
        var little {
        "CSS", "Python", "Ruby"
        }
    }
}

```
