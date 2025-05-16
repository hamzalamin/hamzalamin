# LAMIN_HamzaTheUnregistered

```java
/**
 * @author LAMIN Hamza
 * @version 1.0
 * A Full-Stack Developer focused on Java & Angular
 * Based in Agadir, Morocco 🇲🇦
 */
public class Developer {
    
    // Personal Information
    private final String name = "LAMIN Hamza";
    private final String role = "Full-Stack Developer";
    private final String location = "Agadir, Morocco";
    
    // Contact Information
    public static class Contact {
        public final String email = "hamzalamin80@gmail.com";
        public final String linkedin = "www.linkedin.com/in/hamza-lamin-a0440a296";
        public final String twitter = "https://www.x.com/FlHemza";
    }
    
    /**
     * My tech stack and proficiency levels
     */
    public class Skills {
        // Frontend Technologies
        private final Map<String, SkillLevel> frontend = Map.of(
            "Angular", SkillLevel.INTERMEDIATE,
            "React.js", SkillLevel.INTERMEDIATE,
            "JavaScript", SkillLevel.INTERMEDIATE
        );
        
        // Backend Technologies
        private final Map<String, SkillLevel> backend = Map.of(
            "Java", SkillLevel.INTERMEDIATE,
            "PHP", SkillLevel.ADVANCED,
            "TypeScript", SkillLevel.INTERMEDIATE,
            "Laravel", SkillLevel.ADVANCED,
            "Spring Boot", SkillLevel.INTERMEDIATE,
            "Hibernate", SkillLevel.INTERMEDIATE,
            "Jakarta EE", SkillLevel.INTERMEDIATE,
            "JPA", SkillLevel.INTERMEDIATE,
            "Spring Framework", SkillLevel.INTERMEDIATE
        );
        
        // Database Systems
        private final Map<String, SkillLevel> databases = Map.of(
            "MySQL", SkillLevel.ADVANCED,
            "PostgreSQL", SkillLevel.ADVANCED,
            "MongoDB", SkillLevel.INTERMEDIATE
        );
        
        // DevOps Tools
        private final Map<String, SkillLevel> devops = Map.of(
            "Docker", SkillLevel.INTERMEDIATE,
            "Git", SkillLevel.ADVANCED,
            "Maven", SkillLevel.INTERMEDIATE,
            "Jenkins", SkillLevel.INTERMEDIATE,
            "GitHub Actions", SkillLevel.INTERMEDIATE
        );
    }
    
    // Skill level enum
    private enum SkillLevel {
        BEGINNER, INTERMEDIATE, ADVANCED
    }
    
    /**
     * Areas of interest in the tech world
     * @return List of my current interests
     */
    public List<String> getInterests() {
        return Arrays.asList(
            "Web Development",
            "Machine Learning"
        );
    }
    
    /**
     * Something interesting about me
     * @return A fun fact
     */
    public String getFunFact() {
        return "I love tripping around new places, playing football with friends, " +
               "and swimming to relax and stay fit!";
    }
    
}
```

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hamzalamin&show_icons=true&theme=radical)

## 🔥 Streak Stats

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=hamzalamin&theme=dark)

## 🏆 GitHub Trophies

![](https://github-profile-trophy.vercel.app/?username=hamzalamin&theme=radical&no-frame=false&no-bg=false&margin-w=4)

## 👨‍💻 My Coding Journey

```java
try {
    while(alive) {
        coffee.drink();
        code.write();
        knowledge.expand();
        
        if(problems.exist()) {
            problems.solve();
        }
        
        energy.recharge();
    }
} catch(BurnoutException e) {
    self.takeBreak();
    inspiration.find();
    continue;
}
```

