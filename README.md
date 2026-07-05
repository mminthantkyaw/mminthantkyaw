Hi there 👋, I'm Min Thant Kyaw

Full-Stack Developer

About Me

```java
@Entity
public class Developer {

    @Id
    private String name = "Min Thant Kyaw";

    private String role =
        "Full-Stack Developer";

    @ElementCollection
    private List<String> skills = List.of(
        "Java",
        "Spring Boot",
        "React",
        "MySQL",
        "Git"
    );

    private String Obsessions =
        "Building morden, clean, and scalable web applications";

    private String status =
        "Always Learning New Things";
}
```
