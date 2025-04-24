# AP-Assignment-4
Q. Write a program that demonstrates searching for an element in a HashMap by key.
##
import java.util.HashMap;
public class HashMapSearchExample {
    public static void main(String[] args) {
        HashMap<String, String> capitalCities = new HashMap<>();
        capitalCities.put("India", "New Delhi");
        capitalCities.put("USA", "Washington, D.C.");
        capitalCities.put("Japan", "Tokyo");
        capitalCities.put("France", "Paris");
        String searchKey = "Japan";
        if (capitalCities.containsKey(searchKey)) {
            System.out.println("The capital of " + searchKey + " is " + capitalCities.get(searchKey));
        } else {
            System.out.println(searchKey + " is not in the map.");
        }
    }
}
