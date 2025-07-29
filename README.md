# who.md
# This is TangJin.
> #### Who is he? He is the following, introduced with some random code...
```java
Human TangJin = new Human("TangJin", Gender.MALE);

TangJin.setFrom(
    Country.TAIWAN.withRegions(
        City.HSINCHU,
        County.HSINCHU,
        City.TAIPEI
    )
);

TangJin.addWork(
    Career.SOFTWARE_ENGINEER.withSkills(
        "Kotlin", "Java", "JavaScript", "HTML", "CSS",
        "Python", "PHP", "C", "C++", "C#",
        "React", "SQL", "Linux"
    )
);
TangJin.addWork(Career.INVESTOR);

TangJin.addHobbies(
    Hobby.CODING,
    Hobby.TRAVELLING,
    Hobby.BIKING,
    Hobby.MOUNTAIN_CLIMBING,
    Hobby.ALGORITHM_RESEARCH,
    Hobby.SELF_EXPLORING
);

TangJin.setWorks(List.of(
    new MinecraftPlugin("BungeeCord"),
    new MinecraftPlugin("Spigot"),
    new MinecraftPlugin("Folia"),
    new MinecraftPlugin("Velocity"),
    new Group("TJService")
));

TangJin.think("I will never give up, though there is still a far way to reach home.");
TangJin.setDiscord("@tangjin.equals.to.tj");
TangJin.setEmail("helloworld@tjdev.org");
TangJin.go("https://tjdev.org/");
```
