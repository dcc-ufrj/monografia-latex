/**
 * Block comment
 *
 **/
class Dog {

  // line comment
  int age;
  
  public Dog(int age) {
    this.age = age;
  }

  private static String sound() {
    return "Au";
  }
  
  public final void say() {
    System.out.println(Dog.bark());
  }
  
  @Override
  public String toString() {
    return "{DOG}";
  }
  
  public void setAge(int age) {
    this.age = age;
  }
  
  public int getAge() {
    return this.age;
  }
}