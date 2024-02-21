### Welcome to my Github page!

<!--
**Donatello-Carboni/Donatello-Carboni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<p align="center">
<!-- <video autoplay loop>
  <source src="./github_banner.mp4" type="video/mp4">
</video> -->
  <img src="./github.gif" alt="Alt Text" style="width: 200%; height: auto;"> 
</p>

```java
public class ComputerScientist {
  private String name;
  private String university;
  private String[] interests;

  public ComputerScientist() {
    this.name = "Donatello Grahame Carboni";
    this.university = "University of Pretoria";
    this.interests = new String[] {"My girlfriend", "Artificial Intelligence", "Linux",
                                   "Cryptocurrency", "Formula 1"};
  }

  public void sayHi() {
    System.out.println("Hi, I am " + name + " and I am a third year student at the " +
                       university + "!");
    System.out.println("I use Arch BTW");
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
