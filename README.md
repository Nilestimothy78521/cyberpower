# cyberpower
cyberpower
import java .util.LinkedList;
import java.lang.reflect.Array;

public class UnsortedHashSet<E> {

  private static final double LOAD_FACTOR_LIMIT = 0.7;

  private int size;
  private LinkedList<E>[] con;

  public UnsortedHashSet() {
    con  = (LinkedList<E>[])(new LinkedList [10]);
  }

  Ppublic boolean add(E obj) {
    int oldSize = size;
    int index = Math.abs(obj.hashcode()) % con.length; 
    if(con[index] == null)
        con[index] = new LinkedList 
    
  
