/*U10316044
 *周東誼
 *11.10
 *MyStack
 */


import java.util.ArrayList;
import java.util.Scanner;


class MyStack extends ArrayList<Object>{

  public boolean isEmpty() {                      //return true if this stack is empty
    return super.isEmpty();
  }

  public int getSize() {                         //return numbers 
    return super.size();
  }

  public Object peek() {                         //return the top element (no remove)
    return super.get(getSize() - 1);
  }

  public Object pop() {                          //return the top element (yes remove)
    Object o = super.get(getSize() - 1);
    super.remove(getSize() - 1);
    return o;
  }

  public void push(Object o) {                   //adds a new element to top in stack 
    super.add(o);
  }

  @Override                                       /** Override the toString in the Object class */
  public String toString() {
    return "stack: " + super.toString();
  }
}

