class Time
{
    int hours, minutes, seconds;

    // Constructor 1: No arguments
    Time()
    {
        hours = 0;
        minutes = 0;
        seconds = 0;
    }

    // Constructor 2: Seconds
    Time(int s)
    {
        hours = s / 3600;
        minutes = (s % 3600) / 60;
        seconds = s % 60;
    }

    // Constructor 3: Hours, minutes and seconds
    Time(int h, int m, int s)
    {
        hours = h;
        minutes = m;
        seconds = s;
    }

    void display()
    {
        System.out.println("Time = " + hours + " hours "
                + minutes + " minutes " + seconds + " seconds");
    }
}

class ConstructorOverloading
{
    public static void main(String args[])
    {
        Time t1 = new Time();
        Time t2 = new Time(3665);
        Time t3 = new Time(2, 30, 45);

        System.out.println("Using Default Constructor:");
        t1.display();

        System.out.println("\nUsing Constructor with Seconds:");
        t2.display();

        System.out.println("\nUsing Constructor with Hours, Minutes and Seconds:");
        t3.display();
    }
}
