Hi there 👋, I'm Min Thant Kyaw

About Me

```java
@Entity
public class Developer {

    @Id
    private String name = "Min Thant Kyaw";

    private String role =
        "Software Enginner";

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
