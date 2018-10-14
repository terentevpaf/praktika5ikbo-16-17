# praktika5ikbo-16-17
# ИКБО-16-17 Терентьев Павел Вадимович
# Вариант №1

<pre>
public class Main {

    public static void practFunc(int number)
    {
        if(number != 0)
        {
            boolean key = false;
            for (int index = number; index >= 1; index--)
            {
                if(key == false)
                {
                    practFunc(number-1);
                    key = true;
                }
                System.out.print(number + ", ");
            }
        }
    }

    public static void main(String[] args) {
        int number = 4;
        practFunc(number);
    }
}
</pre>
