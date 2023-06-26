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
