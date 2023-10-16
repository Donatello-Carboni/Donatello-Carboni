### Hi there! 👋

<!--
**Donatello-Carboni/Donatello-Carboni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<h1 align="center">
  <img src="./github_profile.webp" alt="Alt Text" loop>
</h1>

```java
public class ComputerScientist {
  private String name;
  private String university;
  private String[] interests;

  public ComputerScientist() {
    this.name = "Donatello Grahame Carboni";
    this.university = "University of Pretoria";
    this.interests = new String[] {"My girlfriend", "Artificial Intelligence",
                                   "Cryptocurrency", "Formula 1"};
  }

  public void sayHi() {
    System.out.println("Hi, I am " + name + " and I am a student at the " +
                       university + "!");
  }

  public void sayInterests() {
    System.out.println("My interests are: ");
    for (String interest : interests) {
      System.out.println(interest);
    }
  }

  public static void main(String[] args) {
    ComputerScientist me = new ComputerScientist();
    me.sayHi();
    me.sayInterests();
  }
}
```
