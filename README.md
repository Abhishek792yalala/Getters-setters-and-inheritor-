# Getters-setters-and-inheritor-
//Problem:  Using setters, getters and inheritor 

class Parent{

  int a;

  public void setA(int a) {

    this.a = a;

  }

  public int getA() {

    return a;

  }

}

class Child extends Parent{

  int b;

  public void setB(int b){

    this.b=b;

  }

  public int  getB(){

    return b;

  }

}

class Code{

  public static void main(String... args){

    Parent p=new Parent();

    Child c=new Child();

    p.setA(1);

    System.out.println("The value of a is: "+ p.getA());

    c.setB(2);

    System.out.println("The value of b is : "+ c.getB());

  }

}

/*

The value of a is: 1

The value of b is : 2

 */
